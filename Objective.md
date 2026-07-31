# Global Agricultural Market Intelligence Platform — Trimmed Scope

**Year Range:** 2001–2020
**Goal:** Decision-support platform integrating agriculture, trade, and food security data.

---

## Users

1. 🏛 Governments & Policymakers
2. 🌾 Agricultural Ministries
3. 🌍 International Organizations (FAO, World Bank, NGOs)
4. 🚢 Agricultural Exporters & Importers
5. 📈 Commodity Market Analysts
6. 🏢 Agribusiness Companies
7. 📊 Researchers & Data Analysts

---

## Business Problems (4 of original 8)

### Problem 1 — Food Security

**Question:** Which countries are becoming food insecure?

**Decisions supported:**
- Which countries need food assistance?
- Where should food reserves be increased?
- Which countries are at risk next year?

**Tables (2001–2020 coverage confirmed):**
- fact_food_security__data (2000–2025)
- fact_production__crops_livestock (1961–2024)
- fact_trade__matrix (1986–2024)
- fact_socioeconomic__population (1950–2100)
- dim_weather (2000–2025) — supporting context, not a standalone module

---

### Problem 2 — Agricultural Productivity

**Question:** Why are some countries producing more than others?

**Decisions supported:**
- Increase fertilizer usage?
- Improve irrigation?
- Invest in technology?
- Change crop selection?

**Tables (2001–2020 coverage confirmed):**
- fact_production__crops_livestock (1961–2024)
- fact_production__indices (1961–2024)
- fact_land_resources__inputs_fertilizersnutrient (1961–2023)
- fact_land_resources__environment_pesticides (1990–2020)
- fact_land_resources__inputs_landuse (1961–2025)
- fact_socioeconomic__population (1950–2100)
- dim_weather (2000–2025) — supporting context

---

### Problem 3 — Trade Intelligence

**Question:** How dependent is each country on imports and exports?

**Decisions supported:**
- Diversify suppliers
- Find new export markets
- Reduce import dependency

**Tables (2001–2020 coverage confirmed):**
- fact_trade__matrix (1986–2024)
- fact_trade__trade (1961–2023)
- fact_trade__fertilizers_detailedtradematrix (1990–2023)
- fact_production__crops_livestock (1961–2024)

---

### Problem 4 — Commodity Price Analysis

**Question:** Why are agricultural commodity prices changing?

**Decisions supported:**
- Buy now or later
- Export now or later
- Government price intervention

**Tables (2001–2020 coverage confirmed):**
- dim_commodity_prices__prices (1960–2026)
- dim_commodity_prices__indices (1960–2026)
- fact_prices__prices (1991–2025) (Not using)
- fact_prices__deflators (1970–2024)
- fact_prices__rate (1970–2026)
- fact_prices__consumerpriceindices (2000–2025)
- fact_trade__matrix (1986–2024) — supporting context

---

## Dropped (out of scope for now)

- Climate Impact — folded into Productivity/Food Security as supporting weather/disaster context
- Supply Risk — was a composite of Food Security + Trade + Climate; not a standalone module
- Sustainability — largest table set (19 tables), least central to portfolio story
- Investment Prioritization — weakest 2001–2020 coverage, smallest ROI for effort

---

## Modules (6 of original 11)

```
1. Executive Dashboard
2. Agriculture Analytics (Productivity)
3. Trade Intelligence
4. Food Security Analytics
5. Commodity Market Analytics
6. Country Benchmarking
```

---

## Strategic Objectives (trimmed to match scope)

1. Monitor global agricultural production.
2. Detect food security risks.
3. Analyze international agricultural trade.
4. Understand commodity price movements.
5. Compare countries across key agricultural and economic indicators.
6. Support evidence-based policy decisions.

---

## Tables excluded from 2001–2020 scope (reference)

These don't fully cover 2001–2020 and should not be used as primary sources for any module above:

| Table | Year Range |
|---|---|
| fact_commodity_balances___2010 | 2010–2023 |
| fact_commodity_balances___2013_old_methodology | 1961–2013 |
| fact_commodity_balances__commoditybalances_non_food | 1961–2013 |
| fact_food_security__food_and_diet | 2010–2023 |
| fact_food_security__foodbalancesheets | 2010–2023 |
| fact_food_security__historic | 1961–2013 |
| fact_food_security__shipments_wfp | 1988–2016 |
| fact_forestry__flows | 1997–2018 |
| fact_forestry__pulp_paper_survey | 2020–2026 |
| fact_investment_finance__archive | 1961–2005 |
| fact_investment_finance__investment_machinery | 1961–2009 |
| fact_land_resources__budget | 1961–2018 |
| fact_land_resources__disposal | 1990–2019 |
| fact_land_resources__inputs_fertilizersarchive | 1961–2001 |
| fact_land_resources__inputs_fertilizersproduct | 2002–2023 |
| fact_prices__coahd | 2017–2024 |
| fact_prices__pricesarchive | 1966–1990 |
| fact_production__sua_crops_livestock | 2010–2023 |
| fact_research_capacity___archive | 1981–2016 |
| fact_research_capacity__asti_expenditures | 2004–2023 |
| fact_research_capacity__asti_researchers | 2004–2023 |
