# Data Quality Report

**Project:** Global Agricultural Market Intelligence Platform
**Scope:** 2001–2020, `marts` schema (DuckDB), FAOSTAT-derived data
**Companion document to:** `business_insights_report.md`

This document records data limitations, known issues, validation checks, and assumptions underlying the KPIs used in the Business Insights Report. It is intended for analysts, data engineers, and anyone extending or maintaining this analysis — not for a business stakeholder audience.

---

## 1. Data Sources by Analysis Area

| Analysis Area | Tables Used |
|---|---|
| Food Security Analytics | `fact_food_security__data`, `fact_socioeconomic__population` |
| Agricultural Productivity | `fact_production__crops_livestock`, `fact_land_resources__inputs_fertilizersnutrient`, `fact_land_resources__environment_pesticides` |
| Trade Intelligence | `fact_trade__trade`, `fact_trade__matrix` |
| Commodity Market Analytics | `dim_commodity_prices__prices`, `dim_commodity_prices__indices`, `fact_prices__consumerpriceindices`, `fact_prices__rate` |

---

## 2. Data Limitations and Indicator Selection

### Food Security

No single FAOSTAT indicator is both a direct hunger measure *and* has full 2001–2020, all-country coverage. The most direct indicator ("Prevalence of moderate/severe food insecurity") only exists from 2014 onward. The analysis instead uses the best available full-scope proxy — the dietary energy adequacy ratio (`supply_kcal ÷ requirement_kcal`) — as the primary signal, and does not attempt to backfill the pre-2014 direct indicator.

### Agricultural Productivity

KPIs are built on a single representative crop, **Wheat**, chosen for full 2001–2020 coverage across 159 countries. Extending to other crops or an all-crop aggregate is a straightforward follow-up (same query pattern, different `item` filter) but was not done in this deliverable.

FAOSTAT's raw `Yield` element is commonly reported in hectograms per hectare (hg/ha), not tonnes/ha directly. This has not yet been confirmed against the `unit` column in `marts` — a raw hg/ha value divided by 10,000 gives tonnes/ha, and mislabeling the axis in a dashboard would mislead a policy audience. **Action item: confirm unit before this reaches Power BI.**

Fertilizer and pesticide intensity are computed independently and have not yet been joined to yield at the country-year level. The correlation implied by the business question ("does more fertilizer explain higher yield") is not directly tested in the current KPI set — this is a natural next step once the join is built.

### Trade Intelligence

This problem's four KPIs answer two related but genuinely distinct questions, using two different commodities, because the two source tables don't share item coverage:

- **KPI 1 & 4** use `fact_trade__trade` with item `"Pesticides (total)"` — the best-covered item in that table (280 countries, full 2001–2020). `fact_trade__trade`'s entire 37-item universe is pesticides/agrochemicals, with zero overlap into `fact_trade__matrix`'s item list.
- **KPI 2 & 3** use `fact_trade__matrix` with item `"Food preparations n.e.c."` — the best-covered item there (186 reporters, 200 partners, full 2001–2020). `fact_trade__matrix`'s item universe is entirely processed food/beverage/agricultural commodities and has no pesticide coverage at all.

This is a genuine data-scope constraint, not an analytical choice. Any dashboard combining these KPIs must label this distinction explicitly, or it will imply a single consistent "trade dependency" narrative where there are actually two separate ones.

**KPI 1 formula note:** the originally planned formula was `imports ÷ (production + imports − exports)`, using `fact_production__crops_livestock`'s `Production` element as the domestic-supply denominator. Since pesticides have no crop/livestock "production" figure in that table, KPI 1 uses a trade-only ratio instead: `imports / (imports + exports) × 100`. This is a narrower but still valid signal — of a country's total trade flow in this item, what share is imports.

**KPI 3 threshold note:** the "significant partner" threshold (≥5% of import value) is a placeholder, not yet validated against the real distribution of partner shares. Revisit before this is presented as a fixed policy threshold.

### Commodity Market Analytics

`local_price_yoy_pct_approx` (used in the currency-adjusted price exposure KPI) is a first-order additive approximation (`usd_pct + fx_pct`), not the exact compounded formula (`(1 + usd_pct/100) × (1 + fx_pct/100) − 1`). This differs by well under a percentage point at normal magnitudes but should be swapped for the precise compounded formula if extreme values (hyperinflation-era swings) ever need decimal-level accuracy.

