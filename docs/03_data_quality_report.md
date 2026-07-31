# Data Quality Report - Global Agriculture Market Intelligence

## 1. Overview

- **Database:** global_agriculature_market_intelligence.duckdb
- **Generated At:** 2026-07-31 17:35:23
- **Purpose:** This report summarizes automated data quality and profiling checks performed on the raw data layer. Transformation layer validation is handled separately through dbt tests and downstream validation checks (see Section 6). This report is generated directly from the `audit` schema and reflects the latest raw-layer validation run recorded for each table.
---
## 2. Raw Data Quality Coverage

- **Total tables checked:** 369

**Tables by layer (data quality checks):**

| Layer | Tables Checked |
|---|---|
| raw | 369 |

**Validation coverage:** raw layer only

**Checks included in this coverage:** row count validation, duplicate detection, null analysis, profiling statistics, outlier detection, and constant column detection, as recorded in the most recent run per table.
---
## 3. Quality Checks Performed

| Check | Description |
|---|---|
| Row count validation | Confirms each table has the expected volume of records and flags unexpectedly empty or shrinking tables. |
| Duplicate detection | Identifies fully or partially duplicated rows that may indicate upstream ingestion issues. |
| Null analysis | Measures how many columns contain null values and how prevalent they are. |
| Profiling statistics | Captures column counts, data types, and distribution characteristics for each table. |
| Outlier detection | Flags numeric columns with statistically unusual values. |
| Constant column detection | Flags columns where every value is identical, which often signals a data issue or a column no longer in use. |
---
## 4. Quality Summary

**Status counts (latest run per table):**

| Status | Table Count |
|---|---|
| FAIL | 3 |
| PASS | 366 |

**Aggregate figures:**

| Metric | Value |
|---|---|
| Total rows checked | 97,263,654 |
| Total duplicate rows found | 637 |
| Tables with null columns | 57 |

---
## 5. Profiling Summary

| Metric | Value |
|---|---|
| Total tables profiled | 369 |
| Total columns analyzed | 1,932 |
| Numeric columns | 765 |
| Categorical columns | 1,167 |
| Tables with outliers | 167 |
| Tables with constant columns | 106 |

---
## 6. Transformation Layer Validation

Data quality validation for transformed layers is performed through dbt tests rather than the `audit` schema tracked in this report.

**Layers:**

- staging
- intermediate
- marts
- reporting

**Validation includes:**

- not null checks
- uniqueness checks
- relationship checks
- accepted value checks
---
## 7. Failed / Warning Checks

| Table | Status | Failure Reason |
|---|---|---|
| raw.foodbalancesheets_areacodes | FAIL | {'reason': 'duplicate_rows', 'detail': '213 full-row duplicates found (426 total -> 213 distinct).'} |
| raw.foodbalancesheetshistoric_areacodes | FAIL | {'reason': 'duplicate_rows', 'detail': '217 full-row duplicates found (434 total -> 217 distinct).'} |
| raw.forestry_trade_flows_areacodes | FAIL | {'reason': 'duplicate_rows', 'detail': '207 full-row duplicates found (423 total -> 216 distinct).'} |


Duplicate records were detected in some source reference tables. These tables are monitored, and their impact on downstream analytical models should be assessed before production use.
---
## 8. Recommendations

**Overall status:** 366 of 369 checked tables passed their latest data quality run (99.2% pass rate); 3 table(s) require attention.

**Areas requiring attention:**

- Investigate the 3 table(s) listed in Section 7 and resolve their failure reasons.
- Review null handling for the 57 table(s) with columns containing nulls.
- Review the 167 table(s) flagged with statistical outliers to confirm they're expected.
- Review the 106 table(s) with constant columns -- these may indicate stale or unused fields.
---
