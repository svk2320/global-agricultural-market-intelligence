# 🌾 Global Agricultural Market Intelligence Platform

### Twenty years of global agriculture, trade, and price data — turned into country-level risk signals

---

## The Business Problem

Global agricultural and food-security data is scattered across multiple international sources — FAOSTAT, NASA POWER, the World Bank, EM-DAT — each with its own format, coverage window, and update cadence. Governments, agricultural ministries, international organizations, and market analysts all need a consolidated view of food security, productivity, trade dependency, and commodity prices to act quickly, but no single accessible platform pulls these domains together at country-year grain.

Leadership framed the need like this:

> _"We have twenty years of agricultural, trade, and price data sitting in disconnected exports, but nobody can quickly answer which countries are becoming food insecure, why some countries produce more than others, how exposed countries are on trade, or why commodity prices move the way they do. Build something that turns this into a usable intelligence platform."_

This project was built to answer that — integrating 97M+ records across 369 source tables into a validated, decision-ready platform.

---

## Project at a Glance

| Area              | Details                                                                      |
| ----------------- | ---------------------------------------------------------------------------- |
| Role              | Analytics/Data Engineer                                                      |
| Dataset           | FAOSTAT, NASA POWER, World Bank Pink Sheet, EM-DAT — 2001–2020               |
| Scale             | 97M+ raw records · 369 raw tables · 100+ countries                           |
| Business Question | Which countries are moving toward risk, and where should attention go next?  |
| Analysis Focus    | Food security, agricultural productivity, trade dependency, commodity prices |
| Tools             | Python, DuckDB, dbt, PostgreSQL, Power BI                                    |
| Output            | 16 validated KPI models + 5-page Power BI dashboard                          |

---

## The Objective

Analyze twenty years of global agricultural data to determine:

- Which countries are showing declining food security indicators, and which are most at risk going forward?
- Which countries are outperforming or underperforming on agricultural productivity, and how do input levels relate to that?
- How dependent is each country on agricultural imports and exports, and where is trade concentration risk highest?
- Why are commodity prices changing, and how much of local price movement comes from currency effects versus global trends?

Explicitly out of scope: climate impact and supply risk as standalone modules (folded into the above as supporting context), sustainability and investment prioritization analysis (weaker data coverage, lower fit for this phase), real-time data, and causal or predictive claims — this platform identifies patterns, not proven cause-effect relationships or forecasts.

_(Full scoping document: [`docs/00_requirements.md`](docs/00_requirements.md); full scope-trimming rationale: [`docs/08_scope_notes.md`](docs/08_scope_notes.md))_

---

## The Approach

Before any finding could be trusted, the data had to be validated at every stage. 369 raw source tables were profiled, quality-checked, and audited before a single transformation was applied — 366 of 369 passed cleanly, with 3 known duplicate-row issues in reference tables tracked and documented rather than silently patched.

From there, data moved through a layered pipeline: staging (350 models) cleaned and standardized; intermediate (73 models) handled reusable joins and reshaping; marts (76 models) organized everything around the four business domains; and reporting (16 KPI models) pre-computed exactly what the dashboard needed. Power BI never touches raw data or intermediate logic — it connects only to a dedicated PostgreSQL serving layer, so every number on the dashboard traces back to a version-controlled dbt model.

_(Full technical detail: [`docs/01_architecture_report.md`](docs/01_architecture_report.md))_

---

## What the Data Actually Said

**1. Global food security improved on average — but that average hides real deterioration.**
The population-weighted food supply adequacy indicator rose from 1.49 (2001) to 1.64 (2020). But Syria, Venezuela, Egypt, and Nigeria all show clear downward trends — some of them despite still having comfortable absolute food-security levels. Trend direction matters as much as the current number when flagging risk.

**2. Productivity gains are wildly uneven, and they track policy stability as much as inputs.**
Iraq (+298%) and Kuwait (+193%) posted the largest wheat yield gains between 2001 and 2020 — both tied to post-conflict investment and targeted irrigation programs. The steepest declines (Lesotho, Angola, DPR Korea) cluster in conflict-affected or resource-constrained economies. Input access clearly matters, but policy continuity looks just as important.

