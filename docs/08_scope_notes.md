# Scope Trimming Notes — Global Agricultural Market Intelligence Platform

**Year Range:** 2001–2020
**Status:** Historical scoping record — read alongside [`00_requirements.md`](00_requirements.md) for the finalized scope

This document preserves the original scope-trimming rationale from before analysis began: which business problems and modules were cut, why, and which specific source tables were excluded from the 2001–2020 analytical scope. `00_requirements.md` summarizes the *why*; this document provides the full detail, including the excluded-tables reference list.

---

## Original vs. Trimmed Scope

The platform was originally scoped around 8 business problems and 11 modules. It was trimmed to the 4 business problems and 6 modules described in [`00_requirements.md`](00_requirements.md), based on which tables had confirmed, complete 2001–2020 coverage.

## Users

The platform is designed for:

1. 🏛 Governments & Policymakers
2. 🌾 Agricultural Ministries
3. 🌍 International Organizations (FAO, World Bank, NGOs)
4. 🚢 Agricultural Exporters & Importers
5. 📈 Commodity Market Analysts
6. 🏢 Agribusiness Companies
7. 📊 Researchers & Data Analysts

## Business Problems Retained (4 of original 8)

See [`00_requirements.md`](00_requirements.md) Section 3 and [`06_business_insights_report.md`](06_business_insights_report.md) for the finalized questions, decisions supported, and tables used per business problem (Food Security, Agricultural Productivity, Trade Intelligence, Commodity Price Analysis).

## Dropped From Scope

- **Climate Impact** — folded into Productivity/Food Security as supporting weather/disaster context rather than a standalone module.
- **Supply Risk** — was a composite of Food Security + Trade + Climate; not a standalone module once those were addressed individually.
- **Sustainability** — largest table set (19 tables) considered for the platform; least central to the core portfolio story given the effort required.
- **Investment Prioritization** — weakest 2001–2020 coverage among the candidate problem areas; smallest expected return for the modeling effort required.

## Modules Retained (6 of original 11)

```
1. Executive Dashboard
2. Agriculture Analytics (Productivity)
3. Trade Intelligence
4. Food Security Analytics
5. Commodity Market Analytics
6. Country Benchmarking
```

> **Open item:** Country Benchmarking is listed here as a retained module but does not currently appear as a page in the Power BI dashboard (see [`05_powerbi_explanation.md`](05_powerbi_explanation.md), which documents 5 pages). This has not yet been reconciled — confirm whether Country Benchmarking was cut after this scoping document was written, or is still pending implementation.

## Strategic Objectives (as originally scoped)

1. Monitor global agricultural production.
2. Detect food security risks.
3. Analyze international agricultural trade.
4. Understand commodity price movements.
5. Compare countries across key agricultural and economic indicators.
6. Support evidence-based policy decisions.

---

## Tables Excluded From 2001–2020 Scope (Reference)

These tables do not have full 2001–2020 coverage and were not used as primary sources for any of the four retained business problems. Kept here for reference in case a future extension of the platform's year range or scope revisits them.

| Table | Year Range |
|---|---|
| `fact_commodity_balances___2010` | 2010–2023 |
| `fact_commodity_balances___2013_old_methodology` | 1961–2013 |
| `fact_commodity_balances__commoditybalances_non_food` | 1961–2013 |
| `fact_food_security__food_and_diet` | 2010–2023 |
| `fact_food_security__foodbalancesheets` | 2010–2023 |
| `fact_food_security__historic` | 1961–2013 |
| `fact_food_security__shipments_wfp` | 1988–2016 |
| `fact_forestry__flows` | 1997–2018 |
| `fact_forestry__pulp_paper_survey` | 2020–2026 |
| `fact_investment_finance__archive` | 1961–2005 |
| `fact_investment_finance__investment_machinery` | 1961–2009 |
| `fact_land_resources__budget` | 1961–2018 |
| `fact_land_resources__disposal` | 1990–2019 |
| `fact_land_resources__inputs_fertilizersarchive` | 1961–2001 |
| `fact_land_resources__inputs_fertilizersproduct` | 2002–2023 |
| `fact_prices__coahd` | 2017–2024 |
| `fact_prices__pricesarchive` | 1966–1990 |
| `fact_production__sua_crops_livestock` | 2010–2023 |
| `fact_research_capacity___archive` | 1981–2016 |
| `fact_research_capacity__asti_expenditures` | 2004–2023 |
| `fact_research_capacity__asti_researchers` | 2004–2023 |

---

## Tables Confirmed for 2001–2020 Coverage (by Business Problem, as Originally Scoped)

This is the original per-problem table list from the scoping phase. See [`06_business_insights_report.md`](06_business_insights_report.md) Section 1 for the finalized "Key models" list per business problem, which reflects the tables actually used in reporting.

**Food Security:**
- `fact_food_security__data` (2000–2025)
- `fact_production__crops_livestock` (1961–2024)
- `fact_trade__matrix` (1986–2024)
- `fact_socioeconomic__population` (1950–2100)
- `dim_weather` (2000–2025) — supporting context, not a standalone module

**Agricultural Productivity:**
- `fact_production__crops_livestock` (1961–2024)
- `fact_production__indices` (1961–2024)
- `fact_land_resources__inputs_fertilizersnutrient` (1961–2023)
- `fact_land_resources__environment_pesticides` (1990–2020)
- `fact_land_resources__inputs_landuse` (1961–2025)
- `fact_socioeconomic__population` (1950–2100)
- `dim_weather` (2000–2025) — supporting context

**Trade Intelligence:**
- `fact_trade__matrix` (1986–2024)
- `fact_trade__trade` (1961–2023)
- `fact_trade__fertilizers_detailedtradematrix` (1990–2023)
- `fact_production__crops_livestock` (1961–2024)

**Commodity Price Analysis:**
- `dim_commodity_prices__prices` (1960–2026)
- `dim_commodity_prices__indices` (1960–2026)
- `fact_prices__deflators` (1970–2024)
- `fact_prices__rate` (1970–2026)
- `fact_prices__consumerpriceindices` (2000–2025)
- `fact_trade__matrix` (1986–2024) — supporting context

> Note: `fact_prices__prices` (1991–2025) was in the original candidate list for Commodity Price Analysis but marked "Not using" during scoping.

---

*This document is historical scoping material, retained for reference. For the finalized, current scope, see [`00_requirements.md`](00_requirements.md).*