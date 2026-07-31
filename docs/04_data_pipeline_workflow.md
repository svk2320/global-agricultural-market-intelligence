
# 04 Workflow

# Global Agriculture Market Intelligence Platform

---

## 1. Workflow Overview

The Global Agriculture Market Intelligence Platform follows a layered data engineering workflow that moves from raw source acquisition to analytical modeling, reporting, and dashboard consumption.

The workflow is executed through a combination of `make` commands, dbt commands, and supporting scripts.

```
Source Data
      ↓
Raw Data Storage (data/raw)
      ↓
File Conversion (CSV/Excel → Parquet)
      ↓
DuckDB Raw Layer
      ↓
Raw Metadata Generation
      ↓
Raw Data Quality Checks
      ↓
Raw Data Profiling
      ↓
Exploratory Analysis Notebooks
      ↓
dbt Model Generation
      ↓
Analysis & KPI Validation Notebooks
      ↓
dbt Transformation Pipeline
      ↓
Reporting Models
      ↓
PostgreSQL Export
      ↓
Power BI Dashboard
      ↓
Documentation Generation
```

The pipeline follows a layered approach where each stage produces validated outputs required by the next stage.

---

# 2. Source Data Acquisition

All original source files are placed under:

```
data/raw
```

The raw directory acts as the landing area for all external datasets before any transformation occurs.

Additional datasets are generated or downloaded using:

```bash
make generate-holidays

make download-weather
```

These commands download or generate additional raw datasets required by the platform.

At the end of this step, all source datasets required for processing exist under `data/raw`.

---

# 3. File Conversion Workflow

Raw CSV and Excel files are converted into Parquet format using:

```bash
make convert
```

This converts source files into:

```
files_to_parquet
```

Parquet is used because it provides:

* Columnar storage
* Better compression
* Faster analytical reads
* Better compatibility with DuckDB

The converted Parquet files become the input for the ingestion process.

---

# 4. Raw Data Ingestion

Converted files are loaded into DuckDB using:

```bash
make ingest
```

This creates the raw database layer.

The raw layer preserves source-level data before applying business transformations.

Characteristics:

* Source-oriented tables
* No business logic applied
* Used as the foundation for downstream dbt transformations

---

# 5. Raw Metadata Generation

After ingestion, metadata information is generated using:

```bash
make auto-metadata
```

This generates information about tables available in the raw schema.

Generated metadata includes information such as:

* Table names
* Column names
* Data types
* Table structures
* Dataset information

This metadata supports:

* Data understanding
* Data dictionary generation
* Pipeline documentation

---

# 6. Raw Data Quality Validation

After metadata generation, raw data validation is performed.

## Data Quality Checks

```bash
make quality-checks-raw
```

This validates raw datasets for issues such as:

* Missing values
* Duplicate records
* Data consistency problems
* Unexpected structures

## Raw Data Profiling

```bash
make profiling-raw
```

This generates profiling information including:

* Column statistics
* Distinct values
* Data distributions
* Potential anomalies

Together, metadata generation, quality checks, and profiling establish the baseline quality of the ingested raw layer.

---

# 7. dbt Model Generation

The dbt transformation layer is generated from the raw schema.

## Generate Staging Models

```bash
generate_all_staging_models
```

Creates staging models for raw datasets.

Staging models handle:

* Column standardization
* Basic cleaning
* Data type preparation

---

## Generate Deduplication Models

Some source datasets contain duplicate records.

Specific deduplication models are generated using:

```bash
make generate-dedup-models TABLES="foodbalancesheets_areacodes foodbalancesheetshistoric_areacodes forestry_trade_flows_areacodes"
```

These models isolate duplicate handling logic before downstream transformations.

---

## Generate Unpivot Models

```bash
generate_unpivot_models
```

Some agricultural datasets are provided in wide format with years represented as columns.

Unpivot models convert these datasets into long analytical formats suitable for:

* Time-series analysis
* Joins
* Aggregations

---

## Generate dbt Source Definitions

```bash
make generate-sources-yml
```

Creates dbt source configuration files based on the ingested raw datasets.

This enables:

* dbt lineage tracking
* Source references
* Better model documentation

---

# 8. dbt Configuration