**3. Trade dependency isn't one story — it's two.**
Some countries rely almost entirely on imports for key agricultural inputs (Albania sits at 91–100% import-dependent most years). Separately, a number of smaller exporters concentrate the bulk of a given export in a single trading partner. Both are real exposure signals, but they come from different data and shouldn't be blended into one "trade risk" number.

**4. Fertilizer prices rose faster than every other tracked commodity index.**
+114% between 2001 and 2020, versus +91% for food and +85% for agriculture overall. That has a direct knock-on effect for productivity: if input costs outpace output prices, it constrains which countries can actually afford input-intensive yield improvements.

**5. Price volatility spikes line up exactly with the crises you'd expect.**
Wheat price volatility peaked at 11.8% in 2010, with a second spike during the 2007–2008 global food price crisis (9.0–9.7%) — useful reference points for stress-testing buy/sell and price-intervention timing.

---

## So What Should the Business Actually Do?

1. **Prioritize food-assistance monitoring for Syria, Venezuela, Egypt, and Nigeria.** These show the clearest downward food-security trend in the dataset, even where absolute levels remain above the minimum threshold.
2. **Target productivity investment at stability, not just inputs.** The clearest yield gains came from countries undergoing agricultural modernization or post-conflict recovery — policy continuity and infrastructure investment may deliver returns as large as fertilizer or pesticide access alone.
3. **Flag single-partner trade exposure as a diversification priority.** Countries with one dominant export or import partner should be first in line for supplier or market diversification support.
4. **Treat fertilizer cost trends as an early-warning signal for productivity policy.** Since fertilizer prices are outpacing food and agriculture prices overall, rising input costs are a leading risk factor specifically for producers in lower-income countries.
5. **Use 2007–2008 and 2010 as reference case studies** when stress-testing buy/sell and government price-intervention strategies — these are the clearest historical examples of extreme volatility in the dataset.

---

## A Note on Open Items

Two things surfaced during documentation review that haven't been fully reconciled yet:

- **Wheat productivity country coverage** is cited as 159 countries in one document but the actual reporting tables suggest a country count closer to 121–124. Worth confirming against the source notebook before quoting either figure externally.
- **Country Benchmarking** appears as a planned module in early scoping but doesn't currently have a corresponding Power BI dashboard page. Status (cut vs. pending) is still unconfirmed.

Neither affects the core findings above, but both are worth resolving before presenting specific numbers in an interview or portfolio walkthrough.

---

## See It for Yourself

📊 **5-page Power BI dashboard** — Overview, Food Security, Agricultural Productivity, Trade Intelligence, Commodity Market Analysis. Powered entirely by pre-aggregated PostgreSQL reporting tables — no computation happens inside Power BI itself.

---

## Quick Start

**Prerequisites:** Python 3.11, Conda (Miniconda or Anaconda), PostgreSQL, Power BI Desktop, dbt Core 1.8.0

```bash
# Clone the repository
git clone <repository-url>
cd global-agricultural-market-intelligence-pvt

# Create the conda environment
conda env create -f environment.yml
conda activate global-agricultural-market-intelligence

# Install Python dependencies
pip install -r requirements.txt
```

From there, the pipeline runs through a sequence of `make` and `dbt` commands — see [`docs/04_data_pipeline_workflow.md`](docs/04_data_pipeline_workflow.md) for the full step-by-step execution order, from raw ingestion through to the PostgreSQL export that feeds Power BI.

---

## Skills Demonstrated

| Skill                            | How This Project Demonstrates It                                                                                          |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| End-to-end analytics engineering | Full pipeline from raw CSV ingestion to Power BI dashboard delivery                                                       |
| DuckDB analytical architecture   | 369-table raw schema, multi-layer transformation, audit schema for quality tracking                                       |
| Data quality engineering         | Multi-layer validation: Python audit scripts for raw data, dbt tests for transformations, notebook validation for KPIs    |
| Metadata automation              | Auto-generated metadata, data dictionary, and quality reports from DuckDB schema inspection                               |
| KPI engineering                  | 16 business KPIs computed in dbt, validated in notebooks, served through PostgreSQL                                       |
| BI serving architecture          | Dedicated PostgreSQL serving layer that decouples Power BI from the analytical engine                                     |
| Business analytics               | Four business domains with decision-support KPIs, trend analysis, and country-level rankings                              |
| dbt transformation modeling      | 515 SQL models organized across staging, intermediate, marts, and reporting layers with testing and dependency management |

