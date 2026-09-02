# Requirements Document — Global Agricultural Market Intelligence Platform

**Project:** Global Agricultural Market Intelligence Platform
**Prepared for:** International Development & Policy Analytics Lead
**Prepared by:** [Your Name] — Data/Analytics Engineer
**Date:** [scoping date, before analysis began]
**Status:** Finalized — used to scope the analysis in this repository

---

## 1. Background

Global agricultural and food-security data is scattered across multiple international sources — FAOSTAT, NASA POWER, the World Bank, EM-DAT — each with different formats, coverage windows, and update cadences. Governments, agricultural ministries, international organizations, and market analysts need a consolidated view of food security, productivity, trade dependency, and commodity price movements to make timely decisions, but no single accessible platform integrates these domains at country-year grain.

Leadership requested an analysis to answer a recurring cross-organizational question: **"Which countries are moving toward risk — on food security, on trade dependency, on production — and where should attention and resources go next?"**

## 2. Stakeholder & Original Ask

**Stakeholder:** International Development & Policy Analytics Lead, representing the platform's broader user base (governments, agricultural ministries, international organizations, exporters/importers, commodity analysts, agribusiness, researchers)

**Ask (paraphrased from intake conversation):**

> "We have twenty years of agricultural, trade, and price data sitting in disconnected FAOSTAT exports and other sources, but nobody can quickly answer which countries are becoming food insecure, why some countries produce more than others, how exposed countries are on trade, or why commodity prices move the way they do. Build something that turns this into a usable intelligence platform."

**Clarifying questions asked during scoping:**

- _Should this cover the full FAOSTAT table set (all ~30+ business problem areas originally proposed)?_ → No — scope was trimmed from an original 8 business problems and 11 modules down to 4 core business problems (Food Security, Agricultural Productivity, Trade Intelligence, Commodity Market Analysis) and 6 modules, based on which tables had confirmed, complete 2001–2020 coverage.
- _Should Climate Impact, Supply Risk, Sustainability, and Investment Prioritization be included as standalone modules?_ → No — Climate Impact was folded into Productivity/Food Security as supporting weather/disaster context; Supply Risk was a composite of already-included domains and not standalone; Sustainability (19 tables) and Investment Prioritization were dropped for weak 2001–2020 coverage and lower portfolio ROI relative to effort.
- _What time period should be covered?_ → 2001–2020, chosen because this is the window where all core tables have confirmed, complete coverage; several source tables extend further (e.g., population to 2100, commodity prices to 2026) but are constrained to this window for consistency across the platform.
- _Should the platform support real-time or near-real-time data?_ → No — this is a historical, batch-processed analytical platform, not a live monitoring system.

## 3. Scope

### In scope

- Food security risk identification: countries showing declining food security indicators, at-risk-next-year signals
- Agricultural productivity analysis: production trends, yield trends, and input (fertilizer, pesticide, land use) relationships
- Trade intelligence: import/export dependency and concentration risk by country
- Commodity market analysis: price movements, volatility, and currency/inflation pass-through effects
- Country-level benchmarking across the above domains
- Data quality assessment and validation at every pipeline layer before conclusions are drawn

### Out of scope

- Climate Impact as a standalone module (folded into Productivity/Food Security as supporting context)
- Supply Risk as a standalone module (composite of already-included domains)
- Sustainability analysis (19-table domain, weakest fit for this phase)
- Investment Prioritization analysis (weakest 2001–2020 coverage)
- Real-time or live data integration
- Causal analysis or predictive forecasting — this platform identifies patterns and historical trends, not proven cause-effect relationships or future projections
- Data outside the 2001–2020 window, even where source tables extend further

## 4. Success Criteria

This platform is considered complete when it can answer, with data-backed evidence, at country-year grain:

1. Which countries are showing declining food security indicators, and which are most at risk going forward?
2. Which countries are outperforming or underperforming on agricultural productivity, and how do input levels (fertilizer, pesticide, land use) relate to that?
3. How dependent is each country on agricultural imports and exports, and where is trade concentration risk highest?
4. Why are agricultural commodity prices changing, and how much of local price movement is attributable to currency effects versus global commodity trends?
5. Are the observed country-level patterns backed by validated, reproducible KPIs — not one-off notebook calculations — so that policy and investment decisions can rely on them?

Each answer must be traceable to a specific dbt reporting model, not a one-off notebook calculation, so that downstream users (dashboard viewers, analysts extending the platform) can trust and reproduce the finding.

## 5. Deliverables Agreed With Stakeholder

- A written findings report answering the questions above ([`06_business_insights_report.md`](06_business_insights_report.md))
- A validated, layered data pipeline (raw → staging → intermediate → marts → reporting) with automated quality checks at each stage ([`01_architecture_report.md`](01_architecture_report.md), [`03_data_quality_report.md`](03_data_quality_report.md))
- A 5-page Power BI dashboard serving pre-computed KPIs across all four business domains ([`05_powerbi_explanation.md`](05_powerbi_explanation.md))
- A documented data dictionary covering all raw and transformed tables ([`02_data_dictionary.md`](02_data_dictionary.md))
- A documented set of analysis assumptions and known limitations, so stakeholders understand what any given KPI does and does not capture ([`07_analysis_assumptions_and_limitations.md`](07_analysis_assumptions_and_limitations.md))

## 6. Constraints & Assumptions

- Historical dataset only (2001–2020) — no real-time data; findings reflect this period, not current conditions
- Source data quality varies by table; 3 of 369 raw tables have known duplicate-row issues in reference tables, documented and monitored rather than silently corrected
- Food security is measured via a dietary energy adequacy proxy, not a single universal hunger indicator, due to coverage gaps in more direct indicators before 2014
- Productivity KPIs are built on a single representative crop (wheat) rather than an all-crop composite, due to coverage completeness
- Trade intelligence KPIs draw on two source tables with non-overlapping item coverage (pesticides vs. processed food categories), meaning "trade dependency" findings represent two related but distinct signals, not one unified metric
- Findings are correlational and descriptive, not causal or predictive

---

_This document defines the scope agreed before analysis began. See [`06_business_insights_report.md`](06_business_insights_report.md) for the findings delivered against this scope, and [`01_architecture_report.md`](01_architecture_report.md) for technical implementation detail._