---

## 3. Known Data Quality Issues

| Issue | Table | Detail | Status |
|---|---|---|---|
| Null year values | `fact_food_security__data` | `year` is NULL for 48.34% of rows in the current `marts` build — a year-range-string parsing issue. All KPI queries filter `WHERE year BETWEEN 2001 AND 2020`, which works correctly only on the ~52% of rows where `year` parsed. True underlying coverage may be modestly understated as a result. | Open — flagged as a staging-layer fix, not resolved in this analysis. |
| VARCHAR value column | `fact_food_security__data` | `value` is stored as VARCHAR and requires explicit casting in every query. | Handled in KPI queries; not fixed at source. |
| Unmatched partner codes | `fact_trade__matrix` | A partner-side check found 9 unmatched partner codes — confirmed to be uninhabited/remote territories (e.g., Bouvet Island, Wake Island), not regional aggregates. Real but small effect on partner-level KPIs. | Accepted, non-blocking. |
| Yield unit ambiguity | `fact_production__crops_livestock` | Raw `Yield` element is likely in hg/ha, not t/ha — not yet confirmed against the `unit` column. | Open — confirm before dashboard use. |
| Currency redenomination overlaps | `fact_prices__rate` | Several countries have overlapping currency records across redenomination events (e.g., Eurozone accession, Turkmenistan's manat redenomination, Venezuela's redenominations, South Sudan's currency introduction). KPI 4 restricts each country to `element_code = 'LCU'` and its most-recently-used currency to avoid mixing pre- and post-changeover rates. | Handled in KPI logic. |

---

## 4. Aggregate Exclusion (Cross-Cutting Methodology)

FAOSTAT's `area_code` field mixes real countries/territories with regional, continental, and income-group aggregate rows ("World," "Sub-Saharan Africa," "Small Island Developing States," various income-group composites) within the same column, across every source table used in this project.

**Validated rule:** genuine country/territory `area_code` values are consistently below 5000; aggregate rows (regions, continents, income groups, and "excluding intra-trade" variants) are consistently 5000 or above. This numeric-range filter is applied directly in every KPI query across all four analysis areas, on both sides of bilateral tables (reporter and partner) where applicable.

For `fact_socioeconomic__population` specifically: this table stores one row per country **per year** (spanning 1950–2100), not one row per country. Any usage of this table for country-list purposes (e.g., population weighting, exclusion checks) must reference a `DISTINCT area_code` list or perform year-matched joins — not a plain unconditional join — to avoid unintentionally multiplying rows.

---

## 5. Validation Checks Performed

- Each KPI notebook confirms exact `item`/`element` string matches and expected year coverage (2001–2020) against the live `marts` schema before computing any KPI, to catch silent breakage from upstream schema changes.
- Guard checks raise an explicit error if a required item/element combination returns zero rows, rather than allowing an empty or partial result to pass downstream silently.
- Row counts and distinct-country counts are logged at each KPI step to make coverage changes (e.g., from a filter) visible and auditable.
- Two-point trend comparisons (2001 vs. 2020) are used consistently across Food Security, Productivity, and Trade Intelligence as the standard "improving vs. declining" pattern. A full 20-year regression-slope approach would be a more robust follow-up across all three, since a two-point comparison is sensitive to a single anomalous value at either endpoint.

---

## 6. Outstanding Items for Future Work

- Confirm `fact_production__crops_livestock`'s yield unit (hg/ha vs. t/ha) against the `unit` column.
- Resolve the `fact_food_security__data.year` NULL-parsing issue at the staging layer.
- Join fertilizer and pesticide intensity to yield at the country-year level to directly test the input/output relationship.
- Validate the 5% "significant partner" threshold in the Trade Intelligence import-diversification KPI against the real distribution of partner shares.
- Extend Productivity KPIs beyond wheat to other crops or an all-crop composite.
- Apply capping, log-scaling, or explicit outlier handling to country-level commodity price KPIs (food inflation pass-through, currency exposure) before they reach a general dashboard audience, given extreme values from countries experiencing hyperinflation or currency collapse.

---

*This report should be read alongside the platform's architecture and workflow documentation for the underlying notebook structure, dbt modeling plans, and pipeline design.*
