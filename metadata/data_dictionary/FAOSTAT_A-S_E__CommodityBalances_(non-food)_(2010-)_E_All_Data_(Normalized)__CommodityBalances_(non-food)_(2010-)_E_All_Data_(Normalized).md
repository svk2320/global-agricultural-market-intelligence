# FAOSTAT_A-S_E__CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 399.5KB |
| Rows | 127,558 |
| Columns | 14 |
| File created | 2026-07-05T03:43:41.047768+00:00 |
| File last modified | 2026-07-05T03:52:03.341956+00:00 |
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
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | Yes | 1,260 | 0.99% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 120,914 | 94.79% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 828; 829; 767 |
| `Item Code (CPC)` | '25020.01; '25020.02; '01921.02 |
| `Item` | Cigarettes; Cigars and cheroots; Cotton lint, ginned |
| `Element Code` | 5610; 5071; 5910 |
| `Element` | Import quantity; Stock Variation; Export quantity |
| `Year Code` | 2010; 2011; 2012 |
| `Year` | 2010; 2011; 2012 |
| `Unit` | t |
| `Value` | 5729.0; 12754.0; 6977.0 |
| `Flag` | A; X; I |
| `Note` | Estimated data using trading partners database; Unofficial figure |