Before executing dbt transformations, update the dbt profile:

```bash
notepad "$HOME\.dbt\profiles.yml"
```

The profile contains the database connection configuration required by the dbt project.

---

# 9. dbt Transformation Workflow

The dbt project is executed inside the agriculture folder.

Initial dbt execution:

```bash
dbt run

dbt test

dbt deps
```

The project dependencies, models, and tests are executed through dbt.

---

# 10. Intermediate Model Generation

Intermediate models are generated using:

```bash
make generate-intermediate-models
```

Intermediate models contain reusable transformation logic shared across multiple analytical models.

---

# 11. Layer-by-Layer dbt Execution

The dbt pipeline is executed sequentially by layer.

---

## Staging Layer

```bash
dbt run --select staging

dbt test --select staging
```

Purpose:

* Clean source data
* Standardize structures
* Prepare datasets for analytical modeling

---

## Intermediate Layer

```bash
dbt run --select intermediate

dbt test --select intermediate
```

Purpose:

* Apply reusable transformations
* Combine datasets
* Prepare analytical building blocks

---

## Mart Layer

```bash
dbt run --select marts

dbt test --select marts
```

Purpose:

* Create business-oriented analytical models
* Organize data around agriculture business questions

---

## Reporting Layer

```bash
dbt run --select reporting
```

Purpose:

* Create Power BI-ready datasets
* Generate dashboard-specific aggregations
* Prepare final reporting tables

---

# 12. Analysis Notebook Workflow

Analysis notebooks are used as an analytical validation layer during platform development.

Notebooks are not part of the production execution pipeline and do not directly feed Power BI. They are used to explore data, validate business logic, and confirm KPI calculations before final reporting models are consumed by the dashboard.

Notebook activities include:

* Exploratory data analysis
* Business question investigation
* KPI calculation validation
* Trend analysis
* Data anomaly investigation
* Supporting business insight generation

The notebook workflow is divided into two stages:

## Exploratory Analysis

Early notebooks are used after raw data preparation to understand:

* Dataset structures
* Available indicators
* Data coverage
* Data quality issues
* Initial relationships between variables

## Analytical Validation

Later notebooks are used with dbt analytical models to validate:

* Business metrics
* Dashboard KPIs
* Aggregations
* Country-level comparisons
* Trend calculations

Validated analytical logic is then implemented in dbt reporting models to ensure reproducibility and consistency.

Workflow:

```
Raw / Analytical Models
        ↓
Analysis Notebooks
        ↓
Validated Metrics
        ↓
dbt Reporting Models
        ↓
Power BI Dashboard
```

---

# 13. Reporting Export Workflow

Reporting tables are exported using:

```bash
make export
```

This moves reporting tables into:

```
export_to_postgres
```

The exported PostgreSQL database acts as the BI serving layer consumed by Power BI.

---

# 14. Dashboard Artifact Processing

The Power BI dashboard PDF output is processed using:

```bash
make convert-dashboard-pdf
```

This converts the dashboard PDF into individual files for documentation and distribution purposes.

---

# 15. Documentation Generation

The final documentation artifacts are generated using:

## Data Dictionary

```bash
make generate-data-dictionary
```

Generates the data dictionary documentation from the available metadata.

---

## Data Quality Report

```bash
make generate-data-quality-report
```

Generates the data quality report using profiling and validation outputs.

---

# 16. Complete Execution Sequence

```
1. Place source files in data/raw

2. make generate-holidays

3. make download-weather

4. make convert

5. make ingest

6. make auto-metadata

7. make quality-checks-raw

8. make profiling-raw

9. generate_all_staging_models

10. make generate-dedup-models TABLES="..."

11. generate_unpivot_models

12. make generate-sources-yml

13. Update ~/.dbt/profiles.yml

14. dbt run

15. dbt test

16. dbt deps

17. make generate-intermediate-models

18. dbt run --select staging
19. dbt test --select staging

20. dbt run --select intermediate
21. dbt test --select intermediate

22. dbt run --select marts
23. dbt test --select marts

24. dbt run --select reporting

25. make export

26. make convert-dashboard-pdf

27. make generate-data-dictionary

28. make generate-data-quality-report
```