---

## Lessons Learned

**Separating the analytical and BI layers is worth the extra step.** Initially, connecting Power BI directly to DuckDB seemed simpler. In practice, exporting reporting tables to PostgreSQL provided a stable, predictable serving layer that insulated the dashboard from analytical schema changes and eliminated performance concerns during dashboard refresh.

**KPI logic is better maintained in dbt rather than embedded only in Power BI.** Early in the project, some metric calculations were prototyped as DAX measures inside Power BI. This made them invisible to version control, untestable, and difficult to debug. Moving all KPI logic into dbt reporting models meant every metric was version-controlled, testable, and independently auditable.

**Automated metadata generation scales where manual documentation cannot.** With 369 raw tables and 515 dbt models, maintaining a data dictionary by hand is impractical. The `make auto-metadata` command generates metadata directly from the DuckDB schema, keeping documentation in sync with the actual database state as tables are added or modified.

**Validation before consumption prevents downstream errors from compounding.** The multi-layer validation approach (raw quality checks → dbt staging tests → intermediate tests → mart tests → KPI notebook validation) catches issues early. The 3 duplicate-row failures in raw reference tables were caught before they could propagate into staging models.

**Wide-format source data requires early unpivoting.** Several FAOSTAT datasets provide years as columns (Y2001, Y2002, ...), which is incompatible with analytical queries and joins. Handling this in a dedicated `_unpivot` staging sub-layer, rather than in each downstream model individually, kept the transformation logic clean and prevented duplicated unpivot operations across the mart layer.

---

## Project Documentation

This README tells the business story. The complete technical process and supporting evidence are documented below.

| Document                                                                              | What's Inside                                                                      |
| ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| [Requirements & Scope](docs/00_requirements.md)                                       | Stakeholder problem, business questions, and finalized project scope               |
| [Architecture Report](docs/01_architecture_report.md)                                 | Full technical architecture, data layers, dbt design, and pipeline execution       |
| [Data Dictionary](docs/02_data_dictionary.md)                                         | Column-level definitions for all raw and transformed tables                        |
| [Data Quality Report](docs/03_data_quality_report.md)                                 | Raw-layer validation results, profiling, and known issues                          |
| [Pipeline Workflow](docs/04_data_pipeline_workflow.md)                                | Step-by-step execution workflow, command by command                                |
| [Power BI Explanation](docs/05_powerbi_explanation.md)                                | Dashboard architecture, KPI definitions, and page-by-page detail                   |
| [Business Insights Report](docs/06_business_insights_report.md)                       | Full findings and recommendations across all four domains                          |
| [Analysis Assumptions & Limitations](docs/07_analysis_assumptions_and_limitations.md) | KPI-level assumptions, known data issues, and validation methodology               |
| [Scope Trimming Notes](docs/08_scope_notes.md)                                        | Historical record of the original 8-problem/11-module scope and why it was trimmed |
| [Technical Overview](docs/09_technical_overview.md)                                   | Quick-reference technical summary, skills demonstrated, and lessons learned        |

---

## Business Value

This project demonstrates an end-to-end analytics engineering workflow:

**Business Problem → Requirements → Layered Data Validation → dbt Transformation → KPI Engineering → BI Delivery → Documented Findings**

Rather than treating this as a dashboard exercise, the platform is built around answering a practical policy and market question:

> _Which countries are moving toward risk, and where should attention and resources go next?_

---

_Built as a portfolio project simulating a real agricultural intelligence and policy-analytics engagement — from stakeholder problem definition through data validation, dimensional modeling, KPI engineering, and data-backed recommendations._
