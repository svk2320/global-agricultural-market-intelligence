# FAOSTAT_A-S_E__Emissions_crops_E_All_Data_(Normalized)__Emissions_crops_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_crops_E_All_Data_(Normalized)/Emissions_crops_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 2.8MB |
| Rows | 766,730 |
| Columns | 16 |
| File created | 2026-07-05T03:43:50.447113+00:00 |
| File last modified | 2026-07-05T03:52:10.666578+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item Code (CPC)` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | Yes | 958 | 0.12% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 749,499 | 97.75% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 44; 56; 156 |
| `Item Code (CPC)` | '0115; '0112; '01802 |
| `Item` | Barley; Maize (corn); Sugar cane |
| `Element Code` | 72392; 72302; 72342 |
| `Element` | Crop residues (N content); Crop residues (Emissions N2O); Crop residues (Direct emissions N2O) |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Source Code` | 3050; 3051 |
| `Source` | FAO TIER 1; UNFCCC |
| `Unit` | kg; kt; t |
| `Value` | 5925706.1338; 5946873.7579; 5893769.0166 |
| `Flag` | E; F; A |
| `Note` | ; UNFCCC Repository; NC/CRF/BUR |
