# Data Dictionary — Combined

Datasets: 370

---

# All_countries_holidays

| Field | Value |
| --- | --- |
| File path | All_countries_holidays.parquet |
| Format | parquet |
| File size | 273.6KB |
| Rows | 88,537 |
| Columns | 10 |
| File created | 2026-07-05T14:21:57.124631+00:00 |
| File last modified | 2026-07-05T14:21:57.240168+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `country_code` | String | Categorical | No | 0 | 0.0% |
| `country_name` | String | Categorical | No | 0 | 0.0% |
| `date` | String | Categorical | No | 0 | 0.0% |
| `local_name` | String | Categorical | No | 0 | 0.0% |
| `name` | String | Categorical | No | 0 | 0.0% |
| `fixed` | Null | Categorical | Yes | 88,537 | 100.0% |
| `global` | Null | Categorical | Yes | 88,537 | 100.0% |
| `counties` | Null | Categorical | Yes | 88,537 | 100.0% |
| `launch_year` | Null | Categorical | Yes | 88,537 | 100.0% |
| `types` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `country_code` | AD; AE; AF |
| `country_name` | Andorra; United Arab Emirates; Afghanistan |
| `date` | 2000-01-01; 2000-01-06; 2000-03-06 |
| `local_name` | New Year's Day; Epiphany; Carnival |
| `name` | New Year's Day; Epiphany; Carnival |
| `types` | Public |


---

# CMO-Historical-Data-Monthly__Monthly_Indices

| Field | Value |
| --- | --- |
| File path | CMO-Historical-Data-Monthly/Monthly_Indices.parquet |
| Format | parquet |
| File size | 59.1KB |
| Rows | 798 |
| Columns | 17 |
| File created | 2026-07-06T02:41:00.716552+00:00 |
| File last modified | 2026-07-06T02:41:00.720851+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Date` | String | Categorical | No | 0 | 0.0% |
| `Total Index` | Float64 | Numeric | No | 0 | 0.0% |
| `Energy` | Float64 | Numeric | No | 0 | 0.0% |
| `Non-energy **` | Float64 | Numeric | No | 0 | 0.0% |
| `Agriculture **` | Float64 | Numeric | No | 0 | 0.0% |
| `Beverages` | Float64 | Numeric | No | 0 | 0.0% |
| `Food **` | Float64 | Numeric | No | 0 | 0.0% |
| `Oils & Meals` | Float64 | Numeric | No | 0 | 0.0% |
| `Grains` | Float64 | Numeric | No | 0 | 0.0% |
| `Other Food **` | Float64 | Numeric | No | 0 | 0.0% |
| `Raw Materials` | Float64 | Numeric | No | 0 | 0.0% |
| `Timber` | Float64 | Numeric | No | 0 | 0.0% |
| `Other Raw Mat.` | Float64 | Numeric | No | 0 | 0.0% |
| `Fertilizers **` | Float64 | Numeric | No | 0 | 0.0% |
| `Metals  & Minerals` | Float64 | Numeric | No | 0 | 0.0% |
| `Base Metals (ex. iron ore)` | Float64 | Numeric | No | 0 | 0.0% |
| `Precious Metals` | Float64 | Numeric | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Date` | 1960M01; 1960M02; 1960M03 |
| `Total Index` | 7.6; 7.7; 7.4 |
| `Energy` | 2.1; 2.0; 1.9 |
| `Non-energy **` | 18.8; 18.7; 18.6 |
| `Agriculture **` | 22.0; 21.8; 21.9 |
| `Beverages` | 25.4; 25.1; 24.6 |
| `Food **` | 21.2; 20.9; 21.1 |
| `Oils & Meals` | 23.2; 22.5; 22.2 |
| `Grains` | 23.6; 23.4; 23.8 |
| `Other Food **` | 16.4; 16.5; 17.1 |
| `Raw Materials` | 22.3; 22.4; 22.5 |
| `Timber` | 16.2; 16.6; 17.6 |
| `Other Raw Mat.` | 29.0; 29.4; 29.5 |
| `Fertilizers **` | 12.9; 12.6; 12.7 |
| `Metals  & Minerals` | 12.9; 12.7; 12.8 |
| `Base Metals (ex. iron ore)` | 14.1; 13.9; 14.0 |
| `Precious Metals` | 3.3; 3.4; 3.5 |


---

# CMO-Historical-Data-Monthly__Monthly_Prices

| Field | Value |
| --- | --- |
| File path | CMO-Historical-Data-Monthly/Monthly_Prices.parquet |
| Format | parquet |
| File size | 210.3KB |
| Rows | 798 |
| Columns | 72 |
| File created | 2026-07-06T02:41:00.494206+00:00 |
| File last modified | 2026-07-06T02:41:00.501092+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Date` | String | Categorical | No | 0 | 0.0% |
| `Crude oil, average ($/bbl)` | Float64 | Numeric | No | 0 | 0.0% |
| `Crude oil, Brent ($/bbl)` | Float64 | Numeric | No | 0 | 0.0% |
| `Crude oil, Dubai ($/bbl)` | Float64 | Numeric | No | 0 | 0.0% |
| `Crude oil, WTI ($/bbl)` | Float64 | Numeric | Yes | 264 | 33.08% |
| `Coal, Australian ($/mt)` | Float64 | Numeric | Yes | 120 | 15.04% |
| `Coal, South African ** ($/mt)` | Float64 | Numeric | Yes | 288 | 36.09% |
| `Natural gas, US ($/mmbtu)` | Float64 | Numeric | No | 0 | 0.0% |
| `Natural gas, Europe ($/mmbtu)` | Float64 | Numeric | No | 0 | 0.0% |
| `Liquefied natural gas, Japan ($/mmbtu)` | Float64 | Numeric | Yes | 204 | 25.56% |
| `Natural gas index (2010=100)` | Float64 | Numeric | Yes | 204 | 25.56% |
| `Cocoa ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Coffee, Arabica ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Coffee, Robusta ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Tea, avg 3 auctions ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Tea, Colombo ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Tea, Kolkata ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Tea, Mombasa ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Coconut oil ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Groundnuts ($/mt)` | Float64 | Numeric | Yes | 240 | 30.08% |
| `Fish meal ($/mt)` | Float64 | Numeric | Yes | 228 | 28.57% |
| `Groundnut oil ** ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Palm oil ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Palm kernel oil ($/mt)` | Float64 | Numeric | Yes | 432 | 54.14% |
| `Soybeans ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Soybean oil ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Soybean meal ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Rapeseed oil ($/mt)` | Float64 | Numeric | Yes | 505 | 63.28% |
| `Sunflower oil ($/mt)` | Float64 | Numeric | Yes | 510 | 63.91% |
| `Barley ($/mt)` | Float64 | Numeric | Yes | 70 | 8.77% |
| `Maize ($/mt)` | Float64 | Numeric | No | 0 | 0.0% |
| `Sorghum ($/mt)` | Float64 | Numeric | Yes | 70 | 8.77% |
| `Rice, Thai 5% ($/mt)` | Float64 | Numeric | No | 0 | 0.0% |
| `Rice, Thai 25% ($/mt)` | Float64 | Numeric | Yes | 320 | 40.1% |
| `Rice, Thai A.1 ($/mt)` | Float64 | Numeric | Yes | 312 | 39.1% |
| `Rice, Viet Namese 5% ($/mt)` | Float64 | Numeric | Yes | 538 | 67.42% |
| `Wheat, US SRW ($/mt)` | Float64 | Numeric | Yes | 235 | 29.45% |
| `Wheat, US HRW ($/mt)` | Float64 | Numeric | No | 0 | 0.0% |
| `Banana, Europe ($/kg)` | Float64 | Numeric | Yes | 444 | 55.64% |
| `Banana, US ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Orange ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Beef ** ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Chicken ** ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Lamb ** ($/kg)` | Float64 | Numeric | Yes | 132 | 16.54% |
| `Shrimps, Mexican ($/kg)` | Float64 | Numeric | Yes | 32 | 4.01% |
| `Sugar, EU ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Sugar, US ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Sugar, world ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Tobacco, US import u.v. ($/mt)` | Float64 | Numeric | Yes | 2 | 0.25% |
| `Logs, Cameroon ($/cubic meter)` | Float64 | Numeric | Yes | 120 | 15.04% |
| `Logs, Malaysian ($/cubic meter)` | Float64 | Numeric | No | 0 | 0.0% |
| `Sawnwood, Cameroon ($/cubic meter)` | Float64 | Numeric | Yes | 372 | 46.62% |
| `Sawnwood, Malaysian ($/cubic meter)` | Float64 | Numeric | No | 0 | 0.0% |
| `Plywood (cents/sheet)` | Float64 | Numeric | Yes | 228 | 28.57% |
| `Cotton, A Index ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Rubber, TSR20 ** ($/kg)` | Float64 | Numeric | Yes | 468 | 58.65% |
| `Rubber, RSS3 ($/kg)` | Float64 | Numeric | No | 0 | 0.0% |
| `Phosphate rock ($/mt)` | Float64 | Numeric | Yes | 1 | 0.13% |
| `DAP ($/mt)` | Float64 | Numeric | Yes | 84 | 10.53% |
| `TSP ($/mt)` | Float64 | Numeric | No | 0 | 0.0% |
| `Urea ($/mt)` | Float64 | Numeric | No | 0 | 0.0% |
| `Potassium chloride ** ($/mt)` | Float64 | Numeric | No | 0 | 0.0% |
| `Aluminum ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Iron ore, cfr spot ($/dmtu)` | Float64 | Numeric | No | 0 | 0.0% |
| `Copper ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Lead ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Tin ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Nickel ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Zinc ($/mt)` | Int64 | Numeric | No | 0 | 0.0% |
| `Gold ($/troy oz)` | Int64 | Numeric | No | 0 | 0.0% |
| `Platinum ($/troy oz)` | Int64 | Numeric | No | 0 | 0.0% |
| `Silver ($/troy oz)` | Float64 | Numeric | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Date` | 1960M01; 1960M02; 1960M03 |
| `Crude oil, average ($/bbl)` | 1.6; 1.5; 1.4 |
| `Crude oil, Brent ($/bbl)` | 1.6; 1.5; 1.4 |
| `Crude oil, Dubai ($/bbl)` | 1.6; 1.5; 1.4 |
| `Crude oil, WTI ($/bbl)` | 35.3; 34.8; 32.6 |
| `Coal, Australian ($/mt)` | 7.8; 8.7; 9.6 |
| `Coal, South African ** ($/mt)` | 29.3; 34.3; 35.8 |
| `Natural gas, US ($/mmbtu)` | 0.1; 0.2; 0.3 |
| `Natural gas, Europe ($/mmbtu)` | 0.4; 0.5; 0.7 |
| `Liquefied natural gas, Japan ($/mmbtu)` | 2.8; 3.0; 3.7 |
| `Natural gas index (2010=100)` | 18.5; 19.0; 19.5 |
| `Cocoa ($/kg)` | 0.63; 0.61; 0.58 |
| `Coffee, Arabica ($/kg)` | 0.94; 0.95; 0.93 |
| `Coffee, Robusta ($/kg)` | 0.7; 0.69; 0.68 |
| `Tea, avg 3 auctions ($/kg)` | 1.03; 0.95; 0.97 |
| `Tea, Colombo ($/kg)` | 0.93; 0.89; 0.86 |
| `Tea, Kolkata ($/kg)` | 1.12; 0.98; 1.1 |
| `Tea, Mombasa ($/kg)` | 1.04; 0.98; 0.95 |
| `Coconut oil ($/mt)` | 390; 379; 361 |
| `Groundnuts ($/mt)` | 869.0; 887.0; 895.0 |
| `Fish meal ($/mt)` | 381.0; 382.0; 366.0 |
| `Groundnut oil ** ($/mt)` | 334; 341; 338 |
| `Palm oil ($/mt)` | 233; 229; 225 |
| `Palm kernel oil ($/mt)` | 686.0; 716.0; 715.0 |
| `Soybeans ($/mt)` | 94; 91; 92 |
| `Soybean oil ($/mt)` | 204; 201; 207 |
| `Soybean meal ($/mt)` | 92; 87; 84 |
| `Rapeseed oil ($/mt)` | 423.0; 416.0; 411.0 |
| `Sunflower oil ($/mt)` | 578.0; 557.0; 552.0 |
| `Barley ($/mt)` | 20.4; 20.7; 20.6 |
| `Maize ($/mt)` | 45.0; 44.0; 48.0 |
| `Sorghum ($/mt)` | 39.0; 35.0; 36.0 |
| `Rice, Thai 5% ($/mt)` | 104.5; 103.5; 103.8 |
| `Rice, Thai 25% ($/mt)` | 83.3; 115.1; 101.4 |
| `Rice, Thai A.1 ($/mt)` | 98.0; 97.0; 100.0 |
| `Rice, Viet Namese 5% ($/mt)` | 197.0; 198.8; 204.1 |
| `Wheat, US SRW ($/mt)` | 140.4; 144.8; 144.0 |
| `Wheat, US HRW ($/mt)` | 59.9; 61.0; 61.7 |
| `Banana, Europe ($/kg)` | 0.94; 0.97; 1.11 |
| `Banana, US ($/kg)` | 0.14; 0.15; 0.13 |
| `Orange ($/kg)` | 0.12; 0.11; 0.13 |
| `Beef ** ($/kg)` | 0.71; 0.77; 0.84 |
| `Chicken ** ($/kg)` | 0.3; 0.31; 0.32 |
| `Lamb ** ($/kg)` | 0.8; 0.79; 0.78 |
| `Shrimps, Mexican ($/kg)` | 1.43; 1.5; 1.68 |
| `Sugar, EU ($/kg)` | 0.12; 0.13; 0.11 |
| `Sugar, US ($/kg)` | 0.12; 0.13; 0.14 |
| `Sugar, world ($/kg)` | 0.07; 0.05; 0.06 |
| `Tobacco, US import u.v. ($/mt)` | 1737.0; 1563.0; 1405.0 |
| `Logs, Cameroon ($/cubic meter)` | 43.0; 44.4; 52.5 |
| `Logs, Malaysian ($/cubic meter)` | 31.9; 33.1; 36.4 |
| `Sawnwood, Cameroon ($/cubic meter)` | 175.0; 396.0; 307.0 |
| `Sawnwood, Malaysian ($/cubic meter)` | 149.2; 152.0; 160.1 |
| `Plywood (cents/sheet)` | 270.0; 238.0; 206.6 |
| `Cotton, A Index ($/kg)` | 0.65; 0.64; 0.66 |
| `Rubber, TSR20 ** ($/kg)` | 0.6; 0.56; 0.52 |
| `Rubber, RSS3 ($/kg)` | 0.82; 0.83; 0.86 |
| `Phosphate rock ($/mt)` | 13.0; 11.5; 12.5 |
| `DAP ($/mt)` | 68.5; 60.5; 58.0 |
| `TSP ($/mt)` | 53.0; 52.0; 51.0 |
| `Urea ($/mt)` | 42.3; 60.5; 65.8 |
| `Potassium chloride ** ($/mt)` | 28.5; 30.0; 32.5 |
| `Aluminum ($/mt)` | 511; 505; 496 |
| `Iron ore, cfr spot ($/dmtu)` | 11.4; 11.0; 10.2 |
| `Copper ($/mt)` | 715; 728; 685 |
| `Lead ($/mt)` | 206; 204; 210 |
| `Tin ($/mt)` | 2180; 2174; 2178 |
| `Nickel ($/mt)` | 1631; 1711; 1761 |
| `Zinc ($/mt)` | 261; 245; 249 |
| `Gold ($/troy oz)` | 35; 36; 37 |
| `Platinum ($/troy oz)` | 84; 79; 81 |
| `Silver ($/troy oz)` | 0.9; 1.0; 1.1 |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_archive_E_All_Data_(Normalized)__ASTI_Expenditures_archive_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_archive_E_All_Data_(Normalized)/ASTI_Expenditures_archive_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 16.5KB |
| Rows | 3,094 |
| Columns | 13 |
| File created | 2026-07-05T03:43:39.760383+00:00 |
| File last modified | 2026-07-05T03:52:01.820609+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 4; 8; 9 |
| `Area Code (M49)` | '012; '028; '032 |
| `Area` | Algeria; Antigua and Barbuda; Argentina |
| `Item Code` | 23045 |
| `Item` | Agriculture research spending |
| `Element Code` | 6083; 6084 |
| `Element` | Share of Value Added (Agriculture, Forestry and Fishing); Spending, total (constant 2011 prices) |
| `Year Code` | 2009; 2010; 2011 |
| `Year` | 2009; 2010; 2011 |
| `Unit` | %; million PPP |
| `Value` | 0.18; 0.21; 76.9 |
| `Flag` | X |
| `Note` | ASTI (Agricultural Science and Technology Indicators). 2019. ASTI database. h...; Includes estimates for expatriate salaries. ASTI (Agricultural Science and Te... |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_archive_E_All_Data_(Normalized)__ASTI_Expenditures_archive_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_archive_E_All_Data_(Normalized)/ASTI_Expenditures_archive_E_AreaCodes.parquet |
| Format | parquet |
| File size | 2.9KB |
| Rows | 121 |
| Columns | 3 |
| File created | 2026-07-05T03:43:39.783402+00:00 |
| File last modified | 2026-07-05T03:52:01.825521+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 5100; 4; 5200 |
| `M49 Code` | '002; '012; '019 |
| `Area` | Africa; Algeria; Americas |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_archive_E_All_Data_(Normalized)__ASTI_Expenditures_archive_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_archive_E_All_Data_(Normalized)/ASTI_Expenditures_archive_E_Elements.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:39.798402+00:00 |
| File last modified | 2026-07-05T03:52:01.828680+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6083; 6084 |
| `Element` | Share of Value Added (Agriculture; Forestry and Fishing); Spending; total (constant 2011 prices) |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_archive_E_All_Data_(Normalized)__ASTI_Expenditures_archive_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_archive_E_All_Data_(Normalized)/ASTI_Expenditures_archive_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:39.812674+00:00 |
| File last modified | 2026-07-05T03:52:01.830688+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | X |
| ` Description` | Figure from external organization |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_archive_E_All_Data_(Normalized)__ASTI_Expenditures_archive_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_archive_E_All_Data_(Normalized)/ASTI_Expenditures_archive_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:39.825675+00:00 |
| File last modified | 2026-07-05T03:52:01.832689+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 23045 |
| `Item` | Agriculture research spending |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_E_All_Data_(Normalized)__ASTI_Expenditures_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_E_All_Data_(Normalized)/ASTI_Expenditures_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 49.2KB |
| Rows | 7,789 |
| Columns | 15 |
| File created | 2026-07-05T03:43:39.875607+00:00 |
| File last modified | 2026-07-05T03:52:01.877702+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Cost Category Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Cost Category` | String | Categorical | No | 0 | 0.0% |
| `Institution Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Institution` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 7,789 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 3; 4; 8 |
| `Area Code (M49)` | '008; '012; '028 |
| `Area` | Albania; Algeria; Antigua and Barbuda |
| `Indicator Code` | 8000; 8001; 8002 |
| `Indicator` | Total Expenditure in Agricultural R&D (Standard Local Currency); Total Expenditure in Agricultural R&D (Standard Local Currency, 2015 prices); Total Expenditure in Agricultural R&D (US$, 2015 prices) |
| `Cost Category Code` | 300 |
| `Cost Category` | Total |
| `Institution Code` | 200 |
| `Institution` | Government, Higher Education and Private Non-profit |
| `Year Code` | 2023; 2009; 2010 |
| `Year` | 2023; 2009; 2010 |
| `Unit` | million SLC; million USD; % |
| `Value` | 1011.288; 806.1819; 6.4002 |
| `Flag` | A; X; I |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_E_All_Data_(Normalized)__ASTI_Expenditures_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_E_All_Data_(Normalized)/ASTI_Expenditures_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.2KB |
| Rows | 163 |
| Columns | 3 |
| File created | 2026-07-05T03:43:39.912897+00:00 |
| File last modified | 2026-07-05T03:52:01.881710+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 5100; 3; 4 |
| `M49 Code` | '002; '008; '012 |
| `Area` | Africa; Albania; Algeria |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_E_All_Data_(Normalized)__ASTI_Expenditures_E_CostCategorys

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_E_All_Data_(Normalized)/ASTI_Expenditures_E_CostCategorys.parquet |
| Format | parquet |
| File size | 928.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:39.924907+00:00 |
| File last modified | 2026-07-05T03:52:01.884709+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Cost Category Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Cost Category` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Cost Category Code` | 300 |
| `Cost Category` | Total |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_E_All_Data_(Normalized)__ASTI_Expenditures_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_E_All_Data_(Normalized)/ASTI_Expenditures_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:43:39.935904+00:00 |
| File last modified | 2026-07-05T03:52:01.886711+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; B; E |
| ` Description` | Official figure; Time series break; Estimated value |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_E_All_Data_(Normalized)__ASTI_Expenditures_E_Indicators

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_E_All_Data_(Normalized)/ASTI_Expenditures_E_Indicators.parquet |
| Format | parquet |
| File size | 1.4KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:43:39.949931+00:00 |
| File last modified | 2026-07-05T03:52:01.888709+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Indicator Code` | 8006; 8000; 8001 |
| `Indicator` | Expenditure in Agricultural R&D as Share of Agricultural Value Added (Standar...; Total Expenditure in Agricultural R&D (Standard Local Currency); Total Expenditure in Agricultural R&D (Standard Local Currency; 2015 prices) |


---

# FAOSTAT_A-S_E__ASTI_Expenditures_E_All_Data_(Normalized)__ASTI_Expenditures_E_Institutions

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Expenditures_E_All_Data_(Normalized)/ASTI_Expenditures_E_Institutions.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:39.968678+00:00 |
| File last modified | 2026-07-05T03:52:01.891710+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Institution Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Institution` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Institution Code` | 200 |
| `Institution` | Government; Higher Education and Private Non-profit |


---

# FAOSTAT_A-S_E__ASTI_Researchers_archive_E_All_Data_(Normalized)__ASTI_Researchers_archive_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_archive_E_All_Data_(Normalized)/ASTI_Researchers_archive_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 16.6KB |
| Rows | 3,154 |
| Columns | 13 |
| File created | 2026-07-05T03:43:40.020677+00:00 |
| File last modified | 2026-07-05T03:52:01.912311+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 4; 8; 9 |
| `Area Code (M49)` | '012; '028; '032 |
| `Area` | Algeria; Antigua and Barbuda; Argentina |
| `Item Code` | 23046 |
| `Item` | Agricultural researchers (FTE) |
| `Element Code` | 6082; 6086 |
| `Element` | Researchers, total; Per 100,000 farmers |
| `Year Code` | 2009; 2010; 2011 |
| `Year` | 2009; 2010; 2011 |
| `Unit` |  |
| `Value` | 510.3; 529.1; 562.8 |
| `Flag` | X |
| `Note` | ASTI (Agricultural Science and Technology Indicators). 2019. ASTI database. h...; Includes degree estimates for expatriate researchers. ASTI (Agricultural Scie...; Includes estimates for expatriate researchers. ASTI (Agricultural Science and... |


---

# FAOSTAT_A-S_E__ASTI_Researchers_archive_E_All_Data_(Normalized)__ASTI_Researchers_archive_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_archive_E_All_Data_(Normalized)/ASTI_Researchers_archive_E_AreaCodes.parquet |
| Format | parquet |
| File size | 2.9KB |
| Rows | 121 |
| Columns | 3 |
| File created | 2026-07-05T03:43:40.044287+00:00 |
| File last modified | 2026-07-05T03:52:01.916322+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 5100; 4; 5200 |
| `M49 Code` | '002; '012; '019 |
| `Area` | Africa; Algeria; Americas |


---

# FAOSTAT_A-S_E__ASTI_Researchers_archive_E_All_Data_(Normalized)__ASTI_Researchers_archive_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_archive_E_All_Data_(Normalized)/ASTI_Researchers_archive_E_Elements.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.058935+00:00 |
| File last modified | 2026-07-05T03:52:01.918319+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6086; 6082 |
| `Element` | Per 100;000 farmers; Researchers; total |


---

# FAOSTAT_A-S_E__ASTI_Researchers_archive_E_All_Data_(Normalized)__ASTI_Researchers_archive_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_archive_E_All_Data_(Normalized)/ASTI_Researchers_archive_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.065944+00:00 |
| File last modified | 2026-07-05T03:52:01.920319+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | X |
| ` Description` | Figure from external organization |


---

# FAOSTAT_A-S_E__ASTI_Researchers_archive_E_All_Data_(Normalized)__ASTI_Researchers_archive_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_archive_E_All_Data_(Normalized)/ASTI_Researchers_archive_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.080065+00:00 |
| File last modified | 2026-07-05T03:52:01.922319+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 23046 |
| `Item` | Agricultural researchers (FTE) |


---

# FAOSTAT_A-S_E__ASTI_Researchers_E_All_Data_(Normalized)__ASTI_Researchers_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_E_All_Data_(Normalized)/ASTI_Researchers_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 23.0KB |
| Rows | 3,800 |
| Columns | 18 |
| File created | 2026-07-05T03:43:40.123697+00:00 |
| File last modified | 2026-07-05T03:52:01.949320+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Degree Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Degree` | String | Categorical | No | 0 | 0.0% |
| `Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Sex Code (SDG)` | String | Categorical | No | 0 | 0.0% |
| `Sex` | String | Categorical | No | 0 | 0.0% |
| `Institution Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Institution` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 3,800 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 3; 4; 8 |
| `Area Code (M49)` | '008; '012; '028 |
| `Area` | Albania; Algeria; Antigua and Barbuda |
| `Indicator Code` | 8100; 8102 |
| `Indicator` | Agricultural Researchers (FTE); Agricultural Researchers (FTE) per 100 000 Agricultural Workers |
| `Degree Code` | 100 |
| `Degree` | Total |
| `Sex Code` | 1 |
| `Sex Code (SDG)` | _T |
| `Sex` | Total |
| `Institution Code` | 200 |
| `Institution` | Government, Higher Education and Private Non-profit |
| `Year Code` | 2023; 2009; 2010 |
| `Year` | 2023; 2009; 2010 |
| `Unit` | No |
| `Value` | 291.4; 65.9; 510.3 |
| `Flag` | A; X; I |


---

# FAOSTAT_A-S_E__ASTI_Researchers_E_All_Data_(Normalized)__ASTI_Researchers_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_E_All_Data_(Normalized)/ASTI_Researchers_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.2KB |
| Rows | 168 |
| Columns | 3 |
| File created | 2026-07-05T03:43:40.144742+00:00 |
| File last modified | 2026-07-05T03:52:01.953320+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 5100; 3; 4 |
| `M49 Code` | '002; '008; '012 |
| `Area` | Africa; Albania; Algeria |


---

# FAOSTAT_A-S_E__ASTI_Researchers_E_All_Data_(Normalized)__ASTI_Researchers_E_Degrees

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_E_All_Data_(Normalized)/ASTI_Researchers_E_Degrees.parquet |
| Format | parquet |
| File size | 866.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.164382+00:00 |
| File last modified | 2026-07-05T03:52:01.955003+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Degree Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Degree` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Degree Code` | 100 |
| `Degree` | Total |


---

# FAOSTAT_A-S_E__ASTI_Researchers_E_All_Data_(Normalized)__ASTI_Researchers_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_E_All_Data_(Normalized)/ASTI_Researchers_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.176389+00:00 |
| File last modified | 2026-07-05T03:52:01.959011+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__ASTI_Researchers_E_All_Data_(Normalized)__ASTI_Researchers_E_Indicators

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_E_All_Data_(Normalized)/ASTI_Researchers_E_Indicators.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.189393+00:00 |
| File last modified | 2026-07-05T03:52:01.961021+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Indicator Code` | 8100; 8102 |
| `Indicator` | Agricultural Researchers (FTE); Agricultural Researchers (FTE) per 100 000 Agricultural Workers |


---

# FAOSTAT_A-S_E__ASTI_Researchers_E_All_Data_(Normalized)__ASTI_Researchers_E_Institutions

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_E_All_Data_(Normalized)/ASTI_Researchers_E_Institutions.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.196670+00:00 |
| File last modified | 2026-07-05T03:52:01.964021+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Institution Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Institution` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Institution Code` | 200 |
| `Institution` | Government; Higher Education and Private Non-profit |


---

# FAOSTAT_A-S_E__ASTI_Researchers_E_All_Data_(Normalized)__ASTI_Researchers_E_Sexes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ASTI_Researchers_E_All_Data_(Normalized)/ASTI_Researchers_E_Sexes.parquet |
| Format | parquet |
| File size | 836.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.209865+00:00 |
| File last modified | 2026-07-05T03:52:01.966022+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Sex` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Sex Code` | 1 |
| `Sex` | Total |


---

# FAOSTAT_A-S_E__Climate_change_Emissions_indicators_E_All_Data_(Normalized)__Climate_change_Emissions_indicators_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Climate_change_Emissions_indicators_E_All_Data_(Normalized)/Climate_change_Emissions_indicators_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 1.3MB |
| Rows | 678,370 |
| Columns | 12 |
| File created | 2026-07-05T03:43:40.317185+00:00 |
| File last modified | 2026-07-05T03:52:02.201442+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6996; 6516; 6517 |
| `Item` | Farm gate; Land-use change; Pre- and post-production |
| `Element Code` | 726313; 7264; 7265 |
| `Element` | Emissions Share (CO2eq) (AR5); Emissions Share (CO2); Emissions Share (CH4) |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Unit` | %; t CO2eq/cap; kg CO2eq/Int$ |
| `Value` | 72.43; 73.71; 76.49 |
| `Flag` | E |


---

# FAOSTAT_A-S_E__Climate_change_Emissions_indicators_E_All_Data_(Normalized)__Climate_change_Emissions_indicators_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Climate_change_Emissions_indicators_E_All_Data_(Normalized)/Climate_change_Emissions_indicators_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 279 |
| Columns | 3 |
| File created | 2026-07-05T03:43:40.655053+00:00 |
| File last modified | 2026-07-05T03:52:02.205945+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Climate_change_Emissions_indicators_E_All_Data_(Normalized)__Climate_change_Emissions_indicators_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Climate_change_Emissions_indicators_E_All_Data_(Normalized)/Climate_change_Emissions_indicators_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 10 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.667575+00:00 |
| File last modified | 2026-07-05T03:52:02.208941+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 72792; 7279; 72791 |
| ` Element` | Emissions per area of agricultural land; Emissions per capita; Emissions per value of agricultural production |


---

# FAOSTAT_A-S_E__Climate_change_Emissions_indicators_E_All_Data_(Normalized)__Climate_change_Emissions_indicators_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Climate_change_Emissions_indicators_E_All_Data_(Normalized)/Climate_change_Emissions_indicators_E_Flags.parquet |
| Format | parquet |
| File size | 882.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.682576+00:00 |
| File last modified | 2026-07-05T03:52:02.211944+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | E |
| ` Description` | Estimated value |


---

# FAOSTAT_A-S_E__Climate_change_Emissions_indicators_E_All_Data_(Normalized)__Climate_change_Emissions_indicators_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Climate_change_Emissions_indicators_E_All_Data_(Normalized)/Climate_change_Emissions_indicators_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:43:40.696053+00:00 |
| File last modified | 2026-07-05T03:52:02.215942+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_(-2013_old_methodology)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_(-2013_old_methodology)_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_(-2013_old_methodology)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_(-2013_old_methodology)_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 2.3MB |
| Rows | 1,184,986 |
| Columns | 13 |
| File created | 2026-07-05T03:43:40.785973+00:00 |
| File last modified | 2026-07-05T03:52:02.957312+00:00 |
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
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 2600; 2661; 2559 |
| `Item Code (CPC)` | 'B2600; 'B2661; 'F2559 |
| `Item` | Brans; Cotton lint; Cottonseed |
| `Element Code` | 5510; 5300; 5520 |
| `Element` | Production; Domestic supply quantity; Feed |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | t |
| `Value` | 468407.0; 463852.0; 417196.0 |
| `Flag` | I; E |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_(-2013_old_methodology)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_(-2013_old_methodology)_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_(-2013_old_methodology)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_(-2013_old_methodology)_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.8KB |
| Rows | 217 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.143604+00:00 |
| File last modified | 2026-07-05T03:52:03.244427+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_(-2013_old_methodology)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_(-2013_old_methodology)_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_(-2013_old_methodology)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_(-2013_old_methodology)_E_Flags.parquet |
| Format | parquet |
| File size | 881.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:40.952090+00:00 |
| File last modified | 2026-07-05T03:52:03.247436+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E; I |
| `Description` | Estimated value; Imputed value |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_(-2013_old_methodology)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_(-2013_old_methodology)_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_(-2013_old_methodology)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_(-2013_old_methodology)_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.6KB |
| Rows | 22 |
| Columns | 3 |
| File created | 2026-07-05T03:43:40.967231+00:00 |
| File last modified | 2026-07-05T03:52:03.250434+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 2590; 2591; 2592 |
| `CPC Code` | 'B2590; 'B2591; 'B2592 |
| `Item` | Soyabean Cake; Groundnut Cake; Sunflowerseed Cake |


---

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


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_(2010-)_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_(2010-)_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.7KB |
| Rows | 213 |
| Columns | 3 |
| File created | 2026-07-05T03:43:41.166862+00:00 |
| File last modified | 2026-07-05T03:52:03.347161+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_(2010-)_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_(2010-)_E_Elements.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 7 |
| Columns | 2 |
| File created | 2026-07-05T03:43:41.180201+00:00 |
| File last modified | 2026-07-05T03:52:03.350446+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 5910; 5610; 5165 |
| `Element` | Export quantity; Import quantity; Other uses (non-food) |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_(2010-)_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_(2010-)_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:43:41.195132+00:00 |
| File last modified | 2026-07-05T03:52:03.353457+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_(2010-)_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_(2010-)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_(2010-)_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.9KB |
| Rows | 13 |
| Columns | 3 |
| File created | 2026-07-05T03:43:41.210253+00:00 |
| File last modified | 2026-07-05T03:52:03.359135+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 809; 828; 829 |
| `CPC Code` | '01929.07; '25020.01; '25020.02 |
| `Item` | Abaca; manila hemp; raw; Cigarettes; Cigars and cheroots |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 2.1MB |
| Rows | 1,184,986 |
| Columns | 13 |
| File created | 2026-07-05T03:43:41.299633+00:00 |
| File last modified | 2026-07-05T03:52:04.115804+00:00 |
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
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 2600; 2661; 2559 |
| `Item Code (CPC)` | 'B2600; 'B2661; 'S2559 |
| `Item` | Brans; Cotton lint; Cottonseed |
| `Element Code` | 5510; 5300; 5520 |
| `Element` | Production; Domestic supply quantity; Feed |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | tonnes |
| `Value` | 468407.0; 463852.0; 417196.0 |
| `Flag` | I; E |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.8KB |
| Rows | 217 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.156373+00:00 |
| File last modified | 2026-07-05T03:52:04.401821+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_E_Flags.parquet |
| Format | parquet |
| File size | 881.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:41.434136+00:00 |
| File last modified | 2026-07-05T03:52:04.404820+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E; I |
| `Description` | Estimated value; Imputed value |


---

# FAOSTAT_A-S_E__CommodityBalances_(non-food)_E_All_Data_(Normalized)__CommodityBalances_(non-food)_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/CommodityBalances_(non-food)_E_All_Data_(Normalized)/CommodityBalances_(non-food)_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.7KB |
| Rows | 28 |
| Columns | 3 |
| File created | 2026-07-05T03:43:41.449427+00:00 |
| File last modified | 2026-07-05T03:52:04.410827+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 2558; 2559; 2562 |
| `CPC Code` | 'S2558; 'S2559; 'S2562 |
| `Item` | Rape and Mustardseed; Cottonseed; Palm kernels |


---

# FAOSTAT_A-S_E__ConsumerPriceIndices_E_All_Data_(Normalized)__ConsumerPriceIndices_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ConsumerPriceIndices_E_All_Data_(Normalized)/ConsumerPriceIndices_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 1.6MB |
| Rows | 248,394 |
| Columns | 15 |
| File created | 2026-07-05T03:43:41.541133+00:00 |
| File last modified | 2026-07-05T03:52:04.542635+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Months Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Months` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 79,295 | 31.92% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 284; 3 |
| `Area Code (M49)` | '004; '248; '008 |
| `Area` | Afghanistan; Åland Islands; Albania |
| `Item Code` | 23013; 23012; 23014 |
| `Item` | Consumer Prices, Food Indices (2015 = 100); Consumer Prices, General Indices (2015 = 100); Food price inflation |
| `Element Code` | 6125; 6121 |
| `Element` | Value |
| `Months Code` | 7001; 7002; 7003 |
| `Months` | January; February; March |
| `Year Code` | 2000; 2001; 2002 |
| `Year` | 2000; 2001; 2002 |
| `Unit` | ; % |
| `Value` | 24.356332; 29.944592; 33.421952 |
| `Flag` | I; X; A |
| `Note` | base year is 2015 |


---

# FAOSTAT_A-S_E__ConsumerPriceIndices_E_All_Data_(Normalized)__ConsumerPriceIndices_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ConsumerPriceIndices_E_All_Data_(Normalized)/ConsumerPriceIndices_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.2KB |
| Rows | 252 |
| Columns | 3 |
| File created | 2026-07-05T03:43:41.711840+00:00 |
| File last modified | 2026-07-05T03:52:04.547645+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 284 |
| `M49 Code` | '004; '002; '248 |
| `Area` | Afghanistan; Africa; Åland Islands |


---

# FAOSTAT_A-S_E__ConsumerPriceIndices_E_All_Data_(Normalized)__ConsumerPriceIndices_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ConsumerPriceIndices_E_All_Data_(Normalized)/ConsumerPriceIndices_E_Elements.parquet |
| Format | parquet |
| File size | 881.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:41.723931+00:00 |
| File last modified | 2026-07-05T03:52:04.551665+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6121; 6125 |
| `Element` | Value |


---

# FAOSTAT_A-S_E__ConsumerPriceIndices_E_All_Data_(Normalized)__ConsumerPriceIndices_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ConsumerPriceIndices_E_All_Data_(Normalized)/ConsumerPriceIndices_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:41.730055+00:00 |
| File last modified | 2026-07-05T03:52:04.554647+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__ConsumerPriceIndices_E_All_Data_(Normalized)__ConsumerPriceIndices_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/ConsumerPriceIndices_E_All_Data_(Normalized)/ConsumerPriceIndices_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 9 |
| Columns | 2 |
| File created | 2026-07-05T03:43:41.744075+00:00 |
| File last modified | 2026-07-05T03:52:04.559645+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 23013; 230132; 230131 |
| `Item` | Consumer Prices; Food Indices (2015 = 100); Consumer Prices; Food Indices (2015 = 100); median; Consumer Prices; Food Indices (2015 = 100); weighted average |


---

# FAOSTAT_A-S_E__Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)__Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)/Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 35.1KB |
| Rows | 11,672 |
| Columns | 14 |
| File created | 2026-07-05T03:43:41.797563+00:00 |
| File last modified | 2026-07-05T03:52:04.609871+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Release Code` | String | Categorical | No | 0 | 0.0% |
| `Release` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | String | Categorical | Yes | 1,207 | 10.34% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 7005; 7006; 70041 |
| `Item` | Prevalence of unaffordability (PUA), percent; Number of people unable to afford a healthy diet (NUA), million; Cost of a healthy diet (CoHD), LCU per person per day |
| `Element Code` | 6121; 6132; 6205 |
| `Element` | Value |
| `Year Code` | 2017; 2018; 2019 |
| `Year` | 2017; 2018; 2019 |
| `Release Code` | 12U2024; 7S2025 |
| `Release` | December 2024 (Update); July 2025 (SOFI report) |
| `Unit` | %; million No; LCU/cap/d |
| `Value` | 160.41; 164.71; 169.51 |
| `Flag` | O; E; Q |


---

# FAOSTAT_A-S_E__Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)__Cost_Affordability_Healthy_Diet_(CoAHD)_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)/Cost_Affordability_Healthy_Diet_(CoAHD)_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.4KB |
| Rows | 263 |
| Columns | 3 |
| File created | 2026-07-05T03:43:41.842126+00:00 |
| File last modified | 2026-07-05T03:52:04.614867+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)__Cost_Affordability_Healthy_Diet_(CoAHD)_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)/Cost_Affordability_Healthy_Diet_(CoAHD)_E_Elements.parquet |
| Format | parquet |
| File size | 904.0B |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:41.853503+00:00 |
| File last modified | 2026-07-05T03:52:04.617867+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 6121; 6132; 6205 |
| ` Element` | Value |


---

# FAOSTAT_A-S_E__Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)__Cost_Affordability_Healthy_Diet_(CoAHD)_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)/Cost_Affordability_Healthy_Diet_(CoAHD)_E_Flags.parquet |
| Format | parquet |
| File size | 972.0B |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:43:41.866194+00:00 |
| File last modified | 2026-07-05T03:52:04.620871+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | E; O; Q |
| ` Description` | Estimated value; Missing value; Missing value; suppressed |


---

# FAOSTAT_A-S_E__Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)__Cost_Affordability_Healthy_Diet_(CoAHD)_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)/Cost_Affordability_Healthy_Diet_(CoAHD)_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:43:41.872538+00:00 |
| File last modified | 2026-07-05T03:52:04.625884+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)__Cost_Affordability_Healthy_Diet_(CoAHD)_E_Releases

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Cost_Affordability_Healthy_Diet_(CoAHD)_E_All_Data_(Normalized)/Cost_Affordability_Healthy_Diet_(CoAHD)_E_Releases.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:41.884631+00:00 |
| File last modified | 2026-07-05T03:52:04.629571+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Release Code` | String | Categorical | No | 0 | 0.0% |
| ` Release` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Release Code` | 12U2024; 7S2025 |
| ` Release` | December 2024 (Update); July 2025 (SOFI report) |


---

# FAOSTAT_A-S_E__Deflators_E_All_Data_(Normalized)__Deflators_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Deflators_E_All_Data_(Normalized)/Deflators_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 628.4KB |
| Rows | 92,776 |
| Columns | 12 |
| File created | 2026-07-05T03:43:41.965243+00:00 |
| File last modified | 2026-07-05T03:52:04.734787+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 22024; 22025; 22026 |
| `Item` | GDP Deflator; Gross Fixed Capital Formation Deflator; Value Added Deflator (Agriculture, forestry and fishery) |
| `Element Code` | 62250; 6179 |
| `Element` | Value Standard Local Currency, 2015 prices; Value US$, 2015 prices |
| `Year Code` | 1970; 1971; 1972 |
| `Year` | 1970; 1971; 1972 |
| `Unit` | SLC; USD |
| `Value` | 0.0121697308; 0.0127771078; 0.0133177339 |
| `Flag` | X; E |


---

# FAOSTAT_A-S_E__Deflators_E_All_Data_(Normalized)__Deflators_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Deflators_E_All_Data_(Normalized)/Deflators_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.2KB |
| Rows | 252 |
| Columns | 3 |
| File created | 2026-07-05T03:43:42.060165+00:00 |
| File last modified | 2026-07-05T03:52:04.738787+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Deflators_E_All_Data_(Normalized)__Deflators_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Deflators_E_All_Data_(Normalized)/Deflators_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:42.072500+00:00 |
| File last modified | 2026-07-05T03:52:04.742231+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 62250; 6179 |
| ` Element` | Value Standard Local Currency; 2015 prices; Value US$; 2015 prices |


---

# FAOSTAT_A-S_E__Deflators_E_All_Data_(Normalized)__Deflators_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Deflators_E_All_Data_(Normalized)/Deflators_E_Flags.parquet |
| Format | parquet |
| File size | 999.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:42.087914+00:00 |
| File last modified | 2026-07-05T03:52:04.744231+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | E; X |
| ` Description` | Estimated value; Figure from external organization |


---

# FAOSTAT_A-S_E__Deflators_E_All_Data_(Normalized)__Deflators_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Deflators_E_All_Data_(Normalized)/Deflators_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:43:42.095009+00:00 |
| File last modified | 2026-07-05T03:52:04.749232+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Development_Assistance_to_Agriculture_E_All_Data_(Normalized)__Development_Assistance_to_Agriculture_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Development_Assistance_to_Agriculture_E_All_Data_(Normalized)/Development_Assistance_to_Agriculture_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 81.1MB |
| Rows | 13,020,275 |
| Columns | 18 |
| File created | 2026-07-05T03:43:42.203422+00:00 |
| File last modified | 2026-07-05T03:52:10.225015+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Donor Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Donor Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Donor` | String | Categorical | No | 0 | 0.0% |
| `Recipient Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Recipient Country Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Recipient Country` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Purpose Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Purpose` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 13,020,275 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Donor Code` | 1033; 1034; 1031 |
| `Donor Code (M49)` | 'F1033; '1011; '1013 |
| `Donor` | Consultative Group on International Agric Research (CGIAR); Climate Investment Funds (CIF); Council of Europe Development Bank (CEB) |
| `Recipient Country Code` | 5000; 16; 3 |
| `Recipient Country Code (M49)` | '001; '050; '008 |
| `Recipient Country` | World; Bangladesh; Albania |
| `Item Code` | 22040; 22041; 22043 |
| `Item` | Commitment; Commitment ODA; Commitment Private Grant |
| `Element Code` | 6110; 6230; 6159 |
| `Element` | Value US$; Value US$, 2023 prices; Agriculture orientation index US$ |
| `Purpose Code` | 310; 311; 307 |
| `Purpose` | Agriculture, forestry, fishing; Agriculture; Rural Development |
| `Year Code` | 2022; 2023; 2013 |
| `Year` | 2022; 2023; 2013 |
| `Unit` | million USD; ; % |
| `Value` | 110.532; 74.301; 3.099419 |
| `Flag` | X; E |


---

# FAOSTAT_A-S_E__Development_Assistance_to_Agriculture_E_All_Data_(Normalized)__Development_Assistance_to_Agriculture_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Development_Assistance_to_Agriculture_E_All_Data_(Normalized)/Development_Assistance_to_Agriculture_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:50.098096+00:00 |
| File last modified | 2026-07-05T03:52:10.228996+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 6159; 6139; 6110 |
| ` Element` | Agriculture orientation index US$; Share of Total US$; Value US$ |


---

# FAOSTAT_A-S_E__Development_Assistance_to_Agriculture_E_All_Data_(Normalized)__Development_Assistance_to_Agriculture_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Development_Assistance_to_Agriculture_E_All_Data_(Normalized)/Development_Assistance_to_Agriculture_E_Flags.parquet |
| Format | parquet |
| File size | 999.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:50.104096+00:00 |
| File last modified | 2026-07-05T03:52:10.230995+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | E; X |
| ` Description` | Estimated value; Figure from external organization |


---

# FAOSTAT_A-S_E__Development_Assistance_to_Agriculture_E_All_Data_(Normalized)__Development_Assistance_to_Agriculture_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Development_Assistance_to_Agriculture_E_All_Data_(Normalized)/Development_Assistance_to_Agriculture_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:43:50.114104+00:00 |
| File last modified | 2026-07-05T03:52:10.233996+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Development_Assistance_to_Agriculture_E_All_Data_(Normalized)__Development_Assistance_to_Agriculture_E_Purposes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Development_Assistance_to_Agriculture_E_All_Data_(Normalized)/Development_Assistance_to_Agriculture_E_Purposes.parquet |
| Format | parquet |
| File size | 1.9KB |
| Rows | 58 |
| Columns | 2 |
| File created | 2026-07-05T03:43:50.135216+00:00 |
| File last modified | 2026-07-05T03:52:10.237997+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Purpose Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Purpose` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Purpose Code` | 31164; 31165; 31194 |
| ` Purpose` | Agrarian reform; Agricultural alternative development; Agricultural co-operatives |


---

# FAOSTAT_A-S_E__Emissions_Agriculture_Energy_E_All_Data_(Normalized)__Emissions_Agriculture_Energy_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Agriculture_Energy_E_All_Data_(Normalized)/Emissions_Agriculture_Energy_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 384.1KB |
| Rows | 120,740 |
| Columns | 12 |
| File created | 2026-07-05T03:43:50.210866+00:00 |
| File last modified | 2026-07-05T03:52:10.316597+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6807; 6813; 6801 |
| `Item` | Electricity; Total Energy; Petroleum products |
| `Element Code` | 72184; 7273; 7225 |
| `Element` | Energy use in agriculture; Emissions (CO2); Emissions (CH4) |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Unit` | TJ; kt |
| `Value` | 115.2; 100.8; 79.2 |
| `Flag` | E; A; I |


---

# FAOSTAT_A-S_E__Emissions_Agriculture_Energy_E_All_Data_(Normalized)__Emissions_Agriculture_Energy_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Agriculture_Energy_E_All_Data_(Normalized)/Emissions_Agriculture_Energy_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.5KB |
| Rows | 280 |
| Columns | 3 |
| File created | 2026-07-05T03:43:50.320604+00:00 |
| File last modified | 2026-07-05T03:52:10.319575+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Emissions_Agriculture_Energy_E_All_Data_(Normalized)__Emissions_Agriculture_Energy_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Agriculture_Energy_E_All_Data_(Normalized)/Emissions_Agriculture_Energy_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:50.336715+00:00 |
| File last modified | 2026-07-05T03:52:10.322576+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 7225; 7273; 7230 |
| ` Element` | Emissions (CH4); Emissions (CO2); Emissions (N2O) |


---

# FAOSTAT_A-S_E__Emissions_Agriculture_Energy_E_All_Data_(Normalized)__Emissions_Agriculture_Energy_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Agriculture_Energy_E_All_Data_(Normalized)/Emissions_Agriculture_Energy_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:43:50.347854+00:00 |
| File last modified | 2026-07-05T03:52:10.325579+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Emissions_Agriculture_Energy_E_All_Data_(Normalized)__Emissions_Agriculture_Energy_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Agriculture_Energy_E_All_Data_(Normalized)/Emissions_Agriculture_Energy_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:43:50.354774+00:00 |
| File last modified | 2026-07-05T03:52:10.328578+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

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


---

# FAOSTAT_A-S_E__Emissions_crops_E_All_Data_(Normalized)__Emissions_crops_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_crops_E_All_Data_(Normalized)/Emissions_crops_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 282 |
| Columns | 3 |
| File created | 2026-07-05T03:43:50.884892+00:00 |
| File last modified | 2026-07-05T03:52:10.669399+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Emissions_crops_E_All_Data_(Normalized)__Emissions_crops_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_crops_E_All_Data_(Normalized)/Emissions_crops_E_Elements.parquet |
| Format | parquet |
| File size | 1.5KB |
| Rows | 23 |
| Columns | 2 |
| File created | 2026-07-05T03:43:50.902894+00:00 |
| File last modified | 2026-07-05T03:52:10.671406+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 5312; 5066; 7245 |
| `Element` | Area harvested; Burning - Crop residues; Burning crop residues (Biomass burned; dry matter) |


---

# FAOSTAT_A-S_E__Emissions_crops_E_All_Data_(Normalized)__Emissions_crops_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_crops_E_All_Data_(Normalized)/Emissions_crops_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 8 |
| Columns | 2 |
| File created | 2026-07-05T03:43:50.919959+00:00 |
| File last modified | 2026-07-05T03:52:10.674407+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; B; E |
| ` Description` | Official figure; Time series break; Estimated value |


---

# FAOSTAT_A-S_E__Emissions_crops_E_All_Data_(Normalized)__Emissions_crops_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_crops_E_All_Data_(Normalized)/Emissions_crops_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.4KB |
| Rows | 14 |
| Columns | 3 |
| File created | 2026-07-05T03:43:50.935189+00:00 |
| File last modified | 2026-07-05T03:52:10.676406+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 1712; 44; 176 |
| `CPC Code` | 'F1712; '0115; '01701 |
| `Item` | All Crops; Barley; Beans; dry |


---

# FAOSTAT_A-S_E__Emissions_crops_E_All_Data_(Normalized)__Emissions_crops_E_Sources

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_crops_E_All_Data_(Normalized)/Emissions_crops_E_Sources.parquet |
| Format | parquet |
| File size | 915.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:50.948083+00:00 |
| File last modified | 2026-07-05T03:52:10.680410+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Source Code` | 3050; 3051 |
| `Source` | FAO TIER 1; UNFCCC |


---

# FAOSTAT_A-S_E__Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)__Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)/Emissions_Drained_Organic_Soils_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 193.7KB |
| Rows | 87,484 |
| Columns | 15 |
| File created | 2026-07-05T03:43:51.015254+00:00 |
| File last modified | 2026-07-05T03:52:10.754689+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 84,375 | 96.45% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6727; 6728; 6729 |
| `Item` | Cropland organic soils; Grassland organic soils; Drained organic soils |
| `Element Code` | 5026; 7230; 7273 |
| `Element` | Area; Emissions (N2O); Emissions (CO2) |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Source Code` | 3050; 3051 |
| `Source` | FAO TIER 1; UNFCCC |
| `Unit` | ha; kt |
| `Value` | 0.0; 3708.0508; 3707.095 |
| `Flag` | E; I; A |
| `Note` | NC/CRF/BUR |


---

# FAOSTAT_A-S_E__Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)__Emissions_Drained_Organic_Soils_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)/Emissions_Drained_Organic_Soils_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.5KB |
| Rows | 280 |
| Columns | 3 |
| File created | 2026-07-05T03:43:51.108944+00:00 |
| File last modified | 2026-07-05T03:52:10.759228+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)__Emissions_Drained_Organic_Soils_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)/Emissions_Drained_Organic_Soils_E_Elements.parquet |
| Format | parquet |
| File size | 1019.0B |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:51.123851+00:00 |
| File last modified | 2026-07-05T03:52:10.761228+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 5026; 7273; 7230 |
| ` Element` | Area; Emissions (CO2); Emissions (N2O) |


---

# FAOSTAT_A-S_E__Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)__Emissions_Drained_Organic_Soils_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)/Emissions_Drained_Organic_Soils_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:43:51.128607+00:00 |
| File last modified | 2026-07-05T03:52:10.763228+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)__Emissions_Drained_Organic_Soils_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)/Emissions_Drained_Organic_Soils_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:43:51.133611+00:00 |
| File last modified | 2026-07-05T03:52:10.765229+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)__Emissions_Drained_Organic_Soils_E_Sources

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Drained_Organic_Soils_E_All_Data_(Normalized)/Emissions_Drained_Organic_Soils_E_Sources.parquet |
| Format | parquet |
| File size | 921.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:51.145617+00:00 |
| File last modified | 2026-07-05T03:52:10.767230+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Source` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Source Code` | 3050; 3051 |
| ` Source` | FAO TIER 1; UNFCCC |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Fires_E_All_Data_(Normalized)__Emissions_Land_Use_Fires_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Fires_E_All_Data_(Normalized)/Emissions_Land_Use_Fires_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 1002.2KB |
| Rows | 428,963 |
| Columns | 15 |
| File created | 2026-07-05T03:43:51.233520+00:00 |
| File last modified | 2026-07-05T03:52:10.955005+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 423,454 | 98.72% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6992; 6796; 6797 |
| `Item` | Forest fires; Humid tropical forest; Other forest |
| `Element Code` | 7245; 7246; 7225 |
| `Element` | Burning crop residues (Biomass burned, dry matter); Burned Area; Emissions (CH4) |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Source Code` | 3050; 3051 |
| `Source` | FAO TIER 1; UNFCCC |
| `Unit` | t; ha; kt |
| `Value` | 248.9852; 1004.7694; 594.3924 |
| `Flag` | E; A |
| `Note` | NC/CRF/BUR |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Fires_E_All_Data_(Normalized)__Emissions_Land_Use_Fires_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Fires_E_All_Data_(Normalized)/Emissions_Land_Use_Fires_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.5KB |
| Rows | 280 |
| Columns | 3 |
| File created | 2026-07-05T03:43:51.466596+00:00 |
| File last modified | 2026-07-05T03:52:10.958943+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Fires_E_All_Data_(Normalized)__Emissions_Land_Use_Fires_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Fires_E_All_Data_(Normalized)/Emissions_Land_Use_Fires_E_Elements.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:43:51.477593+00:00 |
| File last modified | 2026-07-05T03:52:10.962749+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 7246; 7245; 7225 |
| ` Element` | Burned Area; Burning crop residues (Biomass burned; dry matter); Emissions (CH4) |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Fires_E_All_Data_(Normalized)__Emissions_Land_Use_Fires_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Fires_E_All_Data_(Normalized)/Emissions_Land_Use_Fires_E_Flags.parquet |
| Format | parquet |
| File size | 908.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:51.489119+00:00 |
| File last modified | 2026-07-05T03:52:10.964747+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E |
| ` Description` | Official figure; Estimated value |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Fires_E_All_Data_(Normalized)__Emissions_Land_Use_Fires_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Fires_E_All_Data_(Normalized)/Emissions_Land_Use_Fires_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:43:51.496163+00:00 |
| File last modified | 2026-07-05T03:52:10.968771+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Fires_E_All_Data_(Normalized)__Emissions_Land_Use_Fires_E_Sources

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Fires_E_All_Data_(Normalized)/Emissions_Land_Use_Fires_E_Sources.parquet |
| Format | parquet |
| File size | 921.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:51.501432+00:00 |
| File last modified | 2026-07-05T03:52:10.970767+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Source` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Source Code` | 3050; 3051 |
| ` Source` | FAO TIER 1; UNFCCC |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Forests_E_All_Data_(Normalized)__Emissions_Land_Use_Forests_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Forests_E_All_Data_(Normalized)/Emissions_Land_Use_Forests_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 161.2KB |
| Rows | 65,639 |
| Columns | 15 |
| File created | 2026-07-05T03:43:51.570953+00:00 |
| File last modified | 2026-07-05T03:52:11.039466+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 65,639 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6751; 6750; 6749 |
| `Item` | Forestland; Net Forest conversion; Carbon stock change in forests |
| `Element Code` | 5110; 72332 |
| `Element` | Area; Net emissions/removals (CO2) (Forest land) |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Source Code` | 3050; 3051 |
| `Source` | FAO TIER 1; UNFCCC |
| `Unit` | 1000 ha; kt |
| `Value` | 1209.44; 0.0; 788.8 |
| `Flag` | X; I; E |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Forests_E_All_Data_(Normalized)__Emissions_Land_Use_Forests_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Forests_E_All_Data_(Normalized)/Emissions_Land_Use_Forests_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 285 |
| Columns | 3 |
| File created | 2026-07-05T03:43:51.658664+00:00 |
| File last modified | 2026-07-05T03:52:11.043761+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Forests_E_All_Data_(Normalized)__Emissions_Land_Use_Forests_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Forests_E_All_Data_(Normalized)/Emissions_Land_Use_Forests_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:51.669841+00:00 |
| File last modified | 2026-07-05T03:52:11.046762+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 5110; 72332 |
| ` Element` | Area; Net emissions/removals (CO2) (Forest land) |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Forests_E_All_Data_(Normalized)__Emissions_Land_Use_Forests_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Forests_E_All_Data_(Normalized)/Emissions_Land_Use_Forests_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:51.681008+00:00 |
| File last modified | 2026-07-05T03:52:11.049761+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Forests_E_All_Data_(Normalized)__Emissions_Land_Use_Forests_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Forests_E_All_Data_(Normalized)/Emissions_Land_Use_Forests_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:43:51.686015+00:00 |
| File last modified | 2026-07-05T03:52:11.053764+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Emissions_Land_Use_Forests_E_All_Data_(Normalized)__Emissions_Land_Use_Forests_E_Sources

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Land_Use_Forests_E_All_Data_(Normalized)/Emissions_Land_Use_Forests_E_Sources.parquet |
| Format | parquet |
| File size | 921.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:51.693045+00:00 |
| File last modified | 2026-07-05T03:52:11.056760+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Source` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Source Code` | 3050; 3051 |
| ` Source` | FAO TIER 1; UNFCCC |


---

# FAOSTAT_A-S_E__Emissions_livestock_E_All_Data_(Normalized)__Emissions_livestock_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_livestock_E_All_Data_(Normalized)/Emissions_livestock_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 20.1MB |
| Rows | 6,650,421 |
| Columns | 16 |
| File created | 2026-07-05T03:43:51.786012+00:00 |
| File last modified | 2026-07-05T03:52:13.329352+00:00 |
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
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 6,565,094 | 98.72% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 1107; 1126; 960 |
| `Item Code (CPC)` | '02132; '02121.01; 'F0960 |
| `Item` | Asses; Camels; Cattle, dairy |
| `Element Code` | 5111; 72431; 72441 |
| `Element` | Stocks; Livestock total (Emissions N2O); Livestock total (Emissions CH4) |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Source Code` | 3050; 3051 |
| `Source` | FAO TIER 1; UNFCCC |
| `Unit` | An; kt; kg |
| `Value` | 1300000.0; 851850.0; 1001112.0 |
| `Flag` | A; E; X |
| `Note` | ; UNFCCC Repository; NC/CRF/BUR |


---

# FAOSTAT_A-S_E__Emissions_livestock_E_All_Data_(Normalized)__Emissions_livestock_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_livestock_E_All_Data_(Normalized)/Emissions_livestock_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 281 |
| Columns | 3 |
| File created | 2026-07-05T03:43:54.483862+00:00 |
| File last modified | 2026-07-05T03:52:13.334352+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Emissions_livestock_E_All_Data_(Normalized)__Emissions_livestock_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_livestock_E_All_Data_(Normalized)/Emissions_livestock_E_Elements.parquet |
| Format | parquet |
| File size | 1.4KB |
| Rows | 29 |
| Columns | 2 |
| File created | 2026-07-05T03:43:54.497217+00:00 |
| File last modified | 2026-07-05T03:52:13.337352+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 72301; 5058; 72254 |
| ` Element` | Emissions (N2O) (Manure applied); Enteric Fermentation; Enteric fermentation (Emissions CH4) |


---

# FAOSTAT_A-S_E__Emissions_livestock_E_All_Data_(Normalized)__Emissions_livestock_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_livestock_E_All_Data_(Normalized)/Emissions_livestock_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:43:54.512212+00:00 |
| File last modified | 2026-07-05T03:52:13.341354+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E; F |
| ` Description` | Official figure; Estimated value; Forecast value |


---

# FAOSTAT_A-S_E__Emissions_livestock_E_All_Data_(Normalized)__Emissions_livestock_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_livestock_E_All_Data_(Normalized)/Emissions_livestock_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.6KB |
| Rows | 24 |
| Columns | 3 |
| File created | 2026-07-05T03:43:54.525449+00:00 |
| File last modified | 2026-07-05T03:52:13.346351+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Item Code` | 1016; 1048; 1049 |
| ` CPC Code` | '02123; 'F1048; 'F1049 |
| ` Item` | Goats; Swine; Swine; market |


---

# FAOSTAT_A-S_E__Emissions_livestock_E_All_Data_(Normalized)__Emissions_livestock_E_Sources

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_livestock_E_All_Data_(Normalized)/Emissions_livestock_E_Sources.parquet |
| Format | parquet |
| File size | 921.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:54.532028+00:00 |
| File last modified | 2026-07-05T03:52:13.350352+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Source` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Source Code` | 3050; 3051 |
| ` Source` | FAO TIER 1; UNFCCC |


---

# FAOSTAT_A-S_E__Emissions_Pre_Post_Production_E_All_Data_(Normalized)__Emissions_Pre_Post_Production_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Pre_Post_Production_E_All_Data_(Normalized)/Emissions_Pre_Post_Production_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 2.8MB |
| Rows | 522,216 |
| Columns | 12 |
| File created | 2026-07-05T03:43:54.627904+00:00 |
| File last modified | 2026-07-05T03:52:13.553235+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6504; 6815; 6508 |
| `Item` | Fertilizers Manufacturing; Food Transport; Food Retail |
| `Element Code` | 7273; 723113; 7225 |
| `Element` | Emissions (CO2); Emissions (CO2eq) (AR5); Emissions (CH4) |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Unit` | kt; TJ |
| `Value` | 11.997046; 12.853935; 13.492864 |
| `Flag` | E; I |


---

# FAOSTAT_A-S_E__Emissions_Pre_Post_Production_E_All_Data_(Normalized)__Emissions_Pre_Post_Production_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Pre_Post_Production_E_All_Data_(Normalized)/Emissions_Pre_Post_Production_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.9KB |
| Rows | 302 |
| Columns | 3 |
| File created | 2026-07-05T03:43:54.899814+00:00 |
| File last modified | 2026-07-05T03:52:13.556943+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 284 |
| `M49 Code` | '004; '002; '248 |
| `Area` | Afghanistan; Africa; Åland Islands |


---

# FAOSTAT_A-S_E__Emissions_Pre_Post_Production_E_All_Data_(Normalized)__Emissions_Pre_Post_Production_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Pre_Post_Production_E_All_Data_(Normalized)/Emissions_Pre_Post_Production_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 11 |
| Columns | 2 |
| File created | 2026-07-05T03:43:54.913819+00:00 |
| File last modified | 2026-07-05T03:52:13.558940+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 7225; 7273; 723113 |
| `Element` | Emissions (CH4); Emissions (CO2); Emissions (CO2eq) (AR5) |


---

# FAOSTAT_A-S_E__Emissions_Pre_Post_Production_E_All_Data_(Normalized)__Emissions_Pre_Post_Production_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Pre_Post_Production_E_All_Data_(Normalized)/Emissions_Pre_Post_Production_E_Flags.parquet |
| Format | parquet |
| File size | 1007.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:54.934814+00:00 |
| File last modified | 2026-07-05T03:52:13.560944+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E; I |
| ` Description` | Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Emissions_Pre_Post_Production_E_All_Data_(Normalized)__Emissions_Pre_Post_Production_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Pre_Post_Production_E_All_Data_(Normalized)/Emissions_Pre_Post_Production_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 15 |
| Columns | 2 |
| File created | 2026-07-05T03:43:54.948332+00:00 |
| File last modified | 2026-07-05T03:52:13.563943+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 6991; 6998; 6988 |
| `Item` | Agrifood Systems Waste Disposal; Cold Chain F-Gas; Domestic Wastewater |


---

# FAOSTAT_A-S_E__Emissions_Totals_E_All_Data_(Normalized)__Emissions_Totals_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Totals_E_All_Data_(Normalized)/Emissions_Totals_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 7.8MB |
| Rows | 2,500,090 |
| Columns | 15 |
| File created | 2026-07-05T03:43:55.055636+00:00 |
| File last modified | 2026-07-05T03:52:14.366910+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 2,500,090 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 5064; 5060; 5066 |
| `Item` | Crop Residues; Rice Cultivation; Burning - Crop residues |
| `Element Code` | 7234; 7236; 7230 |
| `Element` | Direct emissions (N2O); Indirect emissions (N2O); Emissions (N2O) |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Source Code` | 3050; 3051 |
| `Source` | FAO TIER 1; UNFCCC |
| `Unit` | kt |
| `Value` | 0.8762; 0.8829; 0.8236 |
| `Flag` | E; F; A |


---

# FAOSTAT_A-S_E__Emissions_Totals_E_All_Data_(Normalized)__Emissions_Totals_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Totals_E_All_Data_(Normalized)/Emissions_Totals_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 281 |
| Columns | 3 |
| File created | 2026-07-05T03:43:56.310571+00:00 |
| File last modified | 2026-07-05T03:52:14.370894+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Emissions_Totals_E_All_Data_(Normalized)__Emissions_Totals_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Totals_E_All_Data_(Normalized)/Emissions_Totals_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 9 |
| Columns | 2 |
| File created | 2026-07-05T03:43:56.322508+00:00 |
| File last modified | 2026-07-05T03:52:14.372901+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 7234; 7225; 7273 |
| `Element` | Direct emissions (N2O); Emissions (CH4); Emissions (CO2) |


---

# FAOSTAT_A-S_E__Emissions_Totals_E_All_Data_(Normalized)__Emissions_Totals_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Totals_E_All_Data_(Normalized)/Emissions_Totals_E_Flags.parquet |
| Format | parquet |
| File size | 933.0B |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:43:56.332516+00:00 |
| File last modified | 2026-07-05T03:52:14.375902+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; F |
| ` Description` | Official figure; Estimated value; Forecast value |


---

# FAOSTAT_A-S_E__Emissions_Totals_E_All_Data_(Normalized)__Emissions_Totals_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Totals_E_All_Data_(Normalized)/Emissions_Totals_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.8KB |
| Rows | 47 |
| Columns | 3 |
| File created | 2026-07-05T03:43:56.349515+00:00 |
| File last modified | 2026-07-05T03:52:14.379915+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | Yes | 47 | 100.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 6824; 1709; 6518 |
| `Item` | AFOLU; Agricultural Soils; Agrifood systems |


---

# FAOSTAT_A-S_E__Emissions_Totals_E_All_Data_(Normalized)__Emissions_Totals_E_Sources

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Emissions_Totals_E_All_Data_(Normalized)/Emissions_Totals_E_Sources.parquet |
| Format | parquet |
| File size | 915.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:56.356644+00:00 |
| File last modified | 2026-07-05T03:52:14.383901+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Source Code` | 3050; 3051 |
| `Source` | FAO TIER 1; UNFCCC |


---

# FAOSTAT_A-S_E__Employment_Indicators_Agriculture_E_All_Data_(Normalized)__Employment_Indicators_Agriculture_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Agriculture_E_All_Data_(Normalized)/Employment_Indicators_Agriculture_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 891.0KB |
| Rows | 256,389 |
| Columns | 17 |
| File created | 2026-07-05T03:43:56.459460+00:00 |
| File last modified | 2026-07-05T03:52:14.570675+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Sex` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | Yes | 19 | 0.01% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 79,957 | 31.19% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Source Code` | 3044; 3043; 3047 |
| `Source` | FAO Model; ILO - ILO Modelled Estimates; ILO - Modelled Estimates; FAOSTAT - Value added (2015 US$) |
| `Indicator Code` | 21160; 21163; 21161 |
| `Indicator` | Total employment in agrifood systems (AFS); Total non-agricultural AFS employment; Share of AFS employment in total employment |
| `Sex Code` | 1; 2; 3 |
| `Sex` | Total; Male; Female |
| `Element Code` | 6199; 6121; 6228 |
| `Element` | Value |
| `Year Code` | 2000; 2001; 2002 |
| `Year` | 2000; 2001; 2002 |
| `Unit` | 1000 No; %; USD |
| `Value` | 3253.94; 3297.24; 3426.5 |
| `Flag` | E; X; B |
| `Note` | Modelled FAO; Modelled using ISIC shares; Imputed using average of previous and next value |


---

# FAOSTAT_A-S_E__Employment_Indicators_Agriculture_E_All_Data_(Normalized)__Employment_Indicators_Agriculture_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Agriculture_E_All_Data_(Normalized)/Employment_Indicators_Agriculture_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.4KB |
| Rows | 270 |
| Columns | 3 |
| File created | 2026-07-05T03:43:56.698270+00:00 |
| File last modified | 2026-07-05T03:52:14.574520+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Employment_Indicators_Agriculture_E_All_Data_(Normalized)__Employment_Indicators_Agriculture_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Agriculture_E_All_Data_(Normalized)/Employment_Indicators_Agriculture_E_Elements.parquet |
| Format | parquet |
| File size | 891.0B |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:56.709360+00:00 |
| File last modified | 2026-07-05T03:52:14.576520+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6121; 6173; 6199 |
| `Element` | Value |


---

# FAOSTAT_A-S_E__Employment_Indicators_Agriculture_E_All_Data_(Normalized)__Employment_Indicators_Agriculture_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Agriculture_E_All_Data_(Normalized)/Employment_Indicators_Agriculture_E_Flags.parquet |
| Format | parquet |
| File size | 1015.0B |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:43:56.724371+00:00 |
| File last modified | 2026-07-05T03:52:14.579519+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | B; E; L |
| ` Description` | Time series break; Estimated value; Missing value; data exist but were not collected |


---

# FAOSTAT_A-S_E__Employment_Indicators_Agriculture_E_All_Data_(Normalized)__Employment_Indicators_Agriculture_E_Indicators

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Agriculture_E_All_Data_(Normalized)/Employment_Indicators_Agriculture_E_Indicators.parquet |
| Format | parquet |
| File size | 1.9KB |
| Rows | 38 |
| Columns | 2 |
| File created | 2026-07-05T03:43:56.742990+00:00 |
| File last modified | 2026-07-05T03:52:14.582528+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Indicator Code` | 21085; 21144; 21145 |
| `Indicator` | Agriculture value added per worker (constant 2015 US$); Employment in agriculture - ILO modelled estimates; Employment in agriculture by age |


---

# FAOSTAT_A-S_E__Employment_Indicators_Agriculture_E_All_Data_(Normalized)__Employment_Indicators_Agriculture_E_Sexes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Agriculture_E_All_Data_(Normalized)/Employment_Indicators_Agriculture_E_Sexes.parquet |
| Format | parquet |
| File size | 874.0B |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:43:56.757020+00:00 |
| File last modified | 2026-07-05T03:52:14.585538+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Sex` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Sex Code` | 3; 2; 1 |
| `Sex` | Female; Male; Total |


---

# FAOSTAT_A-S_E__Employment_Indicators_Agriculture_E_All_Data_(Normalized)__Employment_Indicators_Agriculture_E_Sources

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Agriculture_E_All_Data_(Normalized)/Employment_Indicators_Agriculture_E_Sources.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 15 |
| Columns | 2 |
| File created | 2026-07-05T03:43:56.767020+00:00 |
| File last modified | 2026-07-05T03:52:14.588042+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Source Code` | 3044; 3043; 3047 |
| `Source` | FAO Model; ILO - ILO Modelled Estimates; ILO - Modelled Estimates; FAOSTAT - Value added (2015 US$) |


---

# FAOSTAT_A-S_E__Employment_Indicators_Rural_E_All_Data_(Normalized)__Employment_Indicators_Rural_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Rural_E_All_Data_(Normalized)/Employment_Indicators_Rural_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 376.6KB |
| Rows | 113,187 |
| Columns | 17 |
| File created | 2026-07-05T03:43:56.874449+00:00 |
| File last modified | 2026-07-05T03:52:14.714608+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Sex` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 661 | 0.58% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 3; 4; 7 |
| `Area Code (M49)` | '008; '012; '024 |
| `Area` | Albania; Algeria; Angola |
| `Source Code` | 3021; 3023; 3022 |
| `Source` | ILOSTAT - Household income and expenditure survey; ILOSTAT - Labour force survey; ILOSTAT - Household survey |
| `Indicator Code` | 21087; 21094; 21095 |
| `Indicator` | Employment by age, total (15+), rural areas; Employment by age, 15 to 24, rural areas; Employment by age, 25 to 54, rural areas |
| `Sex Code` | 1; 2; 3 |
| `Sex` | Total; Male; Female |
| `Element Code` | 6199; 6121 |
| `Element` | Value |
| `Year Code` | 2002; 2008; 2012 |
| `Year` | 2002; 2008; 2012 |
| `Unit` | 1000 No; % |
| `Value` | 830.15; 584.17; 318.08 |
| `Flag` | X; U; B |
| `Note` | Repository: ILO-STATISTICS - Micro data processing; Unreliable Repository: ILO-STATISTICS - Micro data processing; Data reference period: September |


---

# FAOSTAT_A-S_E__Employment_Indicators_Rural_E_All_Data_(Normalized)__Employment_Indicators_Rural_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Rural_E_All_Data_(Normalized)/Employment_Indicators_Rural_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.3KB |
| Rows | 265 |
| Columns | 3 |
| File created | 2026-07-05T03:43:57.007900+00:00 |
| File last modified | 2026-07-05T03:52:14.720646+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 5100; 3; 4 |
| `M49 Code` | '002; '008; '012 |
| `Area` | Africa; Albania; Algeria |


---

# FAOSTAT_A-S_E__Employment_Indicators_Rural_E_All_Data_(Normalized)__Employment_Indicators_Rural_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Rural_E_All_Data_(Normalized)/Employment_Indicators_Rural_E_Elements.parquet |
| Format | parquet |
| File size | 891.0B |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:57.013992+00:00 |
| File last modified | 2026-07-05T03:52:14.724635+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6121; 6173; 6199 |
| `Element` | Value |


---

# FAOSTAT_A-S_E__Employment_Indicators_Rural_E_All_Data_(Normalized)__Employment_Indicators_Rural_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Rural_E_All_Data_(Normalized)/Employment_Indicators_Rural_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:43:57.025981+00:00 |
| File last modified | 2026-07-05T03:52:14.727636+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | B; U; X |
| ` Description` | Time series break; Low reliability; Figure from external organization |


---

# FAOSTAT_A-S_E__Employment_Indicators_Rural_E_All_Data_(Normalized)__Employment_Indicators_Rural_E_Indicators

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Rural_E_All_Data_(Normalized)/Employment_Indicators_Rural_E_Indicators.parquet |
| Format | parquet |
| File size | 1.6KB |
| Rows | 28 |
| Columns | 2 |
| File created | 2026-07-05T03:43:57.042585+00:00 |
| File last modified | 2026-07-05T03:52:14.730635+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Indicator Code` | 21142; 21094; 21095 |
| `Indicator` | Employment by age in rural areas; Employment by age; 15 to 24; rural areas; Employment by age; 25 to 54; rural areas |


---

# FAOSTAT_A-S_E__Employment_Indicators_Rural_E_All_Data_(Normalized)__Employment_Indicators_Rural_E_Sexes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Rural_E_All_Data_(Normalized)/Employment_Indicators_Rural_E_Sexes.parquet |
| Format | parquet |
| File size | 874.0B |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:43:57.049304+00:00 |
| File last modified | 2026-07-05T03:52:14.732637+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Sex` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Sex Code` | 3; 2; 1 |
| `Sex` | Female; Male; Total |


---

# FAOSTAT_A-S_E__Employment_Indicators_Rural_E_All_Data_(Normalized)__Employment_Indicators_Rural_E_Sources

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Employment_Indicators_Rural_E_All_Data_(Normalized)/Employment_Indicators_Rural_E_Sources.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 11 |
| Columns | 2 |
| File created | 2026-07-05T03:43:57.064328+00:00 |
| File last modified | 2026-07-05T03:52:14.735634+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Source Code` | 3043; 3012; 3014 |
| `Source` | ILO - ILO Modelled Estimates; ILOSTAT - Administrative insurance records; ILOSTAT - Administrative population register |


---

# FAOSTAT_A-S_E__Environment_Bioenergy_E_All_Data_(Normalized)__Environment_Bioenergy_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Bioenergy_E_All_Data_(Normalized)/Environment_Bioenergy_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 376.1KB |
| Rows | 128,457 |
| Columns | 12 |
| File created | 2026-07-05T03:43:57.126867+00:00 |
| File last modified | 2026-07-05T03:52:14.813092+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | Yes | 22,286 | 17.35% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6524; 6525; 6527 |
| `Item` | Charcoal; Fuelwood; Total Bioenergy |
| `Element Code` | 5852; 5851 |
| `Element` | Energy production; Energy consumption |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Unit` | TJ |
| `Value` | 1150.323; 1190.2365; 1286.5245 |
| `Flag` | X; O; E |


---

# FAOSTAT_A-S_E__Environment_Bioenergy_E_All_Data_(Normalized)__Environment_Bioenergy_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Bioenergy_E_All_Data_(Normalized)/Environment_Bioenergy_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.7KB |
| Rows | 288 |
| Columns | 3 |
| File created | 2026-07-05T03:43:57.228491+00:00 |
| File last modified | 2026-07-05T03:52:14.818203+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_Bioenergy_E_All_Data_(Normalized)__Environment_Bioenergy_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Bioenergy_E_All_Data_(Normalized)/Environment_Bioenergy_E_Elements.parquet |
| Format | parquet |
| File size | 1014.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:57.241050+00:00 |
| File last modified | 2026-07-05T03:52:14.821200+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 5851; 5852 |
| `Element` | Energy consumption; Energy production |


---

# FAOSTAT_A-S_E__Environment_Bioenergy_E_All_Data_(Normalized)__Environment_Bioenergy_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Bioenergy_E_All_Data_(Normalized)/Environment_Bioenergy_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 6 |
| Columns | 2 |
| File created | 2026-07-05T03:43:57.252061+00:00 |
| File last modified | 2026-07-05T03:52:14.824198+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E; I; L |
| ` Description` | Estimated value; Value imputed by a receiving agency; Missing value; data exist but were not collected |


---

# FAOSTAT_A-S_E__Environment_Bioenergy_E_All_Data_(Normalized)__Environment_Bioenergy_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Bioenergy_E_All_Data_(Normalized)/Environment_Bioenergy_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 15 |
| Columns | 2 |
| File created | 2026-07-05T03:43:57.264065+00:00 |
| File last modified | 2026-07-05T03:52:14.828525+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 6519; 170; 6523 |
| `Item` | Animal waste; Bagasse; Bio jet kerosene |


---

# FAOSTAT_A-S_E__Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)__Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)/Environment_Cropland_nutrient_budget_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 3.4MB |
| Rows | 827,796 |
| Columns | 13 |
| File created | 2026-07-05T03:43:57.360045+00:00 |
| File last modified | 2026-07-05T03:52:15.084840+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 827,796 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 5087; 5089; 5076 |
| `Item` | Mineral fertilizers; Manure applied; Atmospheric deposition |
| `Element Code` | 7275; 7276; 7280 |
| `Element` | Cropland nitrogen; Cropland nitrogen per unit area; Cropland phosphorus |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | t; kg/ha; % |
| `Value` | 1000.0; 550.0; 9000.0 |
| `Flag` | E; X; A |


---

# FAOSTAT_A-S_E__Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)__Environment_Cropland_nutrient_budget_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)/Environment_Cropland_nutrient_budget_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.1KB |
| Rows | 248 |
| Columns | 3 |
| File created | 2026-07-05T03:43:57.741535+00:00 |
| File last modified | 2026-07-05T03:52:15.089592+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)__Environment_Cropland_nutrient_budget_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)/Environment_Cropland_nutrient_budget_E_Elements.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 9 |
| Columns | 2 |
| File created | 2026-07-05T03:43:57.757291+00:00 |
| File last modified | 2026-07-05T03:52:15.092590+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 7275; 7276; 7290 |
| `Element` | Cropland nitrogen; Cropland nitrogen per unit area; Cropland nitrogen use efficiency |


---

# FAOSTAT_A-S_E__Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)__Environment_Cropland_nutrient_budget_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)/Environment_Cropland_nutrient_budget_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:57.764212+00:00 |
| File last modified | 2026-07-05T03:52:15.095591+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)__Environment_Cropland_nutrient_budget_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Cropland_nutrient_budget_E_All_Data_(Normalized)/Environment_Cropland_nutrient_budget_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.4KB |
| Rows | 12 |
| Columns | 3 |
| File created | 2026-07-05T03:43:57.787632+00:00 |
| File last modified | 2026-07-05T03:52:15.099591+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | Yes | 12 | 100.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 5076; 5078; 5077 |
| `Item` | Atmospheric deposition; Biological fixation; Crop harvest removal |


---

# FAOSTAT_A-S_E__Environment_Emissions_by_Sector_E_All_Data_(Normalized)__Environment_Emissions_by_Sector_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Emissions_by_Sector_E_All_Data_(Normalized)/Environment_Emissions_by_Sector_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 1.6MB |
| Rows | 509,153 |
| Columns | 12 |
| File created | 2026-07-05T03:43:57.903995+00:00 |
| File last modified | 2026-07-05T03:52:15.469398+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6996; 6516; 6517 |
| `Item` | Farm gate; Land Use change; Pre- and Post- Production |
| `Element Code` | 726313; 7264; 7265 |
| `Element` | Emissions Share (CO2eq) (AR5); Emissions Share (CO2); Emissions Share (CH4) |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Unit` | %; tonnes/capita |
| `Value` | 77.4831; 78.6209; 86.1877 |
| `Flag` | E |


---

# FAOSTAT_A-S_E__Environment_Emissions_by_Sector_E_All_Data_(Normalized)__Environment_Emissions_by_Sector_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Emissions_by_Sector_E_All_Data_(Normalized)/Environment_Emissions_by_Sector_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.5KB |
| Rows | 279 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.221599+00:00 |
| File last modified | 2026-07-05T03:52:15.585452+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_Emissions_by_Sector_E_All_Data_(Normalized)__Environment_Emissions_by_Sector_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Emissions_by_Sector_E_All_Data_(Normalized)/Environment_Emissions_by_Sector_E_Flags.parquet |
| Format | parquet |
| File size | 868.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:58.000188+00:00 |
| File last modified | 2026-07-05T03:52:15.588681+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E |
| `Description` | Estimated value |


---

# FAOSTAT_A-S_E__Environment_Emissions_intensities_E_All_Data_(Normalized)__Environment_Emissions_intensities_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Emissions_intensities_E_All_Data_(Normalized)/Environment_Emissions_intensities_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 1.7MB |
| Rows | 409,511 |
| Columns | 13 |
| File created | 2026-07-05T03:43:58.096054+00:00 |
| File last modified | 2026-07-05T03:52:15.775201+00:00 |
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
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 1718; 27; 867 |
| `Item Code (CPC)` | 'F1718; '0113; '21111.01 |
| `Item` | Cereals excluding rice; Rice; Meat of cattle with the bone, fresh or chilled |
| `Element Code` | 71761; 723113; 5510 |
| `Element` | Emissions intensity; Emissions (CO2eq) (AR5); Production |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | kg CO2eq/kg; kt; t |
| `Value` | 0.113; 0.1149; 0.1205 |
| `Flag` | E; A; X |


---

# FAOSTAT_A-S_E__Environment_Emissions_intensities_E_All_Data_(Normalized)__Environment_Emissions_intensities_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Emissions_intensities_E_All_Data_(Normalized)/Environment_Emissions_intensities_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.7KB |
| Rows | 289 |
| Columns | 3 |
| File created | 2026-07-05T03:43:58.303869+00:00 |
| File last modified | 2026-07-05T03:52:15.779679+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_Emissions_intensities_E_All_Data_(Normalized)__Environment_Emissions_intensities_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Emissions_intensities_E_All_Data_(Normalized)/Environment_Emissions_intensities_E_Elements.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:43:58.313879+00:00 |
| File last modified | 2026-07-05T03:52:15.782677+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 723113; 71761; 5510 |
| `Element` | Emissions (CO2eq) (AR5); Emissions intensity; Production |


---

# FAOSTAT_A-S_E__Environment_Emissions_intensities_E_All_Data_(Normalized)__Environment_Emissions_intensities_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Emissions_intensities_E_All_Data_(Normalized)/Environment_Emissions_intensities_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:58.320802+00:00 |
| File last modified | 2026-07-05T03:52:15.784678+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Environment_Emissions_intensities_E_All_Data_(Normalized)__Environment_Emissions_intensities_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Emissions_intensities_E_All_Data_(Normalized)/Environment_Emissions_intensities_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.5KB |
| Rows | 14 |
| Columns | 3 |
| File created | 2026-07-05T03:43:58.332882+00:00 |
| File last modified | 2026-07-05T03:52:15.789740+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 1718; 1062; 947 |
| `CPC Code` | 'F1718; '0231; '21112 |
| `Item` | Cereals excluding rice; Hen eggs in shell; fresh; Meat of buffalo; fresh or chilled |


---

# FAOSTAT_A-S_E__Environment_Food_Waste_Disposal_E_All_Data_(Normalized)__Environment_Food_Waste_Disposal_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Food_Waste_Disposal_E_All_Data_(Normalized)/Environment_Food_Waste_Disposal_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 350.5KB |
| Rows | 67,264 |
| Columns | 12 |
| File created | 2026-07-05T03:49:08.247677+00:00 |
| File last modified | 2026-07-05T03:52:15.872457+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6988; 6990; 6989 |
| `Item` | Domestic wastewater; Incineration; Industrial wastewater |
| `Element Code` | 7225; 7230; 7273 |
| `Element` | Emissions (CH4); Emissions (N2O); Emissions (CO2) |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Unit` | kilotonnes |
| `Value` | 15.855902; 16.988608; 18.504317 |
| `Flag` | E |


---

# FAOSTAT_A-S_E__Environment_Food_Waste_Disposal_E_All_Data_(Normalized)__Environment_Food_Waste_Disposal_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Food_Waste_Disposal_E_All_Data_(Normalized)/Environment_Food_Waste_Disposal_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.4KB |
| Rows | 271 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.287672+00:00 |
| File last modified | 2026-07-05T03:52:15.897101+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_Food_Waste_Disposal_E_All_Data_(Normalized)__Environment_Food_Waste_Disposal_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Food_Waste_Disposal_E_All_Data_(Normalized)/Environment_Food_Waste_Disposal_E_Flags.parquet |
| Format | parquet |
| File size | 868.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:58.428519+00:00 |
| File last modified | 2026-07-05T03:52:15.900108+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E |
| `Description` | Estimated value |


---

# FAOSTAT_A-S_E__Environment_LandCover_E_All_Data_(Normalized)__Environment_LandCover_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LandCover_E_All_Data_(Normalized)/Environment_LandCover_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 485.1KB |
| Rows | 210,986 |
| Columns | 12 |
| File created | 2026-07-05T03:43:58.513882+00:00 |
| File last modified | 2026-07-05T03:52:16.018821+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | Yes | 28,780 | 13.64% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6970; 6971; 6972 |
| `Item` | Artificial surfaces (including urban and associated areas); Herbaceous crops; Woody crops |
| `Element Code` | 5006; 5007; 5008 |
| `Element` | Area from CGLS; Area from MODIS; Area from CCI_LC |
| `Year Code` | 2015; 2016; 2017 |
| `Year` | 2015; 2016; 2017 |
| `Unit` | 1000 ha |
| `Value` | 102.77; 103.3; 105.41 |
| `Flag` | E; O |


---

# FAOSTAT_A-S_E__Environment_LandCover_E_All_Data_(Normalized)__Environment_LandCover_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LandCover_E_All_Data_(Normalized)/Environment_LandCover_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 282 |
| Columns | 3 |
| File created | 2026-07-05T03:43:58.624399+00:00 |
| File last modified | 2026-07-05T03:52:16.022835+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_LandCover_E_All_Data_(Normalized)__Environment_LandCover_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LandCover_E_All_Data_(Normalized)/Environment_LandCover_E_Elements.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:58.637350+00:00 |
| File last modified | 2026-07-05T03:52:16.025835+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 5008; 5006; 5007 |
| ` Element` | Area from CCI_LC; Area from CGLS; Area from MODIS |


---

# FAOSTAT_A-S_E__Environment_LandCover_E_All_Data_(Normalized)__Environment_LandCover_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LandCover_E_All_Data_(Normalized)/Environment_LandCover_E_Flags.parquet |
| Format | parquet |
| File size | 898.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:43:58.648350+00:00 |
| File last modified | 2026-07-05T03:52:16.028838+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | E; O |
| ` Description` | Estimated value; Missing value |


---

# FAOSTAT_A-S_E__Environment_LandCover_E_All_Data_(Normalized)__Environment_LandCover_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LandCover_E_All_Data_(Normalized)/Environment_LandCover_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:43:58.655413+00:00 |
| File last modified | 2026-07-05T03:52:16.032836+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Environment_LandUse_E_All_Data_(Normalized)__Environment_LandUse_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LandUse_E_All_Data_(Normalized)/Environment_LandUse_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 371.8KB |
| Rows | 165,960 |
| Columns | 12 |
| File created | 2026-07-05T03:43:58.737911+00:00 |
| File last modified | 2026-07-05T03:52:16.196875+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6610; 6621; 6650 |
| `Item` | Agricultural land; Arable land; Land under permanent crops |
| `Element Code` | 7209; 7208; 7277 |
| `Element` | Share in Land area; Share in Agricultural land; Area per capita |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | %; ha/cap |
| `Value` | 57.8; 57.89; 57.97 |
| `Flag` | E |


---

# FAOSTAT_A-S_E__Environment_LandUse_E_All_Data_(Normalized)__Environment_LandUse_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LandUse_E_All_Data_(Normalized)/Environment_LandUse_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.4KB |
| Rows | 275 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.293672+00:00 |
| File last modified | 2026-07-05T03:52:16.248871+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_LandUse_E_All_Data_(Normalized)__Environment_LandUse_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LandUse_E_All_Data_(Normalized)/Environment_LandUse_E_Flags.parquet |
| Format | parquet |
| File size | 868.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:43:58.789719+00:00 |
| File last modified | 2026-07-05T03:52:16.252876+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E |
| `Description` | Estimated value |


---

# FAOSTAT_A-S_E__Environment_LandUse_E_All_Data_(Normalized)__Environment_LandUse_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LandUse_E_All_Data_(Normalized)/Environment_LandUse_E_ItemCodes.parquet |
| Format | parquet |
| File size | 417.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:43:58.801573+00:00 |
| File last modified | 2026-07-05T03:52:16.257109+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Environment_LivestockManure_E_All_Data_(Normalized)__Environment_LivestockManure_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LivestockManure_E_All_Data_(Normalized)/Environment_LivestockManure_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 11.3MB |
| Rows | 2,555,034 |
| Columns | 14 |
| File created | 2026-07-05T03:43:58.894539+00:00 |
| File last modified | 2026-07-05T03:52:17.070266+00:00 |
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
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 2,555,034 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 1107; 1126; 960 |
| `Item Code (CPC)` | '02132; '02121.01; 'F0960 |
| `Item` | Asses; Camels; Cattle, dairy |
| `Element Code` | 5111; 72538; 72380 |
| `Element` | Stocks; Amount excreted in manure (N content); Manure left on pasture (N content) |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | An; kg |
| `Value` | 1300000.0; 851850.0; 1001112.0 |
| `Flag` | A; E; X |


---

# FAOSTAT_A-S_E__Environment_LivestockManure_E_All_Data_(Normalized)__Environment_LivestockManure_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LivestockManure_E_All_Data_(Normalized)/Environment_LivestockManure_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 281 |
| Columns | 3 |
| File created | 2026-07-05T03:43:59.892857+00:00 |
| File last modified | 2026-07-05T03:52:17.074263+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_LivestockManure_E_All_Data_(Normalized)__Environment_LivestockManure_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LivestockManure_E_All_Data_(Normalized)/Environment_LivestockManure_E_Elements.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 10 |
| Columns | 2 |
| File created | 2026-07-05T03:43:59.910284+00:00 |
| File last modified | 2026-07-05T03:52:17.076267+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 72538; 72539; 72381 |
| ` Element` | Amount excreted in manure (N content); Losses from manure treated (N content); Manure applied to soils (N content) |


---

# FAOSTAT_A-S_E__Environment_LivestockManure_E_All_Data_(Normalized)__Environment_LivestockManure_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LivestockManure_E_All_Data_(Normalized)/Environment_LivestockManure_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:43:59.915283+00:00 |
| File last modified | 2026-07-05T03:52:17.079268+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Environment_LivestockManure_E_All_Data_(Normalized)__Environment_LivestockManure_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LivestockManure_E_All_Data_(Normalized)/Environment_LivestockManure_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.6KB |
| Rows | 24 |
| Columns | 3 |
| File created | 2026-07-05T03:43:59.922283+00:00 |
| File last modified | 2026-07-05T03:52:17.082270+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Item Code` | 1016; 1048; 1049 |
| ` CPC Code` | '02123; 'F1048; 'F1049 |
| ` Item` | Goats; Swine; Swine; market |


---

# FAOSTAT_A-S_E__Environment_LivestockPatterns_E_All_Data_(Normalized)__Environment_LivestockPatterns_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LivestockPatterns_E_All_Data_(Normalized)/Environment_LivestockPatterns_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 971.9KB |
| Rows | 470,577 |
| Columns | 13 |
| File created | 2026-07-05T03:44:00.026683+00:00 |
| File last modified | 2026-07-05T03:52:17.277459+00:00 |
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
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 1107; 1126; 866 |
| `Item Code (CPC)` | '02132; '02121.01; '02111 |
| `Item` | Asses; Camels; Cattle |
| `Element Code` | 7213; 7211; 5118 |
| `Element` | Livestock units per agricultural land area; Share in total livestock; Stocks |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | LSU/ha; %LSU; LSU |
| `Value` | 0.02; 0.01; 12.36 |
| `Flag` | E |


---

# FAOSTAT_A-S_E__Environment_LivestockPatterns_E_All_Data_(Normalized)__Environment_LivestockPatterns_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LivestockPatterns_E_All_Data_(Normalized)/Environment_LivestockPatterns_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.5KB |
| Rows | 274 |
| Columns | 3 |
| File created | 2026-07-05T03:44:00.284376+00:00 |
| File last modified | 2026-07-05T03:52:17.280606+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_LivestockPatterns_E_All_Data_(Normalized)__Environment_LivestockPatterns_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LivestockPatterns_E_All_Data_(Normalized)/Environment_LivestockPatterns_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:44:00.301227+00:00 |
| File last modified | 2026-07-05T03:52:17.282613+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 7213; 7211; 5118 |
| ` Element` | Livestock units per agricultural land area; Share in total livestock; Stocks |


---

# FAOSTAT_A-S_E__Environment_LivestockPatterns_E_All_Data_(Normalized)__Environment_LivestockPatterns_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LivestockPatterns_E_All_Data_(Normalized)/Environment_LivestockPatterns_E_Flags.parquet |
| Format | parquet |
| File size | 882.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:00.309331+00:00 |
| File last modified | 2026-07-05T03:52:17.284614+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | E |
| ` Description` | Estimated value |


---

# FAOSTAT_A-S_E__Environment_LivestockPatterns_E_All_Data_(Normalized)__Environment_LivestockPatterns_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_LivestockPatterns_E_All_Data_(Normalized)/Environment_LivestockPatterns_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.5KB |
| Rows | 14 |
| Columns | 3 |
| File created | 2026-07-05T03:44:00.322428+00:00 |
| File last modified | 2026-07-05T03:52:17.287614+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Item Code` | 1016; 1034; 1057 |
| ` CPC Code` | '02123; '02140; '02151 |
| ` Item` | Goats; Swine / pigs; Chickens |


---

# FAOSTAT_A-S_E__Environment_Pesticides_E_All_Data_(Normalized)__Environment_Pesticides_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Pesticides_E_All_Data_(Normalized)/Environment_Pesticides_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 32.6KB |
| Rows | 15,452 |
| Columns | 12 |
| File created | 2026-07-05T03:49:08.321741+00:00 |
| File last modified | 2026-07-05T03:52:17.348843+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 3; 4; 7 |
| `Area Code (M49)` | '008; '012; '024 |
| `Area` | Albania; Algeria; Angola |
| `Item Code` | 1357 |
| `Item` | Pesticides (total) |
| `Element Code` | 5159; 5172; 5173 |
| `Element` | Use per area of cropland; Use per capita; Use per value of agricultural production |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Unit` | kg/ha; kg/cap; kg/1000 Int.$ |
| `Value` | 0.17; 0.29; 0.36 |
| `Flag` | E |


---

# FAOSTAT_A-S_E__Environment_Pesticides_E_All_Data_(Normalized)__Environment_Pesticides_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Pesticides_E_All_Data_(Normalized)/Environment_Pesticides_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.6KB |
| Rows | 207 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.353422+00:00 |
| File last modified | 2026-07-05T03:52:17.357934+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 5100; 3; 4 |
| `M49 Code` | '002; '008; '012 |
| `Area` | Africa; Albania; Algeria |


---

# FAOSTAT_A-S_E__Environment_Pesticides_E_All_Data_(Normalized)__Environment_Pesticides_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Pesticides_E_All_Data_(Normalized)/Environment_Pesticides_E_Flags.parquet |
| Format | parquet |
| File size | 868.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:00.386344+00:00 |
| File last modified | 2026-07-05T03:52:17.360881+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E |
| `Description` | Estimated value |


---

# FAOSTAT_A-S_E__Environment_Pesticides_E_All_Data_(Normalized)__Environment_Pesticides_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Pesticides_E_All_Data_(Normalized)/Environment_Pesticides_E_ItemCodes.parquet |
| Format | parquet |
| File size | 417.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:44:00.392440+00:00 |
| File last modified | 2026-07-05T03:52:17.361880+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Environment_Soil_nutrient_budget_E_All_Data_(Normalized)__Environment_Soil_nutrient_budget_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Soil_nutrient_budget_E_All_Data_(Normalized)/Environment_Soil_nutrient_budget_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 831.3KB |
| Rows | 196,030 |
| Columns | 12 |
| File created | 2026-07-05T03:44:00.492734+00:00 |
| File last modified | 2026-07-05T03:52:17.562260+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 5061; 5062; 5076 |
| `Item` | Synthetic Fertilizers; Manure applied to Soils; Atmospheric Deposition |
| `Element Code` | 7275; 7276 |
| `Element` | Cropland nutrient flow; Cropland nutrient flow per unit area |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | tonnes; kg/ha |
| `Value` | 1000.0; 9000.0; 14000.0 |
| `Flag` | E; X; A |


---

# FAOSTAT_A-S_E__Environment_Soil_nutrient_budget_E_All_Data_(Normalized)__Environment_Soil_nutrient_budget_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Soil_nutrient_budget_E_All_Data_(Normalized)/Environment_Soil_nutrient_budget_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.0KB |
| Rows | 242 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.353422+00:00 |
| File last modified | 2026-07-05T03:52:17.615758+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_Soil_nutrient_budget_E_All_Data_(Normalized)__Environment_Soil_nutrient_budget_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Soil_nutrient_budget_E_All_Data_(Normalized)/Environment_Soil_nutrient_budget_E_Flags.parquet |
| Format | parquet |
| File size | 975.0B |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:00.541625+00:00 |
| File last modified | 2026-07-05T03:52:17.618761+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; P |
| `Description` | Official figure; Estimated value; Provisional value |


---

# FAOSTAT_A-S_E__Environment_Temperature_change_E_All_Data_(Normalized)__Environment_Temperature_change_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Temperature_change_E_All_Data_(Normalized)/Environment_Temperature_change_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 797.0KB |
| Rows | 590,512 |
| Columns | 12 |
| File created | 2026-07-05T03:44:00.639242+00:00 |
| File last modified | 2026-07-05T03:52:17.806020+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Months Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Months` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | Yes | 22,333 | 3.78% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Months Code` | 7001; 7002; 7003 |
| `Months` | January; February; March |
| `Element Code` | 7271; 6078 |
| `Element` | Temperature change; Standard Deviation |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | °C |
| `Value` | 0.767; 0.031; 2.713 |
| `Flag` | E; O; L |


---

# FAOSTAT_A-S_E__Environment_Temperature_change_E_All_Data_(Normalized)__Environment_Temperature_change_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Temperature_change_E_All_Data_(Normalized)/Environment_Temperature_change_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.7KB |
| Rows | 288 |
| Columns | 3 |
| File created | 2026-07-05T03:44:00.886784+00:00 |
| File last modified | 2026-07-05T03:52:17.809999+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Environment_Temperature_change_E_All_Data_(Normalized)__Environment_Temperature_change_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Temperature_change_E_All_Data_(Normalized)/Environment_Temperature_change_E_Elements.parquet |
| Format | parquet |
| File size | 1022.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:44:00.904577+00:00 |
| File last modified | 2026-07-05T03:52:17.813954+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6078; 7271 |
| `Element` | Standard Deviation; Temperature change |


---

# FAOSTAT_A-S_E__Environment_Temperature_change_E_All_Data_(Normalized)__Environment_Temperature_change_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Environment_Temperature_change_E_All_Data_(Normalized)/Environment_Temperature_change_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:44:00.920118+00:00 |
| File last modified | 2026-07-05T03:52:17.815964+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E; L; O |
| ` Description` | Estimated value; Missing value; data exist but were not collected; Missing value |


---

# FAOSTAT_A-S_E__Exchange_rate_E_All_Data_(Normalized)__Exchange_rate_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Exchange_rate_E_All_Data_(Normalized)/Exchange_rate_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 517.6KB |
| Rows | 145,821 |
| Columns | 14 |
| File created | 2026-07-05T03:44:01.014171+00:00 |
| File last modified | 2026-07-05T03:52:17.917072+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | String | Categorical | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `ISO Currency Code` | String | Categorical | No | 0 | 0.0% |
| `Currency` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Months Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Months` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | Yes | 17 | 0.01% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 284; 3 |
| `Area Code (M49)` | '004; '248; '008 |
| `Area` | Afghanistan; Åland Islands; Albania |
| `Element Code` | LCU; SLC |
| `Element` | Local currency units per USD; Standard local currency units per USD |
| `ISO Currency Code` | AFA; AFN; EUR |
| `Currency` | Afghani; Euro; Lek |
| `Year Code` | 1970; 1971; 1972 |
| `Year` | 1970; 1971; 1972 |
| `Months Code` | 7021; 7001; 7002 |
| `Months` | Annual value; January; February |
| `Unit` |  |
| `Value` | 44.99842708; 38.69226155; 34.92963077 |
| `Flag` | X; L; I |


---

# FAOSTAT_A-S_E__Exchange_rate_E_All_Data_(Normalized)__Exchange_rate_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Exchange_rate_E_All_Data_(Normalized)/Exchange_rate_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.4KB |
| Rows | 266 |
| Columns | 3 |
| File created | 2026-07-05T03:44:01.175422+00:00 |
| File last modified | 2026-07-05T03:52:17.921947+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 284 |
| `M49 Code` | '004; '002; '248 |
| `Area` | Afghanistan; Africa; Åland Islands |


---

# FAOSTAT_A-S_E__Exchange_rate_E_All_Data_(Normalized)__Exchange_rate_E_Currencys

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Exchange_rate_E_All_Data_(Normalized)/Exchange_rate_E_Currencys.parquet |
| Format | parquet |
| File size | 3.6KB |
| Rows | 294 |
| Columns | 2 |
| File created | 2026-07-05T03:44:01.191341+00:00 |
| File last modified | 2026-07-05T03:52:17.924948+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `ISO Currency Code` | String | Categorical | No | 0 | 0.0% |
| `Currency` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `ISO Currency Code` | AIF; AFA; AFN |
| `Currency` | Affars and Issas Franc; Afghani; Algerian Dinar |


---

# FAOSTAT_A-S_E__Exchange_rate_E_All_Data_(Normalized)__Exchange_rate_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Exchange_rate_E_All_Data_(Normalized)/Exchange_rate_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:44:01.202341+00:00 |
| File last modified | 2026-07-05T03:52:17.928988+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | String | Categorical | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | LCU; SLC |
| `Element` | Local currency units per USD; Standard local currency units per USD |


---

# FAOSTAT_A-S_E__Exchange_rate_E_All_Data_(Normalized)__Exchange_rate_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Exchange_rate_E_All_Data_(Normalized)/Exchange_rate_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:01.214436+00:00 |
| File last modified | 2026-07-05T03:52:17.931987+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; I; L |
| ` Description` | Official figure; Value imputed by a receiving agency; Missing value; data exist but were not collected |


---

# FAOSTAT_A-S_E__Fertilizers_DetailedTradeMatrix_E_All_Data_(Normalized)__Fertilizers_DetailedTradeMatrix_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Fertilizers_DetailedTradeMatrix_E_All_Data_(Normalized)/Fertilizers_DetailedTradeMatrix_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 20.3MB |
| Rows | 5,300,910 |
| Columns | 16 |
| File created | 2026-07-05T03:44:01.309078+00:00 |
| File last modified | 2026-07-05T03:52:19.685990+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Reporter Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Reporter Country Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Reporter Countries` | String | Categorical | No | 0 | 0.0% |
| `Partner Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Partner Country Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Partner Countries` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item Code (CPC)` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Reporter Country Code` | 2; 3; 4 |
| `Reporter Country Code (M49)` | '004; '008; '012 |
| `Reporter Countries` | Afghanistan; Albania; Algeria |
| `Partner Country Code` | 7; 10; 11 |
| `Partner Country Code (M49)` | '024; '036; '040 |
| `Partner Countries` | Angola; Australia; Austria |
| `Item Code` | 3104; 4017; 3102 |
| `Item Code (CPC)` | 'F3104; '34632; 'F3102 |
| `Item` | Nutrient potash K2O (total); Potassium sulphate (sulphate of potash) (SOP); Nutrient nitrogen N (total) |
| `Element Code` | 5910; 59104; 5922 |
| `Element` | Export quantity; Export quantity (tonnes K); Export value |
| `Year Code` | 2012; 2007; 1990 |
| `Year` | 2012; 2007; 1990 |
| `Unit` | t; 1000 USD |
| `Value` | 4.82; 9.64; 19.64 |
| `Flag` | I; E; X |


---

# FAOSTAT_A-S_E__Fertilizers_DetailedTradeMatrix_E_All_Data_(Normalized)__Fertilizers_DetailedTradeMatrix_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Fertilizers_DetailedTradeMatrix_E_All_Data_(Normalized)/Fertilizers_DetailedTradeMatrix_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 10 |
| Columns | 2 |
| File created | 2026-07-05T03:44:03.907871+00:00 |
| File last modified | 2026-07-05T03:52:19.688973+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 5910; 59104; 59102 |
| ` Element` | Export quantity; Export quantity (tonnes K); Export quantity (tonnes N) |


---

# FAOSTAT_A-S_E__Fertilizers_DetailedTradeMatrix_E_All_Data_(Normalized)__Fertilizers_DetailedTradeMatrix_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Fertilizers_DetailedTradeMatrix_E_All_Data_(Normalized)/Fertilizers_DetailedTradeMatrix_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:44:03.921089+00:00 |
| File last modified | 2026-07-05T03:52:19.691974+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | E; I; X |
| ` Description` | Estimated value; Value imputed by a receiving agency; Figure from external organization |


---

# FAOSTAT_A-S_E__Fertilizers_DetailedTradeMatrix_E_All_Data_(Normalized)__Fertilizers_DetailedTradeMatrix_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Fertilizers_DetailedTradeMatrix_E_All_Data_(Normalized)/Fertilizers_DetailedTradeMatrix_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.9KB |
| Rows | 23 |
| Columns | 3 |
| File created | 2026-07-05T03:44:03.933899+00:00 |
| File last modified | 2026-07-05T03:52:19.694483+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Item Code` | 3102; 4001; 4002 |
| ` CPC Code` | 'F3102; '34611; '34612 |
| ` Item` | Nutrient nitrogen N (total); Urea; Ammonium sulphate |


---

# FAOSTAT_A-S_E__Food_Aid_Shipments_WFP_E_All_Data_(Normalized)__Food_Aid_Shipments_WFP_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Food_Aid_Shipments_WFP_E_All_Data_(Normalized)/Food_Aid_Shipments_WFP_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 117.9KB |
| Rows | 31,114 |
| Columns | 13 |
| File created | 2026-07-05T03:49:08.374585+00:00 |
| File last modified | 2026-07-05T03:52:19.785500+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Recipient Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Recipient Country Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Recipient Country` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 9,811 | 31.53% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Recipient Country Code` | 2; 3; 4 |
| `Recipient Country Code (M49)` | '004; '008; '012 |
| `Recipient Country` | Afghanistan; Albania; Algeria |
| `Item Code` | 10109; 10021; 12061 |
| `Item` | Blended And Mix; Bulgur Wheat Total; Cereals |
| `Element Code` | 500 |
| `Element` | Food aid received |
| `Year Code` | 1990; 1999; 2000 |
| `Year` | 1990; 1999; 2000 |
| `Unit` | t |
| `Value` | 1992.0; 4482.0; 1053.0 |
| `Flag` | X; E |
| `Note` | Data provided by WFP; Provisional data provided by WFP |


---

# FAOSTAT_A-S_E__Food_Aid_Shipments_WFP_E_All_Data_(Normalized)__Food_Aid_Shipments_WFP_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Food_Aid_Shipments_WFP_E_All_Data_(Normalized)/Food_Aid_Shipments_WFP_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.4KB |
| Rows | 183 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.397475+00:00 |
| File last modified | 2026-07-05T03:52:19.798591+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Food_Aid_Shipments_WFP_E_All_Data_(Normalized)__Food_Aid_Shipments_WFP_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Food_Aid_Shipments_WFP_E_All_Data_(Normalized)/Food_Aid_Shipments_WFP_E_Flags.parquet |
| Format | parquet |
| File size | 1016.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:44:04.076834+00:00 |
| File last modified | 2026-07-05T03:52:19.801588+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E; X |
| `Description` | Estimated value; Figure from international organizations |


---

# FAOSTAT_A-S_E__Food_and_Diet_Individual_Quantitative_Dietary_Data_E_All_Data_(Normalized)__Food_and_Diet_Individual_Quantitative_Dietary_Data_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Food_and_Diet_Individual_Quantitative_Dietary_Data_E_All_Data_(Normalized)/Food_and_Diet_Individual_Quantitative_Dietary_Data_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 1.7MB |
| Rows | 1,164,769 |
| Columns | 18 |
| File created | 2026-07-05T03:49:08.426505+00:00 |
| File last modified | 2026-07-05T03:52:20.774865+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Survey Code` | String | Categorical | No | 0 | 0.0% |
| `Survey` | String | Categorical | No | 0 | 0.0% |
| `Geographic Level Code` | Int64 | Numeric | Yes | 1,044,609 | 89.68% |
| `Geographic Level` | String | Categorical | No | 0 | 0.0% |
| `Population Group Code` | String | Categorical | No | 0 | 0.0% |
| `Population Group` | String | Categorical | No | 0 | 0.0% |
| `Food Group Code` | String | Categorical | No | 0 | 0.0% |
| `Food Group` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Sex` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | String | Categorical | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Survey Code` | 076_2014; 484_2012; 788_19961997 |
| `Survey` | Brazil - 2014; Mexico - 2012; Tunisia - 1996-1997 |
| `Geographic Level Code` | 10000; 10001; 10002 |
| `Geographic Level` | National; Urban; Rural |
| `Population Group Code` | allages; 9t18y; 9t13y |
| `Population Group` | All age groups; 9-18 years; 9-13 years |
| `Food Group Code` | FGWD; FG0; FG1 |
| `Food Group` | Whole diet (excluding beverages); All food groups (GIFT); Cereals and their products (GIFT) |
| `Indicator Code` | 3334; 3331; 3345 |
| `Indicator` | Average calcium intake; Average carbohydrate intake; Average dietary folate equivalents intake, in DFE |
| `Element Code` | 6209; 6123; 6227 |
| `Element` | Value |
| `Sex Code` | 1; 2; 3 |
| `Sex` | Total; Male; Female |
| `Unit` | mg/pc/d; g/pc/d; µg/pc/d |
| `Value` | 376; 395; 356 |
| `Flag` | E |
| `Note` | Brazil-2014; Mexico-2012; Tunisia-1996-97 |


---

# FAOSTAT_A-S_E__Food_and_Diet_Individual_Quantitative_Dietary_Data_E_All_Data_(Normalized)__Food_and_Diet_Individual_Quantitative_Dietary_Data_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Food_and_Diet_Individual_Quantitative_Dietary_Data_E_All_Data_(Normalized)/Food_and_Diet_Individual_Quantitative_Dietary_Data_E_Flags.parquet |
| Format | parquet |
| File size | 868.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:04.183677+00:00 |
| File last modified | 2026-07-05T03:52:21.212588+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E |
| `Description` | Estimated value |


---

# FAOSTAT_A-S_E__Food_Security_Data_E_All_Data_(Normalized)__Food_Security_Data_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Food_Security_Data_E_All_Data_(Normalized)/Food_Security_Data_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 416.4KB |
| Rows | 279,470 |
| Columns | 13 |
| File created | 2026-07-05T03:44:04.282870+00:00 |
| File last modified | 2026-07-05T03:52:21.359733+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | String | Categorical | Yes | 38,019 | 13.6% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 237,680 | 85.05% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 21010; 220001; 22000 |
| `Item` | Average dietary energy supply adequacy (percent) (3-year average); Dietary energy supply used in the estimation of the prevalence of undernouris...; Dietary energy supply used in the estimation of the prevalence of undernouris... |
| `Element Code` | 6121; 6128; 6123 |
| `Element` | Value; Confidence interval: Lower bound; Confidence interval: Upper bound |
| `Year Code` | 20002002; 20012003; 20022004 |
| `Year` | 2000-2002; 2001-2003; 2002-2004 |
| `Unit` | %; kcal/cap/d; g/cap/d |
| `Value` | 87; 88; 91 |
| `Flag` | E; X; Q |
| `Note` | FAO data; Official estimate; Official estimate integrated with FAO data |


---

# FAOSTAT_A-S_E__Food_Security_Data_E_All_Data_(Normalized)__Food_Security_Data_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Food_Security_Data_E_All_Data_(Normalized)/Food_Security_Data_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.1KB |
| Rows | 249 |
| Columns | 3 |
| File created | 2026-07-05T03:44:04.471116+00:00 |
| File last modified | 2026-07-05T03:52:21.364152+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Food_Security_Data_E_All_Data_(Normalized)__Food_Security_Data_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Food_Security_Data_E_All_Data_(Normalized)/Food_Security_Data_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 14 |
| Columns | 2 |
| File created | 2026-07-05T03:44:04.482944+00:00 |
| File last modified | 2026-07-05T03:52:21.368152+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 61321; 61211; 61212 |
| `Element` | Confidence interval: Lower bound; Confidence interval: Upper bound; Value |


---

# FAOSTAT_A-S_E__Food_Security_Data_E_All_Data_(Normalized)__Food_Security_Data_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Food_Security_Data_E_All_Data_(Normalized)/Food_Security_Data_E_Flags.parquet |
| Format | parquet |
| File size | 982.0B |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:04.496341+00:00 |
| File last modified | 2026-07-05T03:52:21.372573+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; O |
| ` Description` | Official figure; Estimated value; Missing value |


---

# FAOSTAT_A-S_E__Food_Security_Data_E_All_Data_(Normalized)__Food_Security_Data_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Food_Security_Data_E_All_Data_(Normalized)/Food_Security_Data_E_ItemCodes.parquet |
| Format | parquet |
| File size | 2.6KB |
| Rows | 75 |
| Columns | 2 |
| File created | 2026-07-05T03:44:04.510348+00:00 |
| File last modified | 2026-07-05T03:52:21.376587+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 21051; 21050; 21057 |
| `Item` | Access; Availability; Average dietary energy requirement (kcal/cap/day) |


---

# FAOSTAT_A-S_E__FoodBalanceSheets_E_All_Data_(Normalized)__FoodBalanceSheets_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/FoodBalanceSheets_E_All_Data_(Normalized)/FoodBalanceSheets_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 24.2MB |
| Rows | 4,820,497 |
| Columns | 14 |
| File created | 2026-07-05T03:44:04.619237+00:00 |
| File last modified | 2026-07-05T03:52:22.861497+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item Code (FBS)` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 4,820,497 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 2501; 2901; 2903 |
| `Item Code (FBS)` | 'S2501; 'S2901; 'S2903 |
| `Item` | Population; Grand Total; Vegetal Products |
| `Element Code` | 511; 664; 661 |
| `Element` | Total Population - Both sexes; Food supply (kcal/capita/day); Food supply (kcal) |
| `Year Code` | 2010; 2011; 2012 |
| `Year` | 2010; 2011; 2012 |
| `Unit` | 1000 No; kcal/cap/d; million Kcal |
| `Value` | 28284.09; 2928.72; 29347.71 |
| `Flag` | X; E; I |


---

# FAOSTAT_A-S_E__FoodBalanceSheets_E_All_Data_(Normalized)__FoodBalanceSheets_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/FoodBalanceSheets_E_All_Data_(Normalized)/FoodBalanceSheets_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.9KB |
| Rows | 426 |
| Columns | 3 |
| File created | 2026-07-05T03:44:06.874816+00:00 |
| File last modified | 2026-07-05T03:52:22.866491+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__FoodBalanceSheets_E_All_Data_(Normalized)__FoodBalanceSheets_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/FoodBalanceSheets_E_All_Data_(Normalized)/FoodBalanceSheets_E_Elements.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 21 |
| Columns | 2 |
| File created | 2026-07-05T03:44:06.887412+00:00 |
| File last modified | 2026-07-05T03:52:22.870715+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 5301; 5911; 684 |
| ` Element` | Domestic supply quantity; Export quantity; Fat supply quantity (g/capita/day) |


---

# FAOSTAT_A-S_E__FoodBalanceSheets_E_All_Data_(Normalized)__FoodBalanceSheets_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/FoodBalanceSheets_E_All_Data_(Normalized)/FoodBalanceSheets_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:44:06.894004+00:00 |
| File last modified | 2026-07-05T03:52:22.874722+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | E; I; X |
| ` Description` | Estimated value; Value imputed by a receiving agency; Figure from external organization |


---

# FAOSTAT_A-S_E__FoodBalanceSheets_E_All_Data_(Normalized)__FoodBalanceSheets_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/FoodBalanceSheets_E_All_Data_(Normalized)/FoodBalanceSheets_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:44:06.899003+00:00 |
| File last modified | 2026-07-05T03:52:22.877723+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__FoodBalanceSheetsHistoric_E_All_Data_(Normalized)__FoodBalanceSheetsHistoric_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/FoodBalanceSheetsHistoric_E_All_Data_(Normalized)/FoodBalanceSheetsHistoric_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 15.4MB |
| Rows | 11,479,903 |
| Columns | 13 |
| File created | 2026-07-05T03:44:06.993006+00:00 |
| File last modified | 2026-07-05T03:52:29.323206+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item Code (FBS)` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 2501; 2901; 2903 |
| `Item Code (FBS)` | 'S2501; 'S2901; 'S2903 |
| `Item` | Population; Grand Total; Vegetal Products |
| `Element Code` | 511; 664; 674 |
| `Element` | Total Population - Both sexes; Food supply (kcal/capita/day); Protein supply quantity (g/capita/day) |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | 1000 No; kcal/cap/d; g/cap/d |
| `Value` | 8954.0; 9142.0; 9340.0 |
| `Flag` | X; E; I |


---

# FAOSTAT_A-S_E__FoodBalanceSheetsHistoric_E_All_Data_(Normalized)__FoodBalanceSheetsHistoric_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/FoodBalanceSheetsHistoric_E_All_Data_(Normalized)/FoodBalanceSheetsHistoric_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.9KB |
| Rows | 434 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.490886+00:00 |
| File last modified | 2026-07-05T03:52:32.317887+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__FoodBalanceSheetsHistoric_E_All_Data_(Normalized)__FoodBalanceSheetsHistoric_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/FoodBalanceSheetsHistoric_E_All_Data_(Normalized)/FoodBalanceSheetsHistoric_E_Flags.parquet |
| Format | parquet |
| File size | 928.0B |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:44:07.929411+00:00 |
| File last modified | 2026-07-05T03:52:32.323885+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E; I; X |
| `Description` | Estimated value; Imputed value; Figure from international organizations |


---

# FAOSTAT_A-S_E__FoodBalanceSheetsHistoric_E_All_Data_(Normalized)__FoodBalanceSheetsHistoric_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/FoodBalanceSheetsHistoric_E_All_Data_(Normalized)/FoodBalanceSheetsHistoric_E_ItemCodes.parquet |
| Format | parquet |
| File size | 417.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:44:07.936412+00:00 |
| File last modified | 2026-07-05T03:52:32.328885+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Forestry_E_All_Data_(Normalized)__Forestry_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_E_All_Data_(Normalized)/Forestry_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 6.2MB |
| Rows | 2,457,869 |
| Columns | 13 |
| File created | 2026-07-05T03:44:08.026793+00:00 |
| File last modified | 2026-07-05T03:52:33.487029+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 2,457,869 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 1659; 1877; 1861 |
| `Item` | Wood, pulp and paper products (export/import); Primary wood and paper products (export/import); Roundwood |
| `Element Code` | 5622; 5922; 5516 |
| `Element` | Import value; Export value; Production |
| `Year Code` | 2000; 2001; 2002 |
| `Year` | 2000; 2001; 2002 |
| `Unit` | 1000 USD; m3; t |
| `Value` | 1981.0; 1787.0; 11887.0 |
| `Flag` | E; A; X |


---

# FAOSTAT_A-S_E__Forestry_E_All_Data_(Normalized)__Forestry_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_E_All_Data_(Normalized)/Forestry_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 285 |
| Columns | 3 |
| File created | 2026-07-05T03:44:09.078312+00:00 |
| File last modified | 2026-07-05T03:52:33.505201+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Forestry_E_All_Data_(Normalized)__Forestry_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_E_All_Data_(Normalized)/Forestry_E_Elements.parquet |
| Format | parquet |
| File size | 1019.0B |
| Rows | 8 |
| Columns | 2 |
| File created | 2026-07-05T03:44:09.092535+00:00 |
| File last modified | 2026-07-05T03:52:33.510291+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 5910; 5916; 5922 |
| `Element` | Export quantity; Export value; Import quantity |


---

# FAOSTAT_A-S_E__Forestry_E_All_Data_(Normalized)__Forestry_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_E_All_Data_(Normalized)/Forestry_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:09.107729+00:00 |
| File last modified | 2026-07-05T03:52:33.514294+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; F |
| ` Description` | Official figure; Estimated value; Forecast value |


---

# FAOSTAT_A-S_E__Forestry_E_All_Data_(Normalized)__Forestry_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_E_All_Data_(Normalized)/Forestry_E_ItemCodes.parquet |
| Format | parquet |
| File size | 2.6KB |
| Rows | 104 |
| Columns | 2 |
| File created | 2026-07-05T03:44:09.121552+00:00 |
| File last modified | 2026-07-05T03:52:33.520365+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 1653; 1618; 1617 |
| `Item` | Builder's joinery and carpentry of wood (export/import); Cartonboard; Case materials |


---

# FAOSTAT_A-S_E__Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)__Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)/Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 36.5KB |
| Rows | 67,538 |
| Columns | 12 |
| File created | 2026-07-05T03:44:09.184499+00:00 |
| File last modified | 2026-07-05T03:52:33.596856+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | Yes | 47,057 | 69.67% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 9; 10; 11 |
| `Area Code (M49)` | '032; '036; '040 |
| `Area` | Argentina; Australia; Austria |
| `Item Code` | 1856; 16850; 1685.01 |
| `Item` | Wood pulp for paper and paperboard; Mechanical, thermo-mechanical and semi-chemical wood pulp; Mechanical wood pulp |
| `Element Code` | 5510; 5801; 5034 |
| `Element` | Production; Market pulp Production; Consumption |
| `Year Code` | 2020; 2021; 2022 |
| `Year` | 2020; 2021; 2022 |
| `Unit` | t |
| `Value` | 620000.0; 609000.0; 567000.0 |
| `Flag` | A; O; E |


---

# FAOSTAT_A-S_E__Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)__Forestry_Pulp_Paper_Survey_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)/Forestry_Pulp_Paper_Survey_E_AreaCodes.parquet |
| Format | parquet |
| File size | 2.6KB |
| Rows | 89 |
| Columns | 3 |
| File created | 2026-07-05T03:44:09.265724+00:00 |
| File last modified | 2026-07-05T03:52:33.602856+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 5100; 5200; 5600 |
| ` M49 Code` | '002; '019; '912 |
| ` Area` | Africa; Americas; Antarctic Region |


---

# FAOSTAT_A-S_E__Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)__Forestry_Pulp_Paper_Survey_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)/Forestry_Pulp_Paper_Survey_E_Elements.parquet |
| Format | parquet |
| File size | 1003.0B |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:09.276634+00:00 |
| File last modified | 2026-07-05T03:52:33.605937+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 5326; 5034; 5800 |
| ` Element` | Capacity; Consumption; Market pulp Capacity |


---

# FAOSTAT_A-S_E__Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)__Forestry_Pulp_Paper_Survey_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)/Forestry_Pulp_Paper_Survey_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:09.288534+00:00 |
| File last modified | 2026-07-05T03:52:33.610512+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)__Forestry_Pulp_Paper_Survey_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_Pulp_Paper_Survey_E_All_Data_(Normalized)/Forestry_Pulp_Paper_Survey_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:44:09.295745+00:00 |
| File last modified | 2026-07-05T03:52:33.614457+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Forestry_Trade_Flows_E_All_Data_(Normalized)__Forestry_Trade_Flows_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_Trade_Flows_E_All_Data_(Normalized)/Forestry_Trade_Flows_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 9.8MB |
| Rows | 2,829,802 |
| Columns | 16 |
| File created | 2026-07-05T03:49:08.533413+00:00 |
| File last modified | 2026-07-05T03:52:35.664156+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Reporter Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Reporter Country Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Reporter Countries` | String | Categorical | No | 0 | 0.0% |
| `Partner Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Partner Country Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Partner Countries` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 2,426,777 | 85.76% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Reporter Country Code` | 2; 3; 4 |
| `Reporter Country Code (M49)` | '004; '008; '012 |
| `Reporter Countries` | Afghanistan; Albania; Algeria |
| `Partner Country Code` | 10; 11; 16 |
| `Partner Country Code (M49)` | '036; '040; '050 |
| `Partner Countries` | Australia; Austria; Bangladesh |
| `Item Code` | 1877; 1640; 1860 |
| `Item` | Forest products (export/import); Plywood; Paper and paperboard, excluding newsprint |
| `Element Code` | 5622; 5616; 5610 |
| `Element` | Import Value; Import Quantity; Export Value |
| `Year Code` | 1999; 2005; 2009 |
| `Year` | 1999; 2005; 2009 |
| `Unit` | 1000 USD; m3; t |
| `Value` | 6.0; 18.0; 59.0 |
| `Flag` | A; X; I |
| `Note` | Estimated data using trading partners database |


---

# FAOSTAT_A-S_E__Forestry_Trade_Flows_E_All_Data_(Normalized)__Forestry_Trade_Flows_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_Trade_Flows_E_All_Data_(Normalized)/Forestry_Trade_Flows_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.8KB |
| Rows | 423 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.586852+00:00 |
| File last modified | 2026-07-05T03:52:37.153358+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Forestry_Trade_Flows_E_All_Data_(Normalized)__Forestry_Trade_Flows_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_Trade_Flows_E_All_Data_(Normalized)/Forestry_Trade_Flows_E_Flags.parquet |
| Format | parquet |
| File size | 980.0B |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:09.432136+00:00 |
| File last modified | 2026-07-05T03:52:37.159954+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; I |
| `Description` | Official figure; Estimated value; Imputed value |


---

# FAOSTAT_A-S_E__Forestry_Trade_Flows_E_All_Data_(Normalized)__Forestry_Trade_Flows_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Forestry_Trade_Flows_E_All_Data_(Normalized)/Forestry_Trade_Flows_E_ItemCodes.parquet |
| Format | parquet |
| File size | 417.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:44:09.439040+00:00 |
| File last modified | 2026-07-05T03:52:37.164016+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 2.0MB |
| Rows | 1,166,330 |
| Columns | 14 |
| File created | 2026-07-05T03:44:09.549952+00:00 |
| File last modified | 2026-07-05T03:52:38.148580+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Survey Code` | String | Categorical | No | 0 | 0.0% |
| `Survey` | String | Categorical | No | 0 | 0.0% |
| `Geographic Level Code` | String | Categorical | No | 0 | 0.0% |
| `Geographic Level` | String | Categorical | No | 0 | 0.0% |
| `Food Group Code` | String | Categorical | No | 0 | 0.0% |
| `Food Group` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | String | Categorical | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 21,121 | 1.81% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Survey Code` | 004_2020; 032_2018; 051_2019 |
| `Survey` | Afghanistan - 2020; Argentina - 2018; Armenia - 2019 |
| `Geographic Level Code` | 10000; 10001; 10002 |
| `Geographic Level` | National; Urban; Rural |
| `Food Group Code` | FG0; FGD; FG1 |
| `Food Group` | All food groups; All food groups (excluding beverages); Cereals and their products |
| `Indicator Code` | 3302; 3303; 3304 |
| `Indicator` | Energy apparent intake; Protein apparent intake; Fat apparent intake |
| `Element Code` | 6128A; 61281; 61282 |
| `Element` | Average; Confidence interval: Lower bound; Confidence interval: Upper bound |
| `Unit` | kcal/cap/d; g/cap/d; mg/cap/d |
| `Value` | 2352.0; 2329.0; 2374.0 |
| `Flag` | E |
| `Note` | Income, Expenditure and Labour Force Survey, October 2019 - September 2020.; Encuesta de Gastos de los Hogares, November 2017 - November 2018.; Integrated Living Conditions Survey, January 2019 - December 2019. |


---

# FAOSTAT_A-S_E__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_Elements.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 12 |
| Columns | 2 |
| File created | 2026-07-05T03:44:10.225399+00:00 |
| File last modified | 2026-07-05T03:52:38.152064+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | String | Categorical | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6123A; 6128A; 6206A |
| `Element` | Average; Confidence interval: Lower bound; Confidence interval: Upper bound |


---

# FAOSTAT_A-S_E__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_Flags.parquet |
| Format | parquet |
| File size | 879.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:10.240148+00:00 |
| File last modified | 2026-07-05T03:52:38.156781+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E |
| ` Description` | Estimated value |


---

# FAOSTAT_A-S_E__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_GeographicLevels

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_GeographicLevels.parquet |
| Format | parquet |
| File size | 7.8KB |
| Rows | 774 |
| Columns | 3 |
| File created | 2026-07-05T03:44:10.258143+00:00 |
| File last modified | 2026-07-05T03:52:38.160783+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Geographic Level Code` | String | Categorical | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | Yes | 774 | 100.0% |
| `Geographic Level` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Geographic Level Code` | 566_1; 566_2; 231_14 |
| `Geographic Level` | Abia; Adamawa; Addis Ababa |


---

# FAOSTAT_A-S_E__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_Indicators

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_Indicators.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 19 |
| Columns | 2 |
| File created | 2026-07-05T03:44:10.271245+00:00 |
| File last modified | 2026-07-05T03:52:38.162781+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Indicator Code` | 3307; 3305; 3306 |
| `Indicator` | Calcium apparent intake; Carbohydrate (available) apparent intake; Dietary Fibre apparent intake |


---

# FAOSTAT_A-S_E__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)__Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_Surveys

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_All_Data_(Normalized)/Household_Consumption_and_Expenditure_Surveys_Food_and_Diet_E_Surveys.parquet |
| Format | parquet |
| File size | 1.7KB |
| Rows | 59 |
| Columns | 2 |
| File created | 2026-07-05T03:44:10.285749+00:00 |
| File last modified | 2026-07-05T03:52:38.166383+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Survey Code` | String | Categorical | No | 0 | 0.0% |
| `Survey` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Survey Code` | 004_2020; 032_2018; 051_2019 |
| `Survey` | Afghanistan - 2020; Argentina - 2018; Armenia - 2019 |


---

# FAOSTAT_A-S_E__Indicators_from_Household_Surveys_E_All_Data_(Normalized)__Indicators_from_Household_Surveys_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Indicators_from_Household_Surveys_E_All_Data_(Normalized)/Indicators_from_Household_Surveys_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 602.1KB |
| Rows | 148,620 |
| Columns | 13 |
| File created | 2026-07-05T03:44:10.428714+00:00 |
| File last modified | 2026-07-05T03:52:38.393749+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Survey Code` | String | Categorical | No | 0 | 0.0% |
| `Survey` | String | Categorical | No | 0 | 0.0% |
| `Breakdown Variable Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Breakdown Variable` | String | Categorical | No | 0 | 0.0% |
| `Breadown by Sex of the Household Head Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Breadown by Sex of the Household Head` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Survey Code` | 008_2005; 031_2006; 050_20002001 |
| `Survey` | Albania - 2005; Azerbaijan - 2006; Bangladesh - 2000-2001 |
| `Breakdown Variable Code` | 20008; 20021; 20020 |
| `Breakdown Variable` | Country-level; Gender household head: Male; Gender household head: Female |
| `Breadown by Sex of the Household Head Code` | 20002; 20001; 20000 |
| `Breadown by Sex of the Household Head` | Male-headed household; Female-headed household; Total |
| `Indicator Code` | 6061; 6062; 6063 |
| `Indicator` | Total consumption in monetary value; Food consumption in monetary value; Dietary energy consumption |
| `Element Code` | 60761; 60771; 60781 |
| `Element` | Mean; Median; Standard Deviation |
| `Unit` | LCU/cap/d; No; kcal/cap/d |
| `Value` | 6617.69; 5541.07; 4375.79 |
| `Flag` | E |


---

# FAOSTAT_A-S_E__Indicators_from_Household_Surveys_E_All_Data_(Normalized)__Indicators_from_Household_Surveys_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Indicators_from_Household_Surveys_E_All_Data_(Normalized)/Indicators_from_Household_Surveys_E_Flags.parquet |
| Format | parquet |
| File size | 868.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:10.473175+00:00 |
| File last modified | 2026-07-05T03:52:38.453339+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E |
| `Description` | Estimated value |


---

# FAOSTAT_A-S_E__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 3.4MB |
| Rows | 2,191,084 |
| Columns | 18 |
| File created | 2026-07-05T03:44:10.578164+00:00 |
| File last modified | 2026-07-05T03:52:39.601394+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Survey Code` | String | Categorical | No | 0 | 0.0% |
| `Survey` | String | Categorical | No | 0 | 0.0% |
| `Geographic Level Code` | Int64 | Numeric | Yes | 1,950,294 | 89.01% |
| `Geographic Level` | String | Categorical | No | 0 | 0.0% |
| `Population Age Group Code` | String | Categorical | No | 0 | 0.0% |
| `Population Age Group` | String | Categorical | No | 0 | 0.0% |
| `Food Group Code` | String | Categorical | No | 0 | 0.0% |
| `Food Group` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Sex` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | String | Categorical | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Survey Code` | 076_20082009; 076_2014; 076_20172018 |
| `Survey` | Brazil - 2008-2009; Brazil - 2014; Brazil - 2017-2018 |
| `Geographic Level Code` | 10000; 10001; 10002 |
| `Geographic Level` | National; Urban; Rural |
| `Population Age Group Code` | allages; 9t18y; 9t13y |
| `Population Age Group` | All; 9-18 years; 9-13 years |
| `Food Group Code` | FGD; FG0; FG1 |
| `Food Group` | All food groups (excluding beverages); All food groups; Cereals and their products |
| `Indicator Code` | 3320; 3321; 3322 |
| `Indicator` | Food consumption, all subjects; Food consumption, consumers only; Percentage of consumers |
| `Element Code` | 6123; 6121; 6120 |
| `Element` | Value |
| `Sex Code` | 1; 2; 3 |
| `Sex` | Total; Male; Female |
| `Unit` | g/cap/d; %;  |
| `Value` | 1032.3; 1134.64; 939.09 |
| `Flag` | E |
| `Note` | Brazil-2008-2009; Brazil-2014; Brazil-2017-18 |


---

# FAOSTAT_A-S_E__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_Elements.parquet |
| Format | parquet |
| File size | 910.0B |
| Rows | 6 |
| Columns | 2 |
| File created | 2026-07-05T03:44:11.996205+00:00 |
| File last modified | 2026-07-05T03:52:39.605395+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 6120; 6121; 6123 |
| ` Element` | Value |


---

# FAOSTAT_A-S_E__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_Flags.parquet |
| Format | parquet |
| File size | 882.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:12.016178+00:00 |
| File last modified | 2026-07-05T03:52:39.609393+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | E |
| ` Description` | Estimated value |


---

# FAOSTAT_A-S_E__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_Indicators

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_Indicators.parquet |
| Format | parquet |
| File size | 1.4KB |
| Rows | 27 |
| Columns | 2 |
| File created | 2026-07-05T03:44:12.039256+00:00 |
| File last modified | 2026-07-05T03:52:39.624852+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Indicator` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Indicator Code` | 3334; 3331; 3332 |
| ` Indicator` | Calcium intake; Carbohydrate (total) intake; Dietary Fibre intake |


---

# FAOSTAT_A-S_E__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_PopulationAgeGroups

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_PopulationAgeGroups.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 11 |
| Columns | 2 |
| File created | 2026-07-05T03:44:12.052265+00:00 |
| File last modified | 2026-07-05T03:52:39.626740+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Population Age Group` | String | Categorical | No | 0 | 0.0% |
| ` Population Age Group_duplicated_0` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Population Age Group` | 12mb; 1t3y; 14t18y |
| ` Population Age Group_duplicated_0` | < 12 months; 1-3 years; 14-18 years |


---

# FAOSTAT_A-S_E__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_Sexs

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_Sexs.parquet |
| Format | parquet |
| File size | 888.0B |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:44:12.066185+00:00 |
| File last modified | 2026-07-05T03:52:39.628747+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Sex` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Sex Code` | 3; 2; 1 |
| ` Sex` | Female; Male; Total |


---

# FAOSTAT_A-S_E__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)__Individual_Quantitative_Dietary_Data_Food_and_Diet_E_Surveys

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_All_Data_(Normalized)/Individual_Quantitative_Dietary_Data_Food_and_Diet_E_Surveys.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 8 |
| Columns | 2 |
| File created | 2026-07-05T03:44:12.095022+00:00 |
| File last modified | 2026-07-05T03:52:39.632749+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Survey Code` | String | Categorical | No | 0 | 0.0% |
| ` Survey` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Survey Code` | 076_20082009; 076_2014; 076_20172018 |
| ` Survey` | Brazil - 2008-2009; Brazil - 2014; Brazil - 2017-2018 |


---

# FAOSTAT_A-S_E__Inputs_FertilizersArchive_E_All_Data_(Normalized)__Inputs_FertilizersArchive_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersArchive_E_All_Data_(Normalized)/Inputs_FertilizersArchive_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 577.5KB |
| Rows | 178,192 |
| Columns | 12 |
| File created | 2026-07-05T03:49:08.624971+00:00 |
| File last modified | 2026-07-05T03:52:39.808051+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 1379; 1368; 1361 |
| `Item` | Ammonium Phosphat (P2o5); Ammonium Phosphate (N); Ammonium sulphate |
| `Element Code` | 5610; 5157; 5751 |
| `Element` | Import Quantity; Agricultural Use; Prices Paid by Farmers |
| `Year Code` | 1972; 1973; 1974 |
| `Year` | 1972; 1973; 1974 |
| `Unit` | t; LCU/t |
| `Value` | 13110.0; 7600.0; 5200.0 |
| `Flag` | A; X; I |


---

# FAOSTAT_A-S_E__Inputs_FertilizersArchive_E_All_Data_(Normalized)__Inputs_FertilizersArchive_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersArchive_E_All_Data_(Normalized)/Inputs_FertilizersArchive_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.4KB |
| Rows | 273 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.655407+00:00 |
| File last modified | 2026-07-05T03:52:39.871924+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Inputs_FertilizersArchive_E_All_Data_(Normalized)__Inputs_FertilizersArchive_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersArchive_E_All_Data_(Normalized)/Inputs_FertilizersArchive_E_Flags.parquet |
| Format | parquet |
| File size | 953.0B |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:12.214679+00:00 |
| File last modified | 2026-07-05T03:52:39.874925+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; I |
| `Description` | Official figure; Estimated value; Imputed value |


---

# FAOSTAT_A-S_E__Inputs_FertilizersNutrient_E_All_Data_(Normalized)__Inputs_FertilizersNutrient_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersNutrient_E_All_Data_(Normalized)/Inputs_FertilizersNutrient_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 763.7KB |
| Rows | 241,859 |
| Columns | 13 |
| File created | 2026-07-05T03:44:12.316242+00:00 |
| File last modified | 2026-07-05T03:52:40.008206+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 30,425 | 12.58% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 3102; 3103; 3104 |
| `Item` | Nutrient nitrogen N (total); Nutrient phosphate P2O5 (total); Nutrient potash K2O (total) |
| `Element Code` | 5510; 5610; 5910 |
| `Element` | Production; Import quantity; Export quantity |
| `Year Code` | 1974; 1975; 1976 |
| `Year` | 1974; 1975; 1976 |
| `Unit` | t; kg/ha; kg/cap |
| `Value` | 19117.0; 14774.0; 26203.0 |
| `Flag` | A; X; I |
| `Note` | Official data from questionnaire; Data sourced from another international organization;  |


---

# FAOSTAT_A-S_E__Inputs_FertilizersNutrient_E_All_Data_(Normalized)__Inputs_FertilizersNutrient_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersNutrient_E_All_Data_(Normalized)/Inputs_FertilizersNutrient_E_AreaCodes.parquet |
| Format | parquet |
| File size | 5.0KB |
| Rows | 311 |
| Columns | 3 |
| File created | 2026-07-05T03:44:12.504142+00:00 |
| File last modified | 2026-07-05T03:52:40.012003+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 51000 |
| ` M49 Code` | '004; '002; '002.03 |
| ` Area` | Afghanistan; Africa; Africa (excluding intra-trade) |


---

# FAOSTAT_A-S_E__Inputs_FertilizersNutrient_E_All_Data_(Normalized)__Inputs_FertilizersNutrient_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersNutrient_E_All_Data_(Normalized)/Inputs_FertilizersNutrient_E_Elements.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 7 |
| Columns | 2 |
| File created | 2026-07-05T03:44:12.526154+00:00 |
| File last modified | 2026-07-05T03:52:40.015011+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 5157; 5910; 5610 |
| ` Element` | Agricultural Use; Export quantity; Import quantity |


---

# FAOSTAT_A-S_E__Inputs_FertilizersNutrient_E_All_Data_(Normalized)__Inputs_FertilizersNutrient_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersNutrient_E_All_Data_(Normalized)/Inputs_FertilizersNutrient_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:12.538844+00:00 |
| File last modified | 2026-07-05T03:52:40.018936+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; B; E |
| ` Description` | Official figure; Time series break; Estimated value |


---

# FAOSTAT_A-S_E__Inputs_FertilizersNutrient_E_All_Data_(Normalized)__Inputs_FertilizersNutrient_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersNutrient_E_All_Data_(Normalized)/Inputs_FertilizersNutrient_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.4KB |
| Rows | 1 |
| Columns | 3 |
| File created | 2026-07-05T03:44:12.552075+00:00 |
| File last modified | 2026-07-05T03:52:40.022949+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Item Code` | 3102 |
| ` CPC Code` | 'F3102 |
| ` Item` | Nutrient nitrogen N (total) |


---

# FAOSTAT_A-S_E__Inputs_FertilizersProduct_E_All_Data_(Normalized)__Inputs_FertilizersProduct_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersProduct_E_All_Data_(Normalized)/Inputs_FertilizersProduct_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 1.3MB |
| Rows | 303,498 |
| Columns | 12 |
| File created | 2026-07-05T03:44:12.639962+00:00 |
| File last modified | 2026-07-05T03:52:40.163053+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 4007; 4003; 4002 |
| `Item` | Ammonia, anhydrous; Ammonium nitrate (AN); Ammonium sulphate |
| `Element Code` | 5610; 5622; 5910 |
| `Element` | Import quantity; Import value; Export quantity |
| `Year Code` | 2011; 2014; 2017 |
| `Year` | 2011; 2014; 2017 |
| `Unit` | t; 1000 USD |
| `Value` | 4.49; 2.0; 2.07 |
| `Flag` | I; A; X |


---

# FAOSTAT_A-S_E__Inputs_FertilizersProduct_E_All_Data_(Normalized)__Inputs_FertilizersProduct_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersProduct_E_All_Data_(Normalized)/Inputs_FertilizersProduct_E_AreaCodes.parquet |
| Format | parquet |
| File size | 5.0KB |
| Rows | 310 |
| Columns | 3 |
| File created | 2026-07-05T03:44:12.805160+00:00 |
| File last modified | 2026-07-05T03:52:40.167288+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 51000 |
| ` M49 Code` | '004; '002; '002.03 |
| ` Area` | Afghanistan; Africa; Africa (excluding intra-trade) |


---

# FAOSTAT_A-S_E__Inputs_FertilizersProduct_E_All_Data_(Normalized)__Inputs_FertilizersProduct_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersProduct_E_All_Data_(Normalized)/Inputs_FertilizersProduct_E_Elements.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 6 |
| Columns | 2 |
| File created | 2026-07-05T03:44:12.818668+00:00 |
| File last modified | 2026-07-05T03:52:40.170287+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 5157; 5910; 5922 |
| ` Element` | Agricultural Use; Export quantity; Export value |


---

# FAOSTAT_A-S_E__Inputs_FertilizersProduct_E_All_Data_(Normalized)__Inputs_FertilizersProduct_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersProduct_E_All_Data_(Normalized)/Inputs_FertilizersProduct_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:12.824584+00:00 |
| File last modified | 2026-07-05T03:52:40.175294+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Inputs_FertilizersProduct_E_All_Data_(Normalized)__Inputs_FertilizersProduct_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_FertilizersProduct_E_All_Data_(Normalized)/Inputs_FertilizersProduct_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.9KB |
| Rows | 23 |
| Columns | 3 |
| File created | 2026-07-05T03:44:12.843132+00:00 |
| File last modified | 2026-07-05T03:52:40.179284+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Item Code` | 4001; 4002; 4003 |
| ` CPC Code` | '34611; '34612; '34613 |
| ` Item` | Urea; Ammonium sulphate; Ammonium nitrate (AN) |


---

# FAOSTAT_A-S_E__Inputs_LandUse_E_All_Data_(Normalized)__Inputs_LandUse_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_LandUse_E_All_Data_(Normalized)/Inputs_LandUse_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 1.1MB |
| Rows | 413,211 |
| Columns | 13 |
| File created | 2026-07-05T03:44:12.948862+00:00 |
| File last modified | 2026-07-05T03:52:40.342081+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 413,211 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 6600; 6601; 6602 |
| `Item` | Country area; Land area; Agriculture |
| `Element Code` | 5110; 7209; 7278 |
| `Element` | Area; Share in Land area; Value of agricultural production (Int. $) per Area |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | 1000 ha; %; USD_PPP/ha |
| `Value` | 65286.0; 65287.0; 65223.0 |
| `Flag` | A; I; E |


---

# FAOSTAT_A-S_E__Inputs_LandUse_E_All_Data_(Normalized)__Inputs_LandUse_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_LandUse_E_All_Data_(Normalized)/Inputs_LandUse_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 284 |
| Columns | 3 |
| File created | 2026-07-05T03:44:13.239384+00:00 |
| File last modified | 2026-07-05T03:52:40.346078+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Inputs_LandUse_E_All_Data_(Normalized)__Inputs_LandUse_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_LandUse_E_All_Data_(Normalized)/Inputs_LandUse_E_Elements.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 9 |
| Columns | 2 |
| File created | 2026-07-05T03:44:13.262999+00:00 |
| File last modified | 2026-07-05T03:52:40.349507+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 5110; 7277; 72151 |
| `Element` | Area; Area per capita; Carbon stock in living biomass |


---

# FAOSTAT_A-S_E__Inputs_LandUse_E_All_Data_(Normalized)__Inputs_LandUse_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_LandUse_E_All_Data_(Normalized)/Inputs_LandUse_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:13.274565+00:00 |
| File last modified | 2026-07-05T03:52:40.358508+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; B; E |
| ` Description` | Official figure; Time series break; Estimated value |


---

# FAOSTAT_A-S_E__Inputs_LandUse_E_All_Data_(Normalized)__Inputs_LandUse_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_LandUse_E_All_Data_(Normalized)/Inputs_LandUse_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.9KB |
| Rows | 51 |
| Columns | 3 |
| File created | 2026-07-05T03:44:13.309632+00:00 |
| File last modified | 2026-07-05T03:52:40.362725+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | Yes | 51 | 100.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 6610; 66710; 6602 |
| `Item` | Agricultural land; Agricultural practices; Agriculture |


---

# FAOSTAT_A-S_E__Inputs_Pesticides_Trade_E_All_Data_(Normalized)__Inputs_Pesticides_Trade_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_Pesticides_Trade_E_All_Data_(Normalized)/Inputs_Pesticides_Trade_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 985.0KB |
| Rows | 190,740 |
| Columns | 12 |
| File created | 2026-07-05T03:44:13.392897+00:00 |
| File last modified | 2026-07-05T03:52:40.475707+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 3; 4; 6 |
| `Area Code (M49)` | '008; '012; '020 |
| `Area` | Albania; Algeria; Andorra |
| `Item Code` | 1357; 1416; 1417 |
| `Item` | Pesticides (total); Insecticides; Fungicides |
| `Element Code` | 5610; 5622; 5910 |
| `Element` | Import quantity; Import value; Export quantity |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Unit` | t; 1000 USD |
| `Value` | 1975.862; 86.566; 213.701 |
| `Flag` | I; B; A |


---

# FAOSTAT_A-S_E__Inputs_Pesticides_Trade_E_All_Data_(Normalized)__Inputs_Pesticides_Trade_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_Pesticides_Trade_E_All_Data_(Normalized)/Inputs_Pesticides_Trade_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.8KB |
| Rows | 300 |
| Columns | 3 |
| File created | 2026-07-05T03:44:13.520549+00:00 |
| File last modified | 2026-07-05T03:52:40.478665+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 5100; 51000; 3 |
| ` M49 Code` | '002; '002.03; '008 |
| ` Area` | Africa; Africa (excluding intra-trade); Albania |


---

# FAOSTAT_A-S_E__Inputs_Pesticides_Trade_E_All_Data_(Normalized)__Inputs_Pesticides_Trade_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_Pesticides_Trade_E_All_Data_(Normalized)/Inputs_Pesticides_Trade_E_Elements.parquet |
| Format | parquet |
| File size | 1015.0B |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:13.540596+00:00 |
| File last modified | 2026-07-05T03:52:40.480678+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 5910; 5922; 5610 |
| ` Element` | Export quantity; Export value; Import quantity |


---

# FAOSTAT_A-S_E__Inputs_Pesticides_Trade_E_All_Data_(Normalized)__Inputs_Pesticides_Trade_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_Pesticides_Trade_E_All_Data_(Normalized)/Inputs_Pesticides_Trade_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:13.547811+00:00 |
| File last modified | 2026-07-05T03:52:40.483677+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; B; E |
| ` Description` | Official figure; Time series break; Estimated value |


---

# FAOSTAT_A-S_E__Inputs_Pesticides_Trade_E_All_Data_(Normalized)__Inputs_Pesticides_Trade_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_Pesticides_Trade_E_All_Data_(Normalized)/Inputs_Pesticides_Trade_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:44:13.553820+00:00 |
| File last modified | 2026-07-05T03:52:40.486676+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Inputs_Pesticides_Use_E_All_Data_(Normalized)__Inputs_Pesticides_Use_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_Pesticides_Use_E_All_Data_(Normalized)/Inputs_Pesticides_Use_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 241.4KB |
| Rows | 103,622 |
| Columns | 13 |
| File created | 2026-07-05T03:44:13.636941+00:00 |
| File last modified | 2026-07-05T03:52:40.582812+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 3; 4; 6 |
| `Area Code (M49)` | '008; '012; '020 |
| `Area` | Albania; Algeria; Andorra |
| `Item Code` | 1357; 1309; 1310 |
| `Item` | Pesticides (total); Insecticides; Insecticides – Chlorinated Hydrocarbons |
| `Element Code` | 5157; 5159; 5172 |
| `Element` | Agricultural Use; Use per area of cropland; Use per capita |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Unit` | t; kg/ha; kg/cap |
| `Value` | 121.0; 201.0; 251.0 |
| `Flag` | I; A; E |
| `Note` | Imputed value; Official figure; Estimated Value |


---

# FAOSTAT_A-S_E__Inputs_Pesticides_Use_E_All_Data_(Normalized)__Inputs_Pesticides_Use_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_Pesticides_Use_E_All_Data_(Normalized)/Inputs_Pesticides_Use_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.2KB |
| Rows | 256 |
| Columns | 3 |
| File created | 2026-07-05T03:44:13.763616+00:00 |
| File last modified | 2026-07-05T03:52:40.586809+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 5100; 3; 4 |
| ` M49 Code` | '002; '008; '012 |
| ` Area` | Africa; Albania; Algeria |


---

# FAOSTAT_A-S_E__Inputs_Pesticides_Use_E_All_Data_(Normalized)__Inputs_Pesticides_Use_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_Pesticides_Use_E_All_Data_(Normalized)/Inputs_Pesticides_Use_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:13.785161+00:00 |
| File last modified | 2026-07-05T03:52:40.590806+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 5157; 5159; 5172 |
| ` Element` | Agricultural Use; Use per area of cropland; Use per capita |


---

# FAOSTAT_A-S_E__Inputs_Pesticides_Use_E_All_Data_(Normalized)__Inputs_Pesticides_Use_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_Pesticides_Use_E_All_Data_(Normalized)/Inputs_Pesticides_Use_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:13.791252+00:00 |
| File last modified | 2026-07-05T03:52:40.592809+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Inputs_Pesticides_Use_E_All_Data_(Normalized)__Inputs_Pesticides_Use_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Inputs_Pesticides_Use_E_All_Data_(Normalized)/Inputs_Pesticides_Use_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:44:13.796560+00:00 |
| File last modified | 2026-07-05T03:52:40.594807+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Investment_CapitalStock_E_All_Data_(Normalized)__Investment_CapitalStock_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CapitalStock_E_All_Data_(Normalized)/Investment_CapitalStock_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 734.3KB |
| Rows | 144,944 |
| Columns | 13 |
| File created | 2026-07-05T03:44:13.892306+00:00 |
| File last modified | 2026-07-05T03:52:40.717859+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 144,944 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 22030; 22031; 22034 |
| `Item` | Gross Fixed Capital Formation (Agriculture, Forestry and Fishing); Consumption of Fixed Capital (Agriculture, Forestry and Fishing); Net Capital Stocks (Agriculture, Forestry and Fishing) |
| `Element Code` | 6224; 6225; 6110 |
| `Element` | Value Standard Local Currency; Value Standard Local Currency, 2015 prices; Value US$ |
| `Year Code` | 1995; 1996; 1997 |
| `Year` | 1995; 1996; 1997 |
| `Unit` | million SLC; million USD; % |
| `Value` | 94.336086; 264.974931; 294.793052 |
| `Flag` | I; F; X |


---

# FAOSTAT_A-S_E__Investment_CapitalStock_E_All_Data_(Normalized)__Investment_CapitalStock_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CapitalStock_E_All_Data_(Normalized)/Investment_CapitalStock_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.9KB |
| Rows | 232 |
| Columns | 3 |
| File created | 2026-07-05T03:44:14.025582+00:00 |
| File last modified | 2026-07-05T03:52:40.722786+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Investment_CapitalStock_E_All_Data_(Normalized)__Investment_CapitalStock_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CapitalStock_E_All_Data_(Normalized)/Investment_CapitalStock_E_Elements.parquet |
| Format | parquet |
| File size | 1.4KB |
| Rows | 16 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.044452+00:00 |
| File last modified | 2026-07-05T03:52:40.726748+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 61120; 61940; 6159 |
| ` Element` | Agriculture orientation index Standard Local Currency; Agriculture orientation index Standard Local Currency; 2015 prices; Agriculture orientation index US$ |


---

# FAOSTAT_A-S_E__Investment_CapitalStock_E_All_Data_(Normalized)__Investment_CapitalStock_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CapitalStock_E_All_Data_(Normalized)/Investment_CapitalStock_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.051458+00:00 |
| File last modified | 2026-07-05T03:52:40.730743+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E; F |
| ` Description` | Official figure; Estimated value; Forecast value |


---

# FAOSTAT_A-S_E__Investment_CapitalStock_E_All_Data_(Normalized)__Investment_CapitalStock_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CapitalStock_E_All_Data_(Normalized)/Investment_CapitalStock_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:44:14.056410+00:00 |
| File last modified | 2026-07-05T03:52:40.732743+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)__Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)/Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 466.1KB |
| Rows | 66,447 |
| Columns | 13 |
| File created | 2026-07-05T03:44:14.137283+00:00 |
| File last modified | 2026-07-05T03:52:40.801799+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 66,447 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 22016; 22030; 23131 |
| `Item` | Value Added (Agriculture, Forestry and Fishing); Gross Fixed Capital Formation (Agriculture, Forestry and Fishing); Agriculture, forestry, fishing (general government expenditure) |
| `Element Code` | 61840; 61390; 6182 |
| `Element` | Value US$, 2015 prices; Share of Total US$, 2015 prices; Annual growth US$, 2015 prices |
| `Year Code` | 2001; 2002; 2003 |
| `Year` | 2001; 2002; 2003 |
| `Unit` | million USD; %;  |
| `Value` | 2872.475057; 3842.257463; 3976.299728 |
| `Flag` | X; E; I |


---

# FAOSTAT_A-S_E__Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)__Investment_CountryInvestmentStatisticsProfile_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)/Investment_CountryInvestmentStatisticsProfile_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.3KB |
| Rows | 258 |
| Columns | 3 |
| File created | 2026-07-05T03:44:14.210581+00:00 |
| File last modified | 2026-07-05T03:52:40.805758+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)__Investment_CountryInvestmentStatisticsProfile_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)/Investment_CountryInvestmentStatisticsProfile_E_Elements.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 8 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.230579+00:00 |
| File last modified | 2026-07-05T03:52:40.808760+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6159; 6193; 6182 |
| `Element` | Agriculture orientation index US$; Agriculture orientation index US$; 2015 prices; Annual growth US$; 2015 prices |


---

# FAOSTAT_A-S_E__Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)__Investment_CountryInvestmentStatisticsProfile_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)/Investment_CountryInvestmentStatisticsProfile_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 6 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.242584+00:00 |
| File last modified | 2026-07-05T03:52:40.812755+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; F |
| ` Description` | Official figure; Estimated value; Forecast value |


---

# FAOSTAT_A-S_E__Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)__Investment_CountryInvestmentStatisticsProfile_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CountryInvestmentStatisticsProfile_E_All_Data_(Normalized)/Investment_CountryInvestmentStatisticsProfile_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.4KB |
| Rows | 6 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.262119+00:00 |
| File last modified | 2026-07-05T03:52:40.816787+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 23131; 23068; 23070 |
| `Item` | Agriculture; forestry; fishing (general government expenditure); Credit to Agriculture; Forestry and Fishing; DFA Disbursement to Agriculture; Forestry and Fishing |


---

# FAOSTAT_A-S_E__Investment_CreditAgriculture_E_All_Data_(Normalized)__Investment_CreditAgriculture_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CreditAgriculture_E_All_Data_(Normalized)/Investment_CreditAgriculture_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 406.5KB |
| Rows | 62,899 |
| Columns | 12 |
| File created | 2026-07-05T03:44:14.327115+00:00 |
| File last modified | 2026-07-05T03:52:40.883319+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 23018; 23068; 23019 |
| `Item` | Total Credit; Credit to Agriculture, Forestry and Fishing; Credit to Agriculture |
| `Element Code` | 6224; 6225; 6110 |
| `Element` | Value Standard Local Currency; Value Standard Local Currency, 2015 prices; Value US$ |
| `Year Code` | 2008; 2010; 2011 |
| `Year` | 2008; 2010; 2011 |
| `Unit` | million SLC; million USD; % |
| `Value` | 40000.0; 63646.367188; 80240.0 |
| `Flag` | A; X; E |


---

# FAOSTAT_A-S_E__Investment_CreditAgriculture_E_All_Data_(Normalized)__Investment_CreditAgriculture_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CreditAgriculture_E_All_Data_(Normalized)/Investment_CreditAgriculture_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.7KB |
| Rows | 212 |
| Columns | 3 |
| File created | 2026-07-05T03:44:14.406130+00:00 |
| File last modified | 2026-07-05T03:52:40.889223+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Investment_CreditAgriculture_E_All_Data_(Normalized)__Investment_CreditAgriculture_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CreditAgriculture_E_All_Data_(Normalized)/Investment_CreditAgriculture_E_Elements.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 7 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.423629+00:00 |
| File last modified | 2026-07-05T03:52:40.893223+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6193; 61631; 61133 |
| `Element` | Agriculture orientation index US$; 2015 prices; Ratio of Value Added (Agriculture; Forestry and Fishing) US$; 2015 prices; Share of Total Credit US$; 2015 prices |


---

# FAOSTAT_A-S_E__Investment_CreditAgriculture_E_All_Data_(Normalized)__Investment_CreditAgriculture_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CreditAgriculture_E_All_Data_(Normalized)/Investment_CreditAgriculture_E_Flags.parquet |
| Format | parquet |
| File size | 947.0B |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.437628+00:00 |
| File last modified | 2026-07-05T03:52:40.895222+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; X |
| ` Description` | Official figure; Estimated value; Figure from external organization |


---

# FAOSTAT_A-S_E__Investment_CreditAgriculture_E_All_Data_(Normalized)__Investment_CreditAgriculture_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_CreditAgriculture_E_All_Data_(Normalized)/Investment_CreditAgriculture_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 8 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.456728+00:00 |
| File last modified | 2026-07-05T03:52:40.897226+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 23019; 23066; 23067 |
| `Item` | Credit to Agriculture; Credit to Agriculture and Fishery; Credit to Agriculture and Forestry |


---

# FAOSTAT_A-S_E__Investment_ForeignDirectInvestment_E_All_Data_(Normalized)__Investment_ForeignDirectInvestment_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_ForeignDirectInvestment_E_All_Data_(Normalized)/Investment_ForeignDirectInvestment_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 290.5KB |
| Rows | 40,442 |
| Columns | 13 |
| File created | 2026-07-05T03:44:14.520037+00:00 |
| File last modified | 2026-07-05T03:52:40.960642+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 4,602 | 11.38% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 23082; 23085; 23080 |
| `Item` | Total FDI inflows; Total FDI outflows; FDI inflows to Agriculture, Forestry and Fishing |
| `Element Code` | 6110; 6184; 61410 |
| `Element` | Value US$; Value US$, 2015 prices; Share of Total FDI inflows US$, 2015 prices |
| `Year Code` | 1990; 1991; 1992 |
| `Year` | 1990; 1991; 1992 |
| `Unit` | million USD; % |
| `Value` | 1e-05; -0.28; 0.36 |
| `Flag` | X; P |
| `Note` | UNCTAD; ; OECD |


---

# FAOSTAT_A-S_E__Investment_ForeignDirectInvestment_E_All_Data_(Normalized)__Investment_ForeignDirectInvestment_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_ForeignDirectInvestment_E_All_Data_(Normalized)/Investment_ForeignDirectInvestment_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 282 |
| Columns | 3 |
| File created | 2026-07-05T03:44:14.585783+00:00 |
| File last modified | 2026-07-05T03:52:40.965058+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Investment_ForeignDirectInvestment_E_All_Data_(Normalized)__Investment_ForeignDirectInvestment_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_ForeignDirectInvestment_E_All_Data_(Normalized)/Investment_ForeignDirectInvestment_E_Elements.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.597736+00:00 |
| File last modified | 2026-07-05T03:52:40.969429+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 61410; 61420; 6110 |
| ` Element` | Share of Total FDI inflows US$; 2015 prices; Share of Total FDI outflows US$; 2015 prices; Value US$ |


---

# FAOSTAT_A-S_E__Investment_ForeignDirectInvestment_E_All_Data_(Normalized)__Investment_ForeignDirectInvestment_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_ForeignDirectInvestment_E_All_Data_(Normalized)/Investment_ForeignDirectInvestment_E_Flags.parquet |
| Format | parquet |
| File size | 1010.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.608628+00:00 |
| File last modified | 2026-07-05T03:52:40.974428+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | P; X |
| ` Description` | Provisional value; Figure from external organization |


---

# FAOSTAT_A-S_E__Investment_ForeignDirectInvestment_E_All_Data_(Normalized)__Investment_ForeignDirectInvestment_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_ForeignDirectInvestment_E_All_Data_(Normalized)/Investment_ForeignDirectInvestment_E_ItemCodes.parquet |
| Format | parquet |
| File size | 420.0B |
| Rows | 0 |
| Columns | 3 |
| File created | 2026-07-05T03:44:14.614601+00:00 |
| File last modified | 2026-07-05T03:52:40.978429+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Item Code` | String | Categorical | No | 0 | 0.0% |
| ` CPC Code` | String | Categorical | No | 0 | 0.0% |
| ` Item` | String | Categorical | No | 0 | 0.0% |


---

# FAOSTAT_A-S_E__Investment_GovernmentExpenditure_E_All_Data_(Normalized)__Investment_GovernmentExpenditure_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_GovernmentExpenditure_E_All_Data_(Normalized)/Investment_GovernmentExpenditure_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 521.4KB |
| Rows | 156,256 |
| Columns | 13 |
| File created | 2026-07-05T03:44:14.712653+00:00 |
| File last modified | 2026-07-05T03:52:41.106925+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 4 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 23130; 23131; 23144 |
| `Item` | Total Expenditure (general government); Agriculture, forestry, fishing (general government expenditure); Environmental protection (general government expenditure) |
| `Element Code` | 6224; 6110; 6184 |
| `Element` | Value Standard Local Currency; Value US$; Value US$, 2015 prices |
| `Year Code` | 2006; 2007; 2008 |
| `Year` | 2006; 2007; 2008 |
| `Unit` | million SLC; million USD; % |
| `Value` | 111274.57; 165029.87; 466732.04 |
| `Flag` | X; E; A |
| `Note` | consolidated General Government; Budgetary Central Government; consolidated Central Government |


---

# FAOSTAT_A-S_E__Investment_GovernmentExpenditure_E_All_Data_(Normalized)__Investment_GovernmentExpenditure_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_GovernmentExpenditure_E_All_Data_(Normalized)/Investment_GovernmentExpenditure_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.7KB |
| Rows | 287 |
| Columns | 3 |
| File created | 2026-07-05T03:44:14.839245+00:00 |
| File last modified | 2026-07-05T03:52:41.113231+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Investment_GovernmentExpenditure_E_All_Data_(Normalized)__Investment_GovernmentExpenditure_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_GovernmentExpenditure_E_All_Data_(Normalized)/Investment_GovernmentExpenditure_E_Elements.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 7 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.851249+00:00 |
| File last modified | 2026-07-05T03:52:41.116756+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6197; 6131; 61060 |
| `Element` | SDG 2.a.1: Agriculture Orientation Index (AOI) for Government Expenditure; SDG 2.a.1: Agriculture share of Government Expenditure; SDG 2.a.1: Agriculture value added share of GDP |


---

# FAOSTAT_A-S_E__Investment_GovernmentExpenditure_E_All_Data_(Normalized)__Investment_GovernmentExpenditure_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_GovernmentExpenditure_E_All_Data_(Normalized)/Investment_GovernmentExpenditure_E_Flags.parquet |
| Format | parquet |
| File size | 947.0B |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.857862+00:00 |
| File last modified | 2026-07-05T03:52:41.121030+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; X |
| ` Description` | Official figure; Estimated value; Figure from external organization |


---

# FAOSTAT_A-S_E__Investment_GovernmentExpenditure_E_All_Data_(Normalized)__Investment_GovernmentExpenditure_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_GovernmentExpenditure_E_All_Data_(Normalized)/Investment_GovernmentExpenditure_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.8KB |
| Rows | 47 |
| Columns | 2 |
| File created | 2026-07-05T03:44:14.881086+00:00 |
| File last modified | 2026-07-05T03:52:41.127016+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 23164; 23134; 23166 |
| `Item` | Agriculture (central government expenditure); Agriculture (general government expenditure); Agriculture; Capital (central government expenditure) |


---

# FAOSTAT_A-S_E__Investment_Machinery_E_All_Data_(Normalized)__Investment_Machinery_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_Machinery_E_All_Data_(Normalized)/Investment_Machinery_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 476.0KB |
| Rows | 146,834 |
| Columns | 13 |
| File created | 2026-07-05T03:44:14.967237+00:00 |
| File last modified | 2026-07-05T03:52:41.284694+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 146,342 | 99.66% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 2455017; 2455011; 2455009 |
| `Item` | Agricultural machinery nes (trade); Agricultural tractors; Agricultural tractors, total |
| `Element Code` | 5622; 5116; 5607 |
| `Element` | Import Value; In Use; Import Quantity |
| `Year Code` | 1971; 1972; 1973 |
| `Year` | 1971; 1972; 1973 |
| `Unit` | 1000 USD; No |
| `Value` | 15.0; 3.0; 9.0 |
| `Flag` | A; E; X |
| `Note` | Unofficial figure |


---

# FAOSTAT_A-S_E__Investment_Machinery_E_All_Data_(Normalized)__Investment_Machinery_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_Machinery_E_All_Data_(Normalized)/Investment_Machinery_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.5KB |
| Rows | 277 |
| Columns | 3 |
| File created | 2026-07-05T03:49:08.687822+00:00 |
| File last modified | 2026-07-05T03:52:41.333289+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Investment_Machinery_E_All_Data_(Normalized)__Investment_Machinery_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_Machinery_E_All_Data_(Normalized)/Investment_Machinery_E_Flags.parquet |
| Format | parquet |
| File size | 940.0B |
| Rows | 3 |
| Columns | 2 |
| File created | 2026-07-05T03:44:15.023880+00:00 |
| File last modified | 2026-07-05T03:52:41.341265+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; X |
| `Description` | Official figure; Estimated value; Figure from international organizations |


---

# FAOSTAT_A-S_E__Investment_MachineryArchive_E_All_Data_(Normalized)__Investment_MachineryArchive_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_MachineryArchive_E_All_Data_(Normalized)/Investment_MachineryArchive_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 353.2KB |
| Rows | 328,932 |
| Columns | 12 |
| File created | 2026-07-05T03:44:15.115284+00:00 |
| File last modified | 2026-07-05T03:52:41.496130+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | Yes | 117,530 | 35.73% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 1300; 1306; 1307 |
| `Item` | Agr Machinery nes; Harvesters-Threshers; Milking machines |
| `Element Code` | 5116; 5607; 5622 |
| `Element` | In Use; Import quantity; Import value |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | No; 1000 USD |
| `Value` | 0.0; 15.0; 3.0 |
| `Flag` | O; A; E |


---

# FAOSTAT_A-S_E__Investment_MachineryArchive_E_All_Data_(Normalized)__Investment_MachineryArchive_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_MachineryArchive_E_All_Data_(Normalized)/Investment_MachineryArchive_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.5KB |
| Rows | 277 |
| Columns | 3 |
| File created | 2026-07-05T03:44:15.296864+00:00 |
| File last modified | 2026-07-05T03:52:41.500142+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Investment_MachineryArchive_E_All_Data_(Normalized)__Investment_MachineryArchive_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_MachineryArchive_E_All_Data_(Normalized)/Investment_MachineryArchive_E_Elements.parquet |
| Format | parquet |
| File size | 987.0B |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:15.313943+00:00 |
| File last modified | 2026-07-05T03:52:41.505158+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 5907; 5922; 5607 |
| `Element` | Export quantity; Export value; Import quantity |


---

# FAOSTAT_A-S_E__Investment_MachineryArchive_E_All_Data_(Normalized)__Investment_MachineryArchive_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_MachineryArchive_E_All_Data_(Normalized)/Investment_MachineryArchive_E_Flags.parquet |
| Format | parquet |
| File size | 963.0B |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:15.324963+00:00 |
| File last modified | 2026-07-05T03:52:41.509119+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; O |
| ` Description` | Official figure; Estimated value; Missing value |


---

# FAOSTAT_A-S_E__Investment_MachineryArchive_E_All_Data_(Normalized)__Investment_MachineryArchive_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Investment_MachineryArchive_E_All_Data_(Normalized)/Investment_MachineryArchive_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 7 |
| Columns | 3 |
| File created | 2026-07-05T03:44:15.343741+00:00 |
| File last modified | 2026-07-05T03:52:41.513132+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | Yes | 7 | 100.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 1300; 1915; 1911 |
| `Item` | Agr Machinery nes; Agricultural Machines; Agricultural Requisites |


---

# FAOSTAT_A-S_E__Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)__Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)/Macro-Statistics_Key_Indicators_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 3.8MB |
| Rows | 708,632 |
| Columns | 13 |
| File created | 2026-07-05T03:44:15.437700+00:00 |
| File last modified | 2026-07-05T03:52:41.796877+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 708,632 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 22008; 22015; 22016 |
| `Item` | Gross Domestic Product; Gross Fixed Capital Formation; Value Added (Agriculture, Forestry and Fishing) |
| `Element Code` | 6224; 6110; 6119 |
| `Element` | Value Standard Local Currency; Value US$; Value US$ per capita |
| `Year Code` | 1970; 1971; 1972 |
| `Year` | 1970; 1971; 1972 |
| `Unit` | million SLC; million USD; USD |
| `Value` | 78.697146; 82.397024; 71.797487 |
| `Flag` | X; E |


---

# FAOSTAT_A-S_E__Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)__Macro-Statistics_Key_Indicators_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)/Macro-Statistics_Key_Indicators_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.2KB |
| Rows | 252 |
| Columns | 3 |
| File created | 2026-07-05T03:44:15.836442+00:00 |
| File last modified | 2026-07-05T03:52:41.801359+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)__Macro-Statistics_Key_Indicators_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)/Macro-Statistics_Key_Indicators_E_Elements.parquet |
| Format | parquet |
| File size | 1.4KB |
| Rows | 20 |
| Columns | 2 |
| File created | 2026-07-05T03:44:15.850471+00:00 |
| File last modified | 2026-07-05T03:52:41.804361+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 61550; 61810; 6129 |
| `Element` | Annual growth Standard Local Currency; Annual growth Standard Local Currency; 2015 prices; Annual growth US$ |


---

# FAOSTAT_A-S_E__Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)__Macro-Statistics_Key_Indicators_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)/Macro-Statistics_Key_Indicators_E_Flags.parquet |
| Format | parquet |
| File size | 996.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:44:15.872551+00:00 |
| File last modified | 2026-07-05T03:52:41.806358+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E; X |
| ` Description` | Estimated value; Figure from external organization |


---

# FAOSTAT_A-S_E__Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)__Macro-Statistics_Key_Indicators_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Macro-Statistics_Key_Indicators_E_All_Data_(Normalized)/Macro-Statistics_Key_Indicators_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 11 |
| Columns | 2 |
| File created | 2026-07-05T03:44:15.893067+00:00 |
| File last modified | 2026-07-05T03:52:41.810357+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 22008; 22015; 22011 |
| `Item` | Gross Domestic Product; Gross Fixed Capital Formation; Gross National Income |


---

# FAOSTAT_A-S_E__Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)__Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)/Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 10.0KB |
| Rows | 1,223 |
| Columns | 13 |
| File created | 2026-07-05T03:44:15.947987+00:00 |
| File last modified | 2026-07-05T03:52:41.821938+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Survey Code` | String | Categorical | No | 0 | 0.0% |
| `Survey` | String | Categorical | No | 0 | 0.0% |
| `Food Group Code` | String | Categorical | No | 0 | 0.0% |
| `Food Group` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Geographic Level Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Geographic Level` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Survey Code` | 076_2014; 854_2021; 116_2021 |
| `Survey` | Brazil - 2014; Burkina Faso - 2021; Cambodia - 2021 |
| `Food Group Code` | FGW0; FGW1; FGW2 |
| `Food Group` | MDD-W Food groups; Grains, white roots and tubers, and plantains; Pulses (beans, peas and lentils) |
| `Indicator Code` | 6211; 6212 |
| `Indicator` | Percentage of women achieving MDD-W; Percentage of women consuming each food group |
| `Geographic Level Code` | 10000; 10002; 10001 |
| `Geographic Level` | National; Rural; Urban |
| `Element Code` | 6121 |
| `Element` | Value |
| `Unit` | % |
| `Value` | 54.8; 70.1; 54.4 |
| `Flag` | E; A |


---

# FAOSTAT_A-S_E__Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)__Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)/Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_Elements.parquet |
| Format | parquet |
| File size | 886.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:15.963920+00:00 |
| File last modified | 2026-07-05T03:52:41.824936+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 6121 |
| ` Element` | Value |


---

# FAOSTAT_A-S_E__Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)__Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)/Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_Flags.parquet |
| Format | parquet |
| File size | 908.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:44:15.970819+00:00 |
| File last modified | 2026-07-05T03:52:41.826932+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | A; E |
| ` Description` | Official figure; Estimated value |


---

# FAOSTAT_A-S_E__Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)__Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_Indicators

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)/Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_Indicators.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:44:15.990786+00:00 |
| File last modified | 2026-07-05T03:52:41.829938+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Indicator` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Indicator Code` | 6211; 6212 |
| ` Indicator` | Percentage of women achieving MDD-W; Percentage of women consuming each food group |


---

# FAOSTAT_A-S_E__Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)__Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_Surveys

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_All_Data_(Normalized)/Minimum_Dietary_Diversity_for_Women_(MDD-W)_Food_and_Diet_E_Surveys.parquet |
| Format | parquet |
| File size | 1.4KB |
| Rows | 25 |
| Columns | 2 |
| File created | 2026-07-05T03:44:16.008663+00:00 |
| File last modified | 2026-07-05T03:52:41.832935+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Survey Code` | String | Categorical | No | 0 | 0.0% |
| ` Survey` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Survey Code` | 076_2014; 854_2021; 116_2021 |
| ` Survey` | Brazil - 2014; Burkina Faso - 2021; Cambodia - 2021 |


---

# FAOSTAT_A-S_E__Population_E_All_Data_(Normalized)__Population_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Population_E_All_Data_(Normalized)/Population_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 755.9KB |
| Rows | 168,405 |
| Columns | 13 |
| File created | 2026-07-05T03:44:16.096114+00:00 |
| File last modified | 2026-07-05T03:52:41.943871+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 168,405 | 100.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 3010 |
| `Item` | Population - Est. & Proj. |
| `Element Code` | 511; 512; 513 |
| `Element` | Total Population - Both sexes; Total Population - Male; Total Population - Female |
| `Year Code` | 1950; 1951; 1952 |
| `Year` | 1950; 1951; 1952 |
| `Unit` | 1000 No |
| `Value` | 7776.176; 7879.339; 7987.783 |
| `Flag` | X; E |


---

# FAOSTAT_A-S_E__Population_E_All_Data_(Normalized)__Population_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Population_E_All_Data_(Normalized)/Population_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 282 |
| Columns | 3 |
| File created | 2026-07-05T03:44:16.215206+00:00 |
| File last modified | 2026-07-05T03:52:41.948785+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Population_E_All_Data_(Normalized)__Population_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Population_E_All_Data_(Normalized)/Population_E_Elements.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:16.234004+00:00 |
| File last modified | 2026-07-05T03:52:41.951784+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 551; 511; 513 |
| `Element` | Rural population; Total Population - Both sexes; Total Population - Female |


---

# FAOSTAT_A-S_E__Population_E_All_Data_(Normalized)__Population_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Population_E_All_Data_(Normalized)/Population_E_Flags.parquet |
| Format | parquet |
| File size | 996.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:44:16.241948+00:00 |
| File last modified | 2026-07-05T03:52:41.956783+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E; X |
| ` Description` | Estimated value; Figure from external organization |


---

# FAOSTAT_A-S_E__Population_E_All_Data_(Normalized)__Population_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Population_E_All_Data_(Normalized)/Population_E_ItemCodes.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:16.257720+00:00 |
| File last modified | 2026-07-05T03:52:41.959782+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 3010 |
| `Item` | Population - Est. & Proj. |


---

# FAOSTAT_A-S_E__Prices_E_All_Data_(Normalized)__Prices_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Prices_E_All_Data_(Normalized)/Prices_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 4.0MB |
| Rows | 1,319,563 |
| Columns | 15 |
| File created | 2026-07-05T03:44:16.357966+00:00 |
| File last modified | 2026-07-05T03:52:42.458354+00:00 |
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
| `Months Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Months` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 221; 711; 515 |
| `Item Code (CPC)` | '01371; '01654; '01341 |
| `Item` | Almonds, in shell; Anise, badian, coriander, cumin, caraway, fennel and juniper berries, raw; Apples |
| `Element Code` | 5530; 5531; 5539 |
| `Element` | Producer Price (LCU/tonne); Producer Price (SLC/tonne); Producer Price Index (2014-2016 = 100) |
| `Year Code` | 1993; 1994; 1995 |
| `Year` | 1993; 1994; 1995 |
| `Months Code` | 7021; 7007; 7008 |
| `Months` | Annual value; July; August |
| `Unit` | LCU; SLC;  |
| `Value` | 46000.0; 50000.0; 62000.0 |
| `Flag` | A; E; X |


---

# FAOSTAT_A-S_E__Prices_E_All_Data_(Normalized)__Prices_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Prices_E_All_Data_(Normalized)/Prices_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.9KB |
| Rows | 233 |
| Columns | 3 |
| File created | 2026-07-05T03:44:17.116033+00:00 |
| File last modified | 2026-07-05T03:52:42.462354+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Prices_E_All_Data_(Normalized)__Prices_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Prices_E_All_Data_(Normalized)/Prices_E_Elements.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:17.139044+00:00 |
| File last modified | 2026-07-05T03:52:42.465354+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 5530; 5531; 5532 |
| `Element` | Producer Price (LCU/tonne); Producer Price (SLC/tonne); Producer Price (USD/tonne) |


---

# FAOSTAT_A-S_E__Prices_E_All_Data_(Normalized)__Prices_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Prices_E_All_Data_(Normalized)/Prices_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:17.146582+00:00 |
| File last modified | 2026-07-05T03:52:42.467355+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; B; E |
| ` Description` | Official figure; Time series break; Estimated value |


---

# FAOSTAT_A-S_E__Prices_E_All_Data_(Normalized)__Prices_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Prices_E_All_Data_(Normalized)/Prices_E_ItemCodes.parquet |
| Format | parquet |
| File size | 5.0KB |
| Rows | 242 |
| Columns | 3 |
| File created | 2026-07-05T03:44:17.165579+00:00 |
| File last modified | 2026-07-05T03:52:42.471356+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 809; 800; 2051 |
| `CPC Code` | '01929.07; '01929.06; 'F2051 |
| `Item` | Abaca; manila hemp; raw; Agave fibres; raw; n.e.c.; Agriculture |


---

# FAOSTAT_A-S_E__PricesArchive_E_All_Data_(Normalized)__PricesArchive_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/PricesArchive_E_All_Data_(Normalized)/PricesArchive_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 376.5KB |
| Rows | 139,713 |
| Columns | 13 |
| File created | 2026-07-05T03:44:17.250997+00:00 |
| File last modified | 2026-07-05T03:52:42.570848+00:00 |
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
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 4; 9; 10 |
| `Area Code (M49)` | '012; '032; '036 |
| `Area` | Algeria; Argentina; Australia |
| `Item Code` | 221; 515; 526 |
| `Item Code (CPC)` | '01371; '01341; '01343 |
| `Item` | Almonds, in shell; Apples; Apricots |
| `Element Code` | 5530 |
| `Element` | Producer Price (LCU/tonne) |
| `Year Code` | 1966; 1967; 1968 |
| `Year` | 1966; 1967; 1968 |
| `Unit` | LCU |
| `Value` | 1150.0; 1140.0; 1210.0 |
| `Flag` | E; A |


---

# FAOSTAT_A-S_E__PricesArchive_E_All_Data_(Normalized)__PricesArchive_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/PricesArchive_E_All_Data_(Normalized)/PricesArchive_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.4KB |
| Rows | 185 |
| Columns | 3 |
| File created | 2026-07-05T03:44:17.384025+00:00 |
| File last modified | 2026-07-05T03:52:42.573984+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__PricesArchive_E_All_Data_(Normalized)__PricesArchive_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/PricesArchive_E_All_Data_(Normalized)/PricesArchive_E_Elements.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:17.395166+00:00 |
| File last modified | 2026-07-05T03:52:42.576993+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 5530 |
| `Element` | Producer Price (LCU/tonne) |


---

# FAOSTAT_A-S_E__PricesArchive_E_All_Data_(Normalized)__PricesArchive_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/PricesArchive_E_All_Data_(Normalized)/PricesArchive_E_Flags.parquet |
| Format | parquet |
| File size | 905.0B |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:44:17.408260+00:00 |
| File last modified | 2026-07-05T03:52:42.578992+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E |
| ` Description` | Official figure; Estimated value |


---

# FAOSTAT_A-S_E__PricesArchive_E_All_Data_(Normalized)__PricesArchive_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/PricesArchive_E_All_Data_(Normalized)/PricesArchive_E_ItemCodes.parquet |
| Format | parquet |
| File size | 4.9KB |
| Rows | 236 |
| Columns | 3 |
| File created | 2026-07-05T03:44:17.428118+00:00 |
| File last modified | 2026-07-05T03:52:42.581992+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 809; 800; 221 |
| `CPC Code` | '01929.07; '01929.06; '01371 |
| `Item` | Abaca; manila hemp; raw; Agave fibres; raw; n.e.c.; Almonds; in shell |


---

# FAOSTAT_A-S_E__Production_Crops_Livestock_E_All_Data_(Normalized)__Production_Crops_Livestock_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Production_Crops_Livestock_E_All_Data_(Normalized)/Production_Crops_Livestock_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 12.4MB |
| Rows | 4,209,110 |
| Columns | 14 |
| File created | 2026-07-05T03:44:17.518293+00:00 |
| File last modified | 2026-07-05T03:52:43.926515+00:00 |
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
| `Value` | Float64 | Numeric | Yes | 94,355 | 2.24% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 4,125,820 | 98.02% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 221; 711; 515 |
| `Item Code (CPC)` | '01371; '01654; '01341 |
| `Item` | Almonds, in shell; Anise, badian, coriander, cumin, caraway, fennel and juniper berries, raw; Apples |
| `Element Code` | 5312; 5412; 5510 |
| `Element` | Area harvested; Yield; Production |
| `Year Code` | 1961; 1962; 1963 |
| `Year` | 1961; 1962; 1963 |
| `Unit` | ha; kg/ha; t |
| `Value` | 0.0; 5900.0; 6000.0 |
| `Flag` | A; E; X |
| `Note` | Unofficial figure |


---

# FAOSTAT_A-S_E__Production_Crops_Livestock_E_All_Data_(Normalized)__Production_Crops_Livestock_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Production_Crops_Livestock_E_All_Data_(Normalized)/Production_Crops_Livestock_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.1KB |
| Rows | 244 |
| Columns | 3 |
| File created | 2026-07-05T03:44:19.818138+00:00 |
| File last modified | 2026-07-05T03:52:43.942515+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Production_Crops_Livestock_E_All_Data_(Normalized)__Production_Crops_Livestock_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Production_Crops_Livestock_E_All_Data_(Normalized)/Production_Crops_Livestock_E_Elements.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 20 |
| Columns | 2 |
| File created | 2026-07-05T03:44:19.861138+00:00 |
| File last modified | 2026-07-05T03:52:43.946518+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 5312; 5423; 5313 |
| `Element` | Area harvested; Extraction Rate; Laying |


---

# FAOSTAT_A-S_E__Production_Crops_Livestock_E_All_Data_(Normalized)__Production_Crops_Livestock_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Production_Crops_Livestock_E_All_Data_(Normalized)/Production_Crops_Livestock_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:19.869138+00:00 |
| File last modified | 2026-07-05T03:52:43.950516+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__Production_Crops_Livestock_E_All_Data_(Normalized)__Production_Crops_Livestock_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Production_Crops_Livestock_E_All_Data_(Normalized)/Production_Crops_Livestock_E_ItemCodes.parquet |
| Format | parquet |
| File size | 5.9KB |
| Rows | 312 |
| Columns | 3 |
| File created | 2026-07-05T03:44:19.897652+00:00 |
| File last modified | 2026-07-05T03:52:43.957516+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | Yes | 5 | 1.6% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 809; 800; 221 |
| `CPC Code` | '01929.07; '01929.06; '01371 |
| `Item` | Abaca; manila hemp; raw; Agave fibres; raw; n.e.c.; Almonds; in shell |


---

# FAOSTAT_A-S_E__Production_Indices_E_All_Data_(Normalized)__Production_Indices_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Production_Indices_E_All_Data_(Normalized)/Production_Indices_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 6.0MB |
| Rows | 1,995,192 |
| Columns | 13 |
| File created | 2026-07-05T03:44:20.004015+00:00 |
| File last modified | 2026-07-05T03:52:45.018580+00:00 |
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
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 221; 711; 515 |
| `Item Code (CPC)` | '01371; '01654; '01341 |
| `Item` | Almonds, in shell; Anise, badian, coriander, cumin, caraway, fennel and juniper berries, raw; Apples |
| `Element Code` | 432; 434 |
| `Element` | Gross Production Index Number (2014-2016 = 100); Gross per capita Production Index Number (2014-2016 = 100) |
| `Year Code` | 1976; 1977; 1978 |
| `Year` | 1976; 1977; 1978 |
| `Unit` |  |
| `Value` | 34.8; 31.96; 42.61 |
| `Flag` | E |


---

# FAOSTAT_A-S_E__Production_Indices_E_All_Data_(Normalized)__Production_Indices_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Production_Indices_E_All_Data_(Normalized)/Production_Indices_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.1KB |
| Rows | 245 |
| Columns | 3 |
| File created | 2026-07-05T03:44:21.073020+00:00 |
| File last modified | 2026-07-05T03:52:45.026732+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Production_Indices_E_All_Data_(Normalized)__Production_Indices_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Production_Indices_E_All_Data_(Normalized)/Production_Indices_E_Elements.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 2 |
| Columns | 2 |
| File created | 2026-07-05T03:44:21.088033+00:00 |
| File last modified | 2026-07-05T03:52:45.033728+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 434; 432 |
| `Element` | Gross per capita Production Index Number (2014-2016 = 100); Gross Production Index Number (2014-2016 = 100) |


---

# FAOSTAT_A-S_E__Production_Indices_E_All_Data_(Normalized)__Production_Indices_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Production_Indices_E_All_Data_(Normalized)/Production_Indices_E_Flags.parquet |
| Format | parquet |
| File size | 879.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:21.094376+00:00 |
| File last modified | 2026-07-05T03:52:45.037730+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E |
| ` Description` | Estimated value |


---

# FAOSTAT_A-S_E__Production_Indices_E_All_Data_(Normalized)__Production_Indices_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Production_Indices_E_All_Data_(Normalized)/Production_Indices_E_ItemCodes.parquet |
| Format | parquet |
| File size | 4.5KB |
| Rows | 204 |
| Columns | 3 |
| File created | 2026-07-05T03:44:21.113599+00:00 |
| File last modified | 2026-07-05T03:52:45.043840+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 809; 800; 2051 |
| `CPC Code` | '01929.07; '01929.06; 'F2051 |
| `Item` | Abaca; manila hemp; raw; Agave fibres; raw; n.e.c.; Agriculture |


---

# FAOSTAT_A-S_E__Rural_Livelihoods_Indicators_E_All_Data_(Normalized)__Rural_Livelihoods_Indicators_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Rural_Livelihoods_Indicators_E_All_Data_(Normalized)/Rural_Livelihoods_Indicators_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 141.7KB |
| Rows | 38,918 |
| Columns | 14 |
| File created | 2026-07-05T03:44:21.195838+00:00 |
| File last modified | 2026-07-05T03:52:45.188952+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Survey Code` | String | Categorical | No | 0 | 0.0% |
| `Survey` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Qualifier Code` | String | Categorical | No | 0 | 0.0% |
| `Qualifier` | String | Categorical | No | 0 | 0.0% |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Survey Code` | 008_2005; 051_2010; 051_2012 |
| `Survey` | Albania - 2005; Armenia - 2010; Armenia - 2012 |
| `Indicator Code` | 24239; 24241; 24242 |
| `Indicator` | Agricultural income (livestock, crop, fishery, forestry, ag wage), share of t...; Agricultural wage, share of total income (%); Average annual income from agriculture, PPP (constant 2011 international USD) |
| `Element Code` | 60784; 6121; 60788 |
| `Element` | Standard Deviation; Value |
| `Qualifier Code` | N; MH; NSF |
| `Qualifier` | National; Male-headed household; Non small-scale food producers |
| `Source Code` | 3054; 3055; 3052 |
| `Source` | Household level; Individual level; Community level |
| `Unit` | %; Int$;  |
| `Value` | 29.1; 20.0; 59.099998 |
| `Flag` | E |
| `Note` | 2005; 2010; 2011 |


---

# FAOSTAT_A-S_E__Rural_Livelihoods_Indicators_E_All_Data_(Normalized)__Rural_Livelihoods_Indicators_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Rural_Livelihoods_Indicators_E_All_Data_(Normalized)/Rural_Livelihoods_Indicators_E_Elements.parquet |
| Format | parquet |
| File size | 1004.0B |
| Rows | 13 |
| Columns | 2 |
| File created | 2026-07-05T03:44:21.258963+00:00 |
| File last modified | 2026-07-05T03:52:45.196883+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 60784; 60786; 60787 |
| `Element` | Standard Deviation; Value |


---

# FAOSTAT_A-S_E__Rural_Livelihoods_Indicators_E_All_Data_(Normalized)__Rural_Livelihoods_Indicators_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Rural_Livelihoods_Indicators_E_All_Data_(Normalized)/Rural_Livelihoods_Indicators_E_Flags.parquet |
| Format | parquet |
| File size | 879.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:21.272049+00:00 |
| File last modified | 2026-07-05T03:52:45.201870+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | E |
| ` Description` | Estimated value |


---

# FAOSTAT_A-S_E__Rural_Livelihoods_Indicators_E_All_Data_(Normalized)__Rural_Livelihoods_Indicators_E_Indicators

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Rural_Livelihoods_Indicators_E_All_Data_(Normalized)/Rural_Livelihoods_Indicators_E_Indicators.parquet |
| Format | parquet |
| File size | 4.3KB |
| Rows | 143 |
| Columns | 2 |
| File created | 2026-07-05T03:44:21.290699+00:00 |
| File last modified | 2026-07-05T03:52:45.207963+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Indicator Code` | 24201; 24239; 24240 |
| `Indicator` | Adult literacy rate; ages 15+ (%); Agricultural income (livestock; crop; fishery; forestry; ag wage); share of t...; Agricultural output per labour day; PPP (constant 2011 international USD) |


---

# FAOSTAT_A-S_E__Rural_Livelihoods_Indicators_E_All_Data_(Normalized)__Rural_Livelihoods_Indicators_E_Qualifiers

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Rural_Livelihoods_Indicators_E_All_Data_(Normalized)/Rural_Livelihoods_Indicators_E_Qualifiers.parquet |
| Format | parquet |
| File size | 970.0B |
| Rows | 9 |
| Columns | 2 |
| File created | 2026-07-05T03:44:21.302921+00:00 |
| File last modified | 2026-07-05T03:52:45.213965+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Qualifier Code` | String | Categorical | No | 0 | 0.0% |
| `Qualifier` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Qualifier Code` | F; FH; M |
| `Qualifier` | Female; Female-headed household; Male |


---

# FAOSTAT_A-S_E__Rural_Livelihoods_Indicators_E_All_Data_(Normalized)__Rural_Livelihoods_Indicators_E_Sources

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Rural_Livelihoods_Indicators_E_All_Data_(Normalized)/Rural_Livelihoods_Indicators_E_Sources.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:21.318924+00:00 |
| File last modified | 2026-07-05T03:52:45.219960+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Source Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Source` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Source Code` | 3010; 3052; 3053 |
| `Source` | All sources; Community level; External |


---

# FAOSTAT_A-S_E__Rural_Livelihoods_Indicators_E_All_Data_(Normalized)__Rural_Livelihoods_Indicators_E_Surveys

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Rural_Livelihoods_Indicators_E_All_Data_(Normalized)/Rural_Livelihoods_Indicators_E_Surveys.parquet |
| Format | parquet |
| File size | 2.0KB |
| Rows | 103 |
| Columns | 2 |
| File created | 2026-07-05T03:44:21.339326+00:00 |
| File last modified | 2026-07-05T03:52:45.227089+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Survey Code` | String | Categorical | No | 0 | 0.0% |
| `Survey` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Survey Code` | 008_2005; 051_2010; 051_2012 |
| `Survey` | Albania - 2005; Armenia - 2010; Armenia - 2012 |


---

# FAOSTAT_A-S_E__SDG_BulkDownloads_E_All_Data_(Normalized)__SDG_BulkDownloads_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/SDG_BulkDownloads_E_All_Data_(Normalized)/SDG_BulkDownloads_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 888.2KB |
| Rows | 464,787 |
| Columns | 14 |
| File created | 2026-07-05T03:44:21.451282+00:00 |
| File last modified | 2026-07-05T03:52:45.718809+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `Item Code (SDG)` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | String | Categorical | Yes | 169,806 | 36.53% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 284; 3 |
| `Area Code (M49)` | '004; '248; '008 |
| `Area` | Afghanistan; Åland Islands; Albania |
| `Item Code` | 24001; 24000; 24004-F-Y_GE15 |
| `Item Code (SDG)` | SN_ITK_DEFCN; SN_ITK_DEFC; AG_PRD_FIESSN-F-Y_GE15 |
| `Item` | 2.1.1 Number of undernourished people; 2.1.1 Prevalence of undernourishment; 2.1.2 Number of severely food insecure people (female) (15 years old and over) |
| `Element Code` | 6132; 6121; 6199 |
| `Element` | Value; Confidence interval: Lower bound; Confidence interval: Upper bound |
| `Year Code` | 2001; 2002; 2003 |
| `Year` | 2001; 2002; 2003 |
| `Unit` | million No; %; 1000 No |
| `Value` | 9.4; 9.3; 8.7 |
| `Flag` | E; O; A |
| `Note` | Estimated | Food and Agriculture Organization of the United Nations (FAO) | 3...; Estimated | Food and Agriculture Organization of the United Nations (FAO) | 3...; Estimated | Food and Agriculture Organization of the United Nations (FAO) | 3... |


---

# FAOSTAT_A-S_E__SDG_BulkDownloads_E_All_Data_(Normalized)__SDG_BulkDownloads_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/SDG_BulkDownloads_E_All_Data_(Normalized)/SDG_BulkDownloads_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.8KB |
| Rows | 305 |
| Columns | 3 |
| File created | 2026-07-05T03:44:21.815173+00:00 |
| File last modified | 2026-07-05T03:52:45.728412+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 284 |
| `M49 Code` | '004; '002; '248 |
| `Area` | Afghanistan; Africa; Åland Islands |


---

# FAOSTAT_A-S_E__SDG_BulkDownloads_E_All_Data_(Normalized)__SDG_BulkDownloads_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/SDG_BulkDownloads_E_All_Data_(Normalized)/SDG_BulkDownloads_E_Elements.parquet |
| Format | parquet |
| File size | 1.2KB |
| Rows | 16 |
| Columns | 2 |
| File created | 2026-07-05T03:44:21.829153+00:00 |
| File last modified | 2026-07-05T03:52:45.733394+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 61991; 61211; 61212 |
| `Element` | Confidence interval: Lower bound; Confidence interval: Upper bound; Value |


---

# FAOSTAT_A-S_E__SDG_BulkDownloads_E_All_Data_(Normalized)__SDG_BulkDownloads_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/SDG_BulkDownloads_E_All_Data_(Normalized)/SDG_BulkDownloads_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 7 |
| Columns | 2 |
| File created | 2026-07-05T03:44:21.843169+00:00 |
| File last modified | 2026-07-05T03:52:45.740958+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# FAOSTAT_A-S_E__SDG_BulkDownloads_E_All_Data_(Normalized)__SDG_BulkDownloads_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/SDG_BulkDownloads_E_All_Data_(Normalized)/SDG_BulkDownloads_E_ItemCodes.parquet |
| Format | parquet |
| File size | 6.5KB |
| Rows | 279 |
| Columns | 3 |
| File created | 2026-07-05T03:44:21.864148+00:00 |
| File last modified | 2026-07-05T03:52:45.745987+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `SDG Code` | String | Categorical | Yes | 5 | 1.79% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 24044; 24044-AGGS3001; 24044-AGGS3002 |
| `SDG Code` | 'AG_FLS_IDX; 'AG_FLS_PCT-CPC2_1_AGGS3001; 'AG_FLS_PCT-CPC2_1_AGGS3002 |
| `Item` | 12.3.1a Food loss percentage; 12.3.1a Food loss percentage: cereals and pulses; 12.3.1a Food loss percentage: fruits and vegetables |


---

# FAOSTAT_A-S_E__SUA_Crops_Livestock_E_All_Data_(Normalized)__SUA_Crops_Livestock_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/SUA_Crops_Livestock_E_All_Data_(Normalized)/SUA_Crops_Livestock_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 32.6MB |
| Rows | 11,615,212 |
| Columns | 14 |
| File created | 2026-07-05T03:44:21.978635+00:00 |
| File last modified | 2026-07-05T03:52:51.186732+00:00 |
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
| `Value` | Float64 | Numeric | Yes | 33,976 | 0.29% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 7,054,040 | 60.73% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Item Code` | 221; 231; 1168 |
| `Item Code (CPC)` | '01371; '21422; '21529.03 |
| `Item` | Almonds, in shell; Almonds, shelled; Animal oils and fats n.e.c. |
| `Element Code` | 5113; 5510; 5610 |
| `Element` | Opening stocks; Production; Import quantity |
| `Year Code` | 2010; 2011; 2012 |
| `Year` | 2010; 2011; 2012 |
| `Unit` | t; kcal/cap/d; g/cap/d |
| `Value` | 6720.01; 7088.85; 7440.35 |
| `Flag` | E; I; A |
| `Note` | Estimated data using trading partners database; Unofficial figure |


---

# FAOSTAT_A-S_E__SUA_Crops_Livestock_E_All_Data_(Normalized)__SUA_Crops_Livestock_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/SUA_Crops_Livestock_E_All_Data_(Normalized)/SUA_Crops_Livestock_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.7KB |
| Rows | 213 |
| Columns | 3 |
| File created | 2026-07-05T03:44:28.302946+00:00 |
| File last modified | 2026-07-05T03:52:51.204730+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__SUA_Crops_Livestock_E_All_Data_(Normalized)__SUA_Crops_Livestock_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/SUA_Crops_Livestock_E_All_Data_(Normalized)/SUA_Crops_Livestock_E_Elements.parquet |
| Format | parquet |
| File size | 1.3KB |
| Rows | 21 |
| Columns | 2 |
| File created | 2026-07-05T03:44:28.322957+00:00 |
| File last modified | 2026-07-05T03:52:51.211743+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 261; 5910; 684 |
| `Element` | Calories/Year; Export quantity; Fat supply quantity (g/capita/day) |


---

# FAOSTAT_A-S_E__SUA_Crops_Livestock_E_All_Data_(Normalized)__SUA_Crops_Livestock_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/SUA_Crops_Livestock_E_All_Data_(Normalized)/SUA_Crops_Livestock_E_Flags.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 6 |
| Columns | 2 |
| File created | 2026-07-05T03:44:28.337165+00:00 |
| File last modified | 2026-07-05T03:52:51.216745+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; F |
| ` Description` | Official figure; Estimated value; Forecast value |


---

# FAOSTAT_A-S_E__SUA_Crops_Livestock_E_All_Data_(Normalized)__SUA_Crops_Livestock_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/SUA_Crops_Livestock_E_All_Data_(Normalized)/SUA_Crops_Livestock_E_ItemCodes.parquet |
| Format | parquet |
| File size | 8.5KB |
| Rows | 485 |
| Columns | 3 |
| File created | 2026-07-05T03:44:28.358270+00:00 |
| File last modified | 2026-07-05T03:52:51.224747+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | Yes | 4 | 0.82% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 221; 231; 1168 |
| `CPC Code` | '01371; '21422; '21529.03 |
| `Item` | Almonds; in shell; Almonds; shelled; Animal oils and fats n.e.c. |


---

# FAOSTAT_A-S_E__Suite_of_gender_indicators_E_All_Data_(Normalized)__Suite_of_gender_indicators_E_Activities

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Suite_of_gender_indicators_E_All_Data_(Normalized)/Suite_of_gender_indicators_E_Activities.parquet |
| Format | parquet |
| File size | 1000.0B |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:28.386292+00:00 |
| File last modified | 2026-07-05T03:52:51.231020+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Activity Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Activity` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Activity Code` | 3; 2; 10 |
| `Activity` | Agriculture; Agrifood systems; All activities |


---

# FAOSTAT_A-S_E__Suite_of_gender_indicators_E_All_Data_(Normalized)__Suite_of_gender_indicators_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Suite_of_gender_indicators_E_All_Data_(Normalized)/Suite_of_gender_indicators_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 991.3KB |
| Rows | 315,014 |
| Columns | 24 |
| File created | 2026-07-05T03:44:28.547790+00:00 |
| File last modified | 2026-07-05T03:52:51.893059+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `Item Code (SDG)` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Sex Code (SDG)` | String | Categorical | No | 0 | 0.0% |
| `Sex` | String | Categorical | No | 0 | 0.0% |
| `Population Age Group Code` | String | Categorical | No | 0 | 0.0% |
| `Population Age Group` | String | Categorical | No | 0 | 0.0% |
| `Geographic Level Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Geographic Level` | String | Categorical | No | 0 | 0.0% |
| `Activity Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Activity Code (SDG)` | String | Categorical | No | 0 | 0.0% |
| `Activity` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | Yes | 28,494 | 9.05% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 284; 3 |
| `Area Code (M49)` | '004; '248; '008 |
| `Area` | Afghanistan; Åland Islands; Albania |
| `Item Code` | 24064_A; 24064_N; 24064_T |
| `Item Code (SDG)` | EMPL_SEX_AFS_A; EMPL_SEX_AFS_N; EMPL_SEX_AFS_T |
| `Item` | Employment in agrifood systems by subindustry and sex: Agriculture; Employment in agrifood systems by subindustry and sex: Off-farm agrifood systems; Employment in agrifood systems by subindustry and sex: Total |
| `Element Code` | 6199; 6121; 6204 |
| `Element` | Value; Value (2017 constant prices) |
| `Sex Code` | 1; 2; 3 |
| `Sex Code (SDG)` | _T; M; F |
| `Sex` | Total; Male; Female |
| `Population Age Group Code` | Y_T; Y_GE10; Y_GE65 |
| `Population Age Group` | All age ranges or no breakdown by age; 10 years old and over; 65 years old and over |
| `Geographic Level Code` | 10000; 10002; 10001 |
| `Geographic Level` | National; Rural; Urban |
| `Activity Code` | 3; 4; 2 |
| `Activity Code (SDG)` | AGR; NON_AGR_AFS; AFS |
| `Activity` | Agriculture; Non-agricultural agrifood systems; Agrifood systems |
| `Year Code` | 2000; 2001; 2002 |
| `Year` | 2000; 2001; 2002 |
| `Unit` | 1000 No; %; Score |
| `Value` | 2737.43; 2792.49; 2852.68 |
| `Flag` | X; E; O |
| `Note` | Source: ILOStat modelled estimates; Source: Estimated by FAO; Source: Modelled based on average change in AFS from previous year in Africa |


---

# FAOSTAT_A-S_E__Suite_of_gender_indicators_E_All_Data_(Normalized)__Suite_of_gender_indicators_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Suite_of_gender_indicators_E_All_Data_(Normalized)/Suite_of_gender_indicators_E_AreaCodes.parquet |
| Format | parquet |
| File size | 4.6KB |
| Rows | 278 |
| Columns | 3 |
| File created | 2026-07-05T03:44:29.072923+00:00 |
| File last modified | 2026-07-05T03:52:51.900042+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 5100; 284 |
| `M49 Code` | '004; '002; '248 |
| `Area` | Afghanistan; Africa; Åland Islands |


---

# FAOSTAT_A-S_E__Suite_of_gender_indicators_E_All_Data_(Normalized)__Suite_of_gender_indicators_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Suite_of_gender_indicators_E_All_Data_(Normalized)/Suite_of_gender_indicators_E_Elements.parquet |
| Format | parquet |
| File size | 1023.0B |
| Rows | 6 |
| Columns | 2 |
| File created | 2026-07-05T03:44:29.086373+00:00 |
| File last modified | 2026-07-05T03:52:51.904731+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 6121; 6173; 6199 |
| `Element` | Value; Value (2017 constant prices) |


---

# FAOSTAT_A-S_E__Suite_of_gender_indicators_E_All_Data_(Normalized)__Suite_of_gender_indicators_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Suite_of_gender_indicators_E_All_Data_(Normalized)/Suite_of_gender_indicators_E_Flags.parquet |
| Format | parquet |
| File size | 982.0B |
| Rows | 5 |
| Columns | 2 |
| File created | 2026-07-05T03:44:29.093868+00:00 |
| File last modified | 2026-07-05T03:52:51.907731+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; O |
| ` Description` | Official figure; Estimated value; Missing value |


---

# FAOSTAT_A-S_E__Suite_of_gender_indicators_E_All_Data_(Normalized)__Suite_of_gender_indicators_E_GeographicLevels

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Suite_of_gender_indicators_E_All_Data_(Normalized)/Suite_of_gender_indicators_E_GeographicLevels.parquet |
| Format | parquet |
| File size | 1.1KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:29.108462+00:00 |
| File last modified | 2026-07-05T03:52:51.911730+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Geographic Level Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Geographic Level` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Geographic Level Code` | 100000; 10000; 10002 |
| `Geographic Level` | All geographic levels; National; Rural |


---

# FAOSTAT_A-S_E__Suite_of_gender_indicators_E_All_Data_(Normalized)__Suite_of_gender_indicators_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Suite_of_gender_indicators_E_All_Data_(Normalized)/Suite_of_gender_indicators_E_ItemCodes.parquet |
| Format | parquet |
| File size | 4.7KB |
| Rows | 146 |
| Columns | 3 |
| File created | 2026-07-05T03:44:29.125612+00:00 |
| File last modified | 2026-07-05T03:52:51.916131+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | String | Categorical | No | 0 | 0.0% |
| `SDG Code` | String | Categorical | Yes | 23 | 15.75% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 24002-YGE15T; 24003-YGE15T; 24015 |
| `SDG Code` | 'PD_AGR_LSFP; 'PD_AGR_SSFP; 'SI_AGR_LSFP |
| `Item` | 2.1.2 Prevalence of moderate or severe food insecurity (15 years old and over...; 2.1.2 Prevalence of severe food insecurity (15 years old and over) (no breakd...; 2.3.1 Productivity of large-scale food producers (2017 base period) |


---

# FAOSTAT_A-S_E__Suite_of_gender_indicators_E_All_Data_(Normalized)__Suite_of_gender_indicators_E_PopulationAgeGroups

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Suite_of_gender_indicators_E_All_Data_(Normalized)/Suite_of_gender_indicators_E_PopulationAgeGroups.parquet |
| Format | parquet |
| File size | 1.6KB |
| Rows | 40 |
| Columns | 2 |
| File created | 2026-07-05T03:44:29.149357+00:00 |
| File last modified | 2026-07-05T03:52:51.919130+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Population Age Group Code` | String | Categorical | No | 0 | 0.0% |
| `Population Age Group` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Population Age Group Code` | Y10T14; Y_GE10; Y12T14 |
| `Population Age Group` | 10 to 14 years old; 10 years old and over; 12 to 14 years old |


---

# FAOSTAT_A-S_E__Suite_of_gender_indicators_E_All_Data_(Normalized)__Suite_of_gender_indicators_E_Sexes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Suite_of_gender_indicators_E_All_Data_(Normalized)/Suite_of_gender_indicators_E_Sexes.parquet |
| Format | parquet |
| File size | 892.0B |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:29.172322+00:00 |
| File last modified | 2026-07-05T03:52:51.925525+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Sex Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Sex` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Sex Code` | 3; 2; 6 |
| `Sex` | Female; Male; Not available |


---

# FAOSTAT_A-S_E__Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)__Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)/Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized).parquet |
| Format | parquet |
| File size | 1.0MB |
| Rows | 743,139 |
| Columns | 15 |
| File created | 2026-07-05T03:44:29.276287+00:00 |
| File last modified | 2026-07-05T03:52:52.366731+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Area Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Area` | String | Categorical | No | 0 | 0.0% |
| `Food Group Code` | String | Categorical | No | 0 | 0.0% |
| `Food Group` | String | Categorical | No | 0 | 0.0% |
| `Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Indicator` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Year Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Value` | Float64 | Numeric | No | 0 | 0.0% |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| `Note` | String | Categorical | Yes | 720,099 | 96.9% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Area Code` | 2; 3; 4 |
| `Area Code (M49)` | '004; '008; '012 |
| `Area` | Afghanistan; Albania; Algeria |
| `Food Group Code` | FG0; FGD; FG1 |
| `Food Group` | All food groups; All food groups (excluding beverages); Cereals and their products |
| `Indicator Code` | 4003; 4004; 4005 |
| `Indicator` | Energy supply; Protein supply; Fat supply |
| `Element Code` | 6128; 6123; 6209 |
| `Element` | Value |
| `Year Code` | 2010; 2011; 2012 |
| `Year` | 2010; 2011; 2012 |
| `Unit` | kcal/cap/d; g/cap/d; mg/cap/d |
| `Value` | 2200.0; 2172.0; 2166.0 |
| `Flag` | E |
| `Note` | Data correspond only to other aquatic animal products.; Data correspond only to fish oil products.; Data correspond only to algae products. |


---

# FAOSTAT_A-S_E__Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)__Supply_Utilization_Accounts_Food_and_Diet_E_AreaCodes

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)/Supply_Utilization_Accounts_Food_and_Diet_E_AreaCodes.parquet |
| Format | parquet |
| File size | 3.7KB |
| Rows | 213 |
| Columns | 3 |
| File created | 2026-07-05T03:44:29.758849+00:00 |
| File last modified | 2026-07-05T03:52:52.380539+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Area Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` M49 Code` | String | Categorical | No | 0 | 0.0% |
| ` Area` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Area Code` | 2; 5100; 3 |
| ` M49 Code` | '004; '002; '008 |
| ` Area` | Afghanistan; Africa; Albania |


---

# FAOSTAT_A-S_E__Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)__Supply_Utilization_Accounts_Food_and_Diet_E_Elements

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)/Supply_Utilization_Accounts_Food_and_Diet_E_Elements.parquet |
| Format | parquet |
| File size | 904.0B |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T03:44:29.772567+00:00 |
| File last modified | 2026-07-05T03:52:52.385541+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Element Code` | 6123; 6128; 6206 |
| ` Element` | Value |


---

# FAOSTAT_A-S_E__Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)__Supply_Utilization_Accounts_Food_and_Diet_E_Flags

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)/Supply_Utilization_Accounts_Food_and_Diet_E_Flags.parquet |
| Format | parquet |
| File size | 882.0B |
| Rows | 1 |
| Columns | 2 |
| File created | 2026-07-05T03:44:29.779516+00:00 |
| File last modified | 2026-07-05T03:52:52.393535+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Flag` | E |
| ` Description` | Estimated value |


---

# FAOSTAT_A-S_E__Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)__Supply_Utilization_Accounts_Food_and_Diet_E_Indicators

| Field | Value |
| --- | --- |
| File path | FAOSTAT_A-S_E/Supply_Utilization_Accounts_Food_and_Diet_E_All_Data_(Normalized)/Supply_Utilization_Accounts_Food_and_Diet_E_Indicators.parquet |
| Format | parquet |
| File size | 1.5KB |
| Rows | 26 |
| Columns | 2 |
| File created | 2026-07-05T03:44:29.792822+00:00 |
| File last modified | 2026-07-05T03:52:52.399539+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| ` Indicator Code` | Int64 | Numeric | No | 0 | 0.0% |
| ` Indicator` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| ` Indicator Code` | 4040; 4009; 4006 |
| ` Indicator` | Additional nutrients for aquatic foods; Calcium supply; Carbohydrate (available) supply |


---

# nasa_power_data___ALL_COUNTRIES_weather

| Field | Value |
| --- | --- |
| File path | nasa_power_data/_ALL_COUNTRIES_weather.parquet |
| Format | parquet |
| File size | 337.7KB |
| Rows | 76,440 |
| Columns | 8 |
| File created | 2026-07-05T14:04:17.835222+00:00 |
| File last modified | 2026-07-05T14:04:17.846313+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `country_iso2` | String | Categorical | No | 0 | 0.0% |
| `country_name` | String | Categorical | No | 0 | 0.0% |
| `latitude` | Float64 | Numeric | No | 0 | 0.0% |
| `longitude` | Float64 | Numeric | No | 0 | 0.0% |
| `year` | Int64 | Numeric | No | 0 | 0.0% |
| `month` | Int64 | Numeric | No | 0 | 0.0% |
| `temp_c` | Float64 | Numeric | No | 0 | 0.0% |
| `precip_mm_day` | Float64 | Numeric | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `country_iso2` | AD; AE; AF |
| `country_name` | Andorra; United Arab Emirates; Afghanistan |
| `latitude` | 42.546245; 23.424076; 33.93911 |
| `longitude` | 1.601554; 53.847818; 67.709953 |
| `year` | 2000; 2001; 2002 |
| `month` | 1; 2; 3 |
| `temp_c` | -3.52; 1.0; 1.15 |
| `precip_mm_day` | 0.41; 1.29; 1.38 |


---

# public_emdat_incl_hist_2026-06-29__EM-DAT_Data

| Field | Value |
| --- | --- |
| File path | public_emdat_incl_hist_2026-06-29/EM-DAT_Data.parquet |
| Format | parquet |
| File size | 4.3MB |
| Rows | 27,681 |
| Columns | 47 |
| File created | 2026-07-05T13:24:22.372851+00:00 |
| File last modified | 2026-07-05T13:24:22.468935+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `DisNo.` | String | Categorical | No | 0 | 0.0% |
| `Historic` | String | Categorical | No | 0 | 0.0% |
| `Classification Key` | String | Categorical | No | 0 | 0.0% |
| `Disaster Group` | String | Categorical | No | 0 | 0.0% |
| `Disaster Subgroup` | String | Categorical | No | 0 | 0.0% |
| `Disaster Type` | String | Categorical | No | 0 | 0.0% |
| `Disaster Subtype` | String | Categorical | No | 0 | 0.0% |
| `External IDs` | String | Categorical | Yes | 22,981 | 83.02% |
| `Event Name` | String | Categorical | Yes | 18,840 | 68.06% |
| `ISO` | String | Categorical | No | 0 | 0.0% |
| `Country` | String | Categorical | No | 0 | 0.0% |
| `Subregion` | String | Categorical | No | 0 | 0.0% |
| `Region` | String | Categorical | No | 0 | 0.0% |
| `Location` | String | Categorical | Yes | 2,484 | 8.97% |
| `Origin` | String | Categorical | Yes | 22,763 | 82.23% |
| `Associated Types` | String | Categorical | Yes | 23,229 | 83.92% |
| `OFDA/BHA Response` | String | Categorical | No | 0 | 0.0% |
| `Appeal` | String | Categorical | No | 0 | 0.0% |
| `Declaration` | String | Categorical | No | 0 | 0.0% |
| `AID Contribution ('000 US$)` | Float64 | Numeric | Yes | 26,894 | 97.16% |
| `Magnitude` | Float64 | Numeric | Yes | 22,210 | 80.24% |
| `Magnitude Scale` | String | Categorical | Yes | 10,295 | 37.19% |
| `Latitude` | Float64 | Numeric | Yes | 24,846 | 89.76% |
| `Longitude` | Float64 | Numeric | Yes | 24,846 | 89.76% |
| `River Basin` | String | Categorical | Yes | 26,048 | 94.1% |
| `Start Year` | Int64 | Numeric | No | 0 | 0.0% |
| `Start Month` | Float64 | Numeric | Yes | 481 | 1.74% |
| `Start Day` | Float64 | Numeric | Yes | 3,930 | 14.2% |
| `End Year` | Int64 | Numeric | No | 0 | 0.0% |
| `End Month` | Float64 | Numeric | Yes | 775 | 2.8% |
| `End Day` | Float64 | Numeric | Yes | 3,821 | 13.8% |
| `Total Deaths` | Float64 | Numeric | Yes | 5,563 | 20.1% |
| `No. Injured` | Float64 | Numeric | Yes | 18,444 | 66.63% |
| `No. Affected` | Float64 | Numeric | Yes | 16,023 | 57.88% |
| `No. Homeless` | Float64 | Numeric | Yes | 24,917 | 90.01% |
| `Total Affected` | Float64 | Numeric | Yes | 8,966 | 32.39% |
| `Reconstruction Costs ('000 US$)` | Float64 | Numeric | Yes | 27,637 | 99.84% |
| `Reconstruction Costs, Adjusted ('000 US$)` | Float64 | Numeric | Yes | 27,637 | 99.84% |
| `Insured Damage ('000 US$)` | Float64 | Numeric | Yes | 26,530 | 95.84% |
| `Insured Damage, Adjusted ('000 US$)` | Float64 | Numeric | Yes | 26,530 | 95.84% |
| `Total Damage ('000 US$)` | Float64 | Numeric | Yes | 21,640 | 78.18% |
| `Total Damage, Adjusted ('000 US$)` | Float64 | Numeric | Yes | 21,654 | 78.23% |
| `CPI` | Float64 | Numeric | Yes | 161 | 0.58% |
| `Admin Units` | String | Categorical | Yes | 19,274 | 69.63% |
| `GADM Admin Units` | String | Categorical | Yes | 19,839 | 71.67% |
| `Entry Date` | String | Categorical | No | 0 | 0.0% |
| `Last Update` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `DisNo.` | 1987-0326-JAM; 1987-0590-FSM; 1988-0312-PHL |
| `Historic` | Yes; No |
| `Classification Key` | nat-hyd-flo-riv; nat-met-sto-tro; nat-geo-ear-gro |
| `Disaster Group` | Natural; Technological |
| `Disaster Subgroup` | Hydrological; Meteorological; Geophysical |
| `Disaster Type` | Flood; Storm; Earthquake |
| `Disaster Subtype` | Riverine flood; Tropical cyclone; Ground movement |
| `External IDs` | GLIDE:EQ-2025-000153; GLIDE:EP-2025-000013; GLIDE:EP-2025-000030|GLIDE:EP-2025-000105 |
| `Event Name` | Typhoon 'Nina' (Sisang); Typhoon 'Warren' (Huaning); Hurricane 'Gilbert' |
| `ISO` | JAM; FSM; PHL |
| `Country` | Jamaica; Micronesia (Federated States of); Philippines |
| `Subregion` | Latin America and the Caribbean; Micronesia; South-eastern Asia |
| `Region` | Americas; Oceania; Asia |
| `Location` | Northern Luzon; Texas, Louisiana, Mississippi; Esmeraldas, Eloy Alfaro, Atacames, Muisne, Quinindé, Rioverde, and San Lorenz... |
| `Origin` | Tropical Depression Fourteen; Heavy rain; Intense rain |
| `Associated Types` | Slide (land, mud, snow, rock); Flood; Lightening |
| `OFDA/BHA Response` | No; Yes |
| `Appeal` | No; Yes |
| `Declaration` | No; Yes |
| `AID Contribution ('000 US$)` | 773.0; 721.0; 30.0 |
| `Magnitude` | 148.0; 215.0; 185.0 |
| `Magnitude Scale` | Km2; Kph; Moment Magnitude |
| `Latitude` | 1.084; 34.519; 30.89 |
| `Longitude` | -79.532; 70.734; 50.194 |
| `River Basin` | Kosi river; Huailhe and Yangtze; Banjir Kanal Barat river |
| `Start Year` | 1987; 1988; 1989 |
| `Start Month` | 10.0; 11.0; 7.0 |
| `Start Day` | 31.0; 21.0; 16.0 |
| `End Year` | 1987; 1988; 1989 |
| `End Month` | 11.0; 7.0; 8.0 |
| `End Day` | 4.0; 21.0; 16.0 |
| `Total Deaths` | 9.0; 5.0; 6.0 |
| `No. Injured` | 3.0; 49.0; 79.0 |
| `No. Affected` | 26000.0; 96120.0; 8241.0 |
| `No. Homeless` | 200.0; 21235.0; 222.0 |
| `Total Affected` | 26000.0; 203.0; 117355.0 |
| `Reconstruction Costs ('000 US$)` | 1000.0; 150000.0; 1600000.0 |
| `Reconstruction Costs, Adjusted ('000 US$)` | 2464.0; 300850.0; 2051354.0 |
| `Insured Damage ('000 US$)` | 45000.0; 92000.0; 68000.0 |
| `Insured Damage, Adjusted ('000 US$)` | 116866.0; 238925.0; 176597.0 |
| `Total Damage ('000 US$)` | 31000.0; 6000.0; 11516.0 |
| `Total Damage, Adjusted ('000 US$)` | 87835.0; 17000.0; 31351.0 |
| `CPI` | 35.29351844458779; 36.73269471079365; 38.505785490798694 |
| `Admin Units` | [{"adm1_code":1444,"adm1_name":"Budapest"}]; [{"adm1_code":40703,"adm1_name":"Kankan"}]; [{"adm1_code":607,"adm1_name":"Stann Creek"},{"adm1_code":608,"adm1_name":"To... |
| `GADM Admin Units` | [{"gid_1":"GIN.4_1","migration_date":"2025-12-20","migration_method":"jaccard...; [{"gid_1":"BLZ.5_1","migration_date":"2025-12-20","migration_method":"jaccard...; [{"gid_2":"NAM.13.1_1","migration_date":"2025-12-20","migration_method":"jacc... |
| `Entry Date` | 2003-07-01; 2026-05-12; 2008-04-04 |
| `Last Update` | 2026-05-12; 2026-05-15; 2026-05-11 |


---

# public_emdat_incl_hist_2026-06-29__EM-DAT_Info

| Field | Value |
| --- | --- |
| File path | public_emdat_incl_hist_2026-06-29/EM-DAT_Info.parquet |
| Format | parquet |
| File size | 2.2KB |
| Rows | 6 |
| Columns | 2 |
| File created | 2026-07-05T13:24:22.472386+00:00 |
| File last modified | 2026-07-05T13:24:22.473390+00:00 |
| Metadata generated | 2026-07-06T04:01:31.319332+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Source:` | String | Categorical | Yes | 1 | 16.67% |
| `EM-DAT, CRED / UCLouvain, Brussels, Belgium` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Source:` | Glossary:; Version:; File creation: |
| `EM-DAT, CRED / UCLouvain, Brussels, Belgium` | https://www.emdat.be; https://doc.emdat.be/docs/data-structure-and-content/emdat-public-table/; 2026-06-24 |


---

# Trade_DetailedTradeMatrix_E_All_Data__Trade_DetailedTradeMatrix_E_All_Data

| Field | Value |
| --- | --- |
| File path | Trade_DetailedTradeMatrix_E_All_Data/Trade_DetailedTradeMatrix_E_All_Data.parquet |
| Format | parquet |
| File size | 159.7MB |
| Rows | 6,640,547 |
| Columns | 90 |
| File created | 2026-07-05T12:54:30.425653+00:00 |
| File last modified | 2026-07-05T12:54:37.969469+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Reporter Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Reporter Country Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Reporter Countries` | String | Categorical | No | 0 | 0.0% |
| `Partner Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Partner Country Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Partner Countries` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item Code (CPC)` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Y1986` | String | Categorical | Yes | 6,215,777 | 93.6% |
| `Y1986F` | String | Categorical | Yes | 6,215,777 | 93.6% |
| `Y1987` | String | Categorical | Yes | 6,205,386 | 93.45% |
| `Y1987F` | String | Categorical | Yes | 6,205,386 | 93.45% |
| `Y1988` | String | Categorical | Yes | 6,162,037 | 92.79% |
| `Y1988F` | String | Categorical | Yes | 6,162,037 | 92.79% |
| `Y1989` | String | Categorical | Yes | 6,139,941 | 92.46% |
| `Y1989F` | String | Categorical | Yes | 6,139,941 | 92.46% |
| `Y1990` | String | Categorical | Yes | 6,137,606 | 92.43% |
| `Y1990F` | String | Categorical | Yes | 6,137,606 | 92.43% |
| `Y1991` | String | Categorical | Yes | 6,066,214 | 91.35% |
| `Y1991F` | String | Categorical | Yes | 6,066,214 | 91.35% |
| `Y1992` | String | Categorical | Yes | 6,003,653 | 90.41% |
| `Y1992F` | String | Categorical | Yes | 6,003,653 | 90.41% |
| `Y1993` | String | Categorical | Yes | 5,947,222 | 89.56% |
| `Y1993F` | String | Categorical | Yes | 5,947,222 | 89.56% |
| `Y1994` | String | Categorical | Yes | 5,858,419 | 88.22% |
| `Y1994F` | String | Categorical | Yes | 5,858,419 | 88.22% |
| `Y1995` | String | Categorical | Yes | 5,803,181 | 87.39% |
| `Y1995F` | String | Categorical | Yes | 5,803,181 | 87.39% |
| `Y1996` | Float64 | Numeric | Yes | 5,784,128 | 87.1% |
| `Y1996F` | String | Categorical | Yes | 5,784,128 | 87.1% |
| `Y1997` | Float64 | Numeric | Yes | 5,738,152 | 86.41% |
| `Y1997F` | String | Categorical | Yes | 5,738,152 | 86.41% |
| `Y1998` | String | Categorical | Yes | 5,669,278 | 85.37% |
| `Y1998F` | String | Categorical | Yes | 5,669,278 | 85.37% |
| `Y1999` | Float64 | Numeric | Yes | 5,629,645 | 84.78% |
| `Y1999F` | String | Categorical | Yes | 5,629,645 | 84.78% |
| `Y2000` | Float64 | Numeric | Yes | 5,515,499 | 83.06% |
| `Y2000F` | String | Categorical | Yes | 5,515,499 | 83.06% |
| `Y2001` | Float64 | Numeric | Yes | 5,418,273 | 81.59% |
| `Y2001F` | String | Categorical | Yes | 5,418,273 | 81.59% |
| `Y2002` | Float64 | Numeric | Yes | 5,361,982 | 80.75% |
| `Y2002F` | String | Categorical | Yes | 5,361,982 | 80.75% |
| `Y2003` | Float64 | Numeric | Yes | 5,332,151 | 80.3% |
| `Y2003F` | String | Categorical | Yes | 5,332,151 | 80.3% |
| `Y2004` | Float64 | Numeric | Yes | 5,283,025 | 79.56% |
| `Y2004F` | String | Categorical | Yes | 5,283,025 | 79.56% |
| `Y2005` | Float64 | Numeric | Yes | 5,232,553 | 78.8% |
| `Y2005F` | String | Categorical | Yes | 5,232,553 | 78.8% |
| `Y2006` | Float64 | Numeric | Yes | 5,240,427 | 78.92% |
| `Y2006F` | String | Categorical | Yes | 5,240,427 | 78.92% |
| `Y2007` | Float64 | Numeric | Yes | 5,164,370 | 77.77% |
| `Y2007F` | String | Categorical | Yes | 5,164,370 | 77.77% |
| `Y2008` | Float64 | Numeric | Yes | 5,171,579 | 77.88% |
| `Y2008F` | String | Categorical | Yes | 5,171,579 | 77.88% |
| `Y2009` | Float64 | Numeric | Yes | 5,156,053 | 77.65% |
| `Y2009F` | String | Categorical | Yes | 5,156,053 | 77.65% |
| `Y2010` | Float64 | Numeric | Yes | 5,116,749 | 77.05% |
| `Y2010F` | String | Categorical | Yes | 5,116,749 | 77.05% |
| `Y2011` | Float64 | Numeric | Yes | 5,083,406 | 76.55% |
| `Y2011F` | String | Categorical | Yes | 5,083,406 | 76.55% |
| `Y2012` | Float64 | Numeric | Yes | 4,960,274 | 74.7% |
| `Y2012F` | String | Categorical | Yes | 4,960,274 | 74.7% |
| `Y2013` | Float64 | Numeric | Yes | 4,903,491 | 73.84% |
| `Y2013F` | String | Categorical | Yes | 4,903,491 | 73.84% |
| `Y2014` | Float64 | Numeric | Yes | 4,800,669 | 72.29% |
| `Y2014F` | String | Categorical | Yes | 4,800,669 | 72.29% |
| `Y2015` | Float64 | Numeric | Yes | 4,761,156 | 71.7% |
| `Y2015F` | String | Categorical | Yes | 4,761,156 | 71.7% |
| `Y2016` | Float64 | Numeric | Yes | 4,671,410 | 70.35% |
| `Y2016F` | String | Categorical | Yes | 4,671,410 | 70.35% |
| `Y2017` | Float64 | Numeric | Yes | 4,573,976 | 68.88% |
| `Y2017F` | String | Categorical | Yes | 4,573,976 | 68.88% |
| `Y2018` | Float64 | Numeric | Yes | 4,554,509 | 68.59% |
| `Y2018F` | String | Categorical | Yes | 4,554,509 | 68.59% |
| `Y2019` | Float64 | Numeric | Yes | 4,508,750 | 67.9% |
| `Y2019F` | String | Categorical | Yes | 4,508,750 | 67.9% |
| `Y2020` | Float64 | Numeric | Yes | 4,500,460 | 67.77% |
| `Y2020F` | String | Categorical | Yes | 4,500,460 | 67.77% |
| `Y2021` | Float64 | Numeric | Yes | 4,391,599 | 66.13% |
| `Y2021F` | String | Categorical | Yes | 4,391,599 | 66.13% |
| `Y2022` | String | Categorical | Yes | 4,410,397 | 66.42% |
| `Y2022F` | String | Categorical | Yes | 4,410,397 | 66.42% |
| `Y2023` | Float64 | Numeric | Yes | 4,437,715 | 66.83% |
| `Y2023F` | String | Categorical | Yes | 4,437,715 | 66.83% |
| `Y2024` | Float64 | Numeric | Yes | 4,659,591 | 70.17% |
| `Y2024F` | String | Categorical | Yes | 4,659,591 | 70.17% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Reporter Country Code` | 2; 3; 4 |
| `Reporter Country Code (M49)` | '004; '008; '012 |
| `Reporter Countries` | Afghanistan; Albania; Algeria |
| `Partner Country Code` | 9; 1; 10 |
| `Partner Country Code (M49)` | '032; '051; '036 |
| `Partner Countries` | Argentina; Armenia; Australia |
| `Item Code` | 341; 1232; 1058 |
| `Item Code (CPC)` | '21910.90; 'F1232; '21121 |
| `Item` | Cake, oilseeds nes; Food preparations n.e.c.; Meat of chickens, fresh or chilled |
| `Element Code` | 5610; 5622; 5910 |
| `Element` | Import quantity; Import value; Export quantity |
| `Unit` | t; 1000 USD; 1000 An |
| `Y1986` | 1200.000000; 266.000000; 24145.000000 |
| `Y1986F` | A; E |
| `Y1987` | 35629.000000; 4403.000000; 1000.000000 |
| `Y1987F` | A; E |
| `Y1988` | 9780.000000; 1272.000000; 500.000000 |
| `Y1988F` | A; E |
| `Y1989` | 770.000000; 1521.000000; 10640.000000 |
| `Y1989F` | A; E |
| `Y1990` | 1460.000000; 199.000000; 1000.000000 |
| `Y1990F` | A; E |
| `Y1991` | 0.000000; 2.000000; 5000.000000 |
| `Y1991F` | A; E |
| `Y1992` | 11.000000; 8.000000; 196.000000 |
| `Y1992F` | A; E; X |
| `Y1993` | 2250.000000; 5013.000000; 2700.000000 |
| `Y1993F` | A; E; X |
| `Y1994` | 1.000000; 5.000000; 19715.000000 |
| `Y1994F` | A; E; X |
| `Y1995` | 114537.000000; 11352.000000; 14750.000000 |
| `Y1995F` | A; E; X |
| `Y1996` | 0.0; 26.0; 40.0 |
| `Y1996F` | A; E; X |
| `Y1997` | 16.0; 28.0; 1.0 |
| `Y1997F` | A; E; X |
| `Y1998` | 358.000000; 451.000000; 8651.000000 |
| `Y1998F` | A; E; X |
| `Y1999` | 1.0; 2.0; 25.0 |
| `Y1999F` | X; A; E |
| `Y2000` | 1000.0; 141.0; 26.0 |
| `Y2000F` | A; X; E |
| `Y2001` | 11.0; 7.0; 16542.0 |
| `Y2001F` | A; X; E |
| `Y2002` | 28.0; 8.0; 850.0 |
| `Y2002F` | A; X; E |
| `Y2003` | 52.0; 59.0; 14.0 |
| `Y2003F` | A; X; E |
| `Y2004` | 12.0; 104.0; 1.0 |
| `Y2004F` | A; E; X |
| `Y2005` | 52.0; 6.0; 22.0 |
| `Y2005F` | A; E; X |
| `Y2006` | 24.0; 8.0; 1.0 |
| `Y2006F` | A; E; X |
| `Y2007` | 0.0; 5.0; 62.0 |
| `Y2007F` | A; E; X |
| `Y2008` | 59.0; 435.0; 48.0 |
| `Y2008F` | A; E; X |
| `Y2009` | 10.0; 49.0; 141.0 |
| `Y2009F` | X; A; E |
| `Y2010` | 0.0; 2.0; 3.0 |
| `Y2010F` | A; X; E |
| `Y2011` | 1.0; 4.0; 198.0 |
| `Y2011F` | A; E; X |
| `Y2012` | 0.0; 1.0; 3.0 |
| `Y2012F` | A; E; X |
| `Y2013` | 11200.0; 6352.0; 2.0 |
| `Y2013F` | A; X; E |
| `Y2014` | 21649.5; 11685.0; 4542.56 |
| `Y2014F` | A; X; E |
| `Y2015` | 13925.0; 6380.0; 20735.87 |
| `Y2015F` | A; X; E |
| `Y2016` | 13175.0; 6912.0; 12612.13 |
| `Y2016F` | A; I; X |
| `Y2017` | 463.11; 85.0; 214.5 |
| `Y2017F` | A; E; I |
| `Y2018` | 4843.45; 2300.0; 627.32 |
| `Y2018F` | A; E; X |
| `Y2019` | 1192.62; 217.0; 98.8 |
| `Y2019F` | A; E; I |
| `Y2020` | 5.34; 13.0; 6000.43 |
| `Y2020F` | A; E; I |
| `Y2021` | 4127.62; 2322.0; 17.41 |
| `Y2021F` | A; E; I |
| `Y2022` | 25.060000; 39.000000; 0.020000 |
| `Y2022F` | A; E; I |
| `Y2023` | 4329.5; 3238.0; 12.14 |
| `Y2023F` | A; E; I |
| `Y2024` | 0.07; 2.0; 259.2 |
| `Y2024F` | A; E; X |


---

# Trade_DetailedTradeMatrix_E_All_Data__Trade_DetailedTradeMatrix_E_All_Data_NOFLAG

| Field | Value |
| --- | --- |
| File path | Trade_DetailedTradeMatrix_E_All_Data/Trade_DetailedTradeMatrix_E_All_Data_NOFLAG.parquet |
| Format | parquet |
| File size | 143.2MB |
| Rows | 6,640,547 |
| Columns | 51 |
| File created | 2026-07-05T12:54:38.009448+00:00 |
| File last modified | 2026-07-05T12:54:42.804652+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Reporter Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Reporter Country Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Reporter Countries` | String | Categorical | No | 0 | 0.0% |
| `Partner Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Partner Country Code (M49)` | String | Categorical | No | 0 | 0.0% |
| `Partner Countries` | String | Categorical | No | 0 | 0.0% |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Item Code (CPC)` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |
| `Unit` | String | Categorical | No | 0 | 0.0% |
| `Y1986` | String | Categorical | Yes | 6,215,777 | 93.6% |
| `Y1987` | String | Categorical | Yes | 6,205,386 | 93.45% |
| `Y1988` | String | Categorical | Yes | 6,162,037 | 92.79% |
| `Y1989` | String | Categorical | Yes | 6,139,941 | 92.46% |
| `Y1990` | String | Categorical | Yes | 6,137,606 | 92.43% |
| `Y1991` | String | Categorical | Yes | 6,066,214 | 91.35% |
| `Y1992` | String | Categorical | Yes | 6,003,653 | 90.41% |
| `Y1993` | String | Categorical | Yes | 5,947,222 | 89.56% |
| `Y1994` | String | Categorical | Yes | 5,858,419 | 88.22% |
| `Y1995` | String | Categorical | Yes | 5,803,181 | 87.39% |
| `Y1996` | Float64 | Numeric | Yes | 5,784,128 | 87.1% |
| `Y1997` | Float64 | Numeric | Yes | 5,738,152 | 86.41% |
| `Y1998` | String | Categorical | Yes | 5,669,278 | 85.37% |
| `Y1999` | Float64 | Numeric | Yes | 5,629,645 | 84.78% |
| `Y2000` | Float64 | Numeric | Yes | 5,515,499 | 83.06% |
| `Y2001` | Float64 | Numeric | Yes | 5,418,273 | 81.59% |
| `Y2002` | Float64 | Numeric | Yes | 5,361,982 | 80.75% |
| `Y2003` | Float64 | Numeric | Yes | 5,332,151 | 80.3% |
| `Y2004` | Float64 | Numeric | Yes | 5,283,025 | 79.56% |
| `Y2005` | Float64 | Numeric | Yes | 5,232,553 | 78.8% |
| `Y2006` | Float64 | Numeric | Yes | 5,240,427 | 78.92% |
| `Y2007` | Float64 | Numeric | Yes | 5,164,370 | 77.77% |
| `Y2008` | Float64 | Numeric | Yes | 5,171,579 | 77.88% |
| `Y2009` | Float64 | Numeric | Yes | 5,156,053 | 77.65% |
| `Y2010` | Float64 | Numeric | Yes | 5,116,749 | 77.05% |
| `Y2011` | Float64 | Numeric | Yes | 5,083,406 | 76.55% |
| `Y2012` | Float64 | Numeric | Yes | 4,960,274 | 74.7% |
| `Y2013` | Float64 | Numeric | Yes | 4,903,491 | 73.84% |
| `Y2014` | Float64 | Numeric | Yes | 4,800,669 | 72.29% |
| `Y2015` | Float64 | Numeric | Yes | 4,761,156 | 71.7% |
| `Y2016` | Float64 | Numeric | Yes | 4,671,410 | 70.35% |
| `Y2017` | Float64 | Numeric | Yes | 4,573,976 | 68.88% |
| `Y2018` | Float64 | Numeric | Yes | 4,554,509 | 68.59% |
| `Y2019` | Float64 | Numeric | Yes | 4,508,750 | 67.9% |
| `Y2020` | Float64 | Numeric | Yes | 4,500,460 | 67.77% |
| `Y2021` | Float64 | Numeric | Yes | 4,391,599 | 66.13% |
| `Y2022` | String | Categorical | Yes | 4,410,397 | 66.42% |
| `Y2023` | Float64 | Numeric | Yes | 4,437,715 | 66.83% |
| `Y2024` | Float64 | Numeric | Yes | 4,659,591 | 70.17% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Reporter Country Code` | 2; 3; 4 |
| `Reporter Country Code (M49)` | '004; '008; '012 |
| `Reporter Countries` | Afghanistan; Albania; Algeria |
| `Partner Country Code` | 9; 1; 10 |
| `Partner Country Code (M49)` | '032; '051; '036 |
| `Partner Countries` | Argentina; Armenia; Australia |
| `Item Code` | 341; 1232; 1058 |
| `Item Code (CPC)` | '21910.90; 'F1232; '21121 |
| `Item` | Cake, oilseeds nes; Food preparations n.e.c.; Meat of chickens, fresh or chilled |
| `Element Code` | 5610; 5622; 5910 |
| `Element` | Import quantity; Import value; Export quantity |
| `Unit` | t; 1000 USD; 1000 An |
| `Y1986` | 1200.000000; 266.000000; 24145.000000 |
| `Y1987` | 35629.000000; 4403.000000; 1000.000000 |
| `Y1988` | 9780.000000; 1272.000000; 500.000000 |
| `Y1989` | 770.000000; 1521.000000; 10640.000000 |
| `Y1990` | 1460.000000; 199.000000; 1000.000000 |
| `Y1991` | 0.000000; 2.000000; 5000.000000 |
| `Y1992` | 11.000000; 8.000000; 196.000000 |
| `Y1993` | 2250.000000; 5013.000000; 2700.000000 |
| `Y1994` | 1.000000; 5.000000; 19715.000000 |
| `Y1995` | 114537.000000; 11352.000000; 14750.000000 |
| `Y1996` | 0.0; 26.0; 40.0 |
| `Y1997` | 16.0; 28.0; 1.0 |
| `Y1998` | 358.000000; 451.000000; 8651.000000 |
| `Y1999` | 1.0; 2.0; 25.0 |
| `Y2000` | 1000.0; 141.0; 26.0 |
| `Y2001` | 11.0; 7.0; 16542.0 |
| `Y2002` | 28.0; 8.0; 850.0 |
| `Y2003` | 52.0; 59.0; 14.0 |
| `Y2004` | 12.0; 104.0; 1.0 |
| `Y2005` | 52.0; 6.0; 22.0 |
| `Y2006` | 24.0; 8.0; 1.0 |
| `Y2007` | 0.0; 5.0; 62.0 |
| `Y2008` | 59.0; 435.0; 48.0 |
| `Y2009` | 10.0; 49.0; 141.0 |
| `Y2010` | 0.0; 2.0; 3.0 |
| `Y2011` | 1.0; 4.0; 198.0 |
| `Y2012` | 0.0; 1.0; 3.0 |
| `Y2013` | 11200.0; 6352.0; 2.0 |
| `Y2014` | 21649.5; 11685.0; 4542.56 |
| `Y2015` | 13925.0; 6380.0; 20735.87 |
| `Y2016` | 13175.0; 6912.0; 12612.13 |
| `Y2017` | 463.11; 85.0; 214.5 |
| `Y2018` | 4843.45; 2300.0; 627.32 |
| `Y2019` | 1192.62; 217.0; 98.8 |
| `Y2020` | 5.34; 13.0; 6000.43 |
| `Y2021` | 4127.62; 2322.0; 17.41 |
| `Y2022` | 25.060000; 39.000000; 0.020000 |
| `Y2023` | 4329.5; 3238.0; 12.14 |
| `Y2024` | 0.07; 2.0; 259.2 |


---

# Trade_DetailedTradeMatrix_E_All_Data__Trade_DetailedTradeMatrix_E_Elements

| Field | Value |
| --- | --- |
| File path | Trade_DetailedTradeMatrix_E_All_Data/Trade_DetailedTradeMatrix_E_Elements.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 10 |
| Columns | 2 |
| File created | 2026-07-05T12:54:42.820649+00:00 |
| File last modified | 2026-07-05T12:54:42.821649+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Element Code` | Int64 | Numeric | No | 0 | 0.0% |
| `Element` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Element Code` | 5907; 5908; 5909 |
| `Element` | Export quantity; Export value; Import quantity |


---

# Trade_DetailedTradeMatrix_E_All_Data__Trade_DetailedTradeMatrix_E_Flags

| Field | Value |
| --- | --- |
| File path | Trade_DetailedTradeMatrix_E_All_Data/Trade_DetailedTradeMatrix_E_Flags.parquet |
| Format | parquet |
| File size | 1.0KB |
| Rows | 4 |
| Columns | 2 |
| File created | 2026-07-05T12:54:42.833649+00:00 |
| File last modified | 2026-07-05T12:54:42.833649+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Flag` | String | Categorical | No | 0 | 0.0% |
| ` Description` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Flag` | A; E; I |
| ` Description` | Official figure; Estimated value; Value imputed by a receiving agency |


---

# Trade_DetailedTradeMatrix_E_All_Data__Trade_DetailedTradeMatrix_E_ItemCodes

| Field | Value |
| --- | --- |
| File path | Trade_DetailedTradeMatrix_E_All_Data/Trade_DetailedTradeMatrix_E_ItemCodes.parquet |
| Format | parquet |
| File size | 10.4KB |
| Rows | 572 |
| Columns | 3 |
| File created | 2026-07-05T12:54:42.847013+00:00 |
| File last modified | 2026-07-05T12:54:42.849016+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Item Code` | Int64 | Numeric | No | 0 | 0.0% |
| `CPC Code` | String | Categorical | No | 0 | 0.0% |
| `Item` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Item Code` | 809; 221; 231 |
| `CPC Code` | '01929.07; '01371; '21422 |
| `Item` | Abaca; manila hemp; raw; Almonds; in shell; Almonds; shelled |


---

# Trade_DetailedTradeMatrix_E_All_Data__Trade_DetailedTradeMatrix_E_PartnerCountries

| Field | Value |
| --- | --- |
| File path | Trade_DetailedTradeMatrix_E_All_Data/Trade_DetailedTradeMatrix_E_PartnerCountries.parquet |
| Format | parquet |
| File size | 4.3KB |
| Rows | 255 |
| Columns | 3 |
| File created | 2026-07-05T12:54:42.861012+00:00 |
| File last modified | 2026-07-05T12:54:42.862013+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Partner Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Partner Countries` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Partner Country Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Partner Countries` | Afghanistan; Africa; Albania |


---

# Trade_DetailedTradeMatrix_E_All_Data__Trade_DetailedTradeMatrix_E_ReporterCountries

| Field | Value |
| --- | --- |
| File path | Trade_DetailedTradeMatrix_E_All_Data/Trade_DetailedTradeMatrix_E_ReporterCountries.parquet |
| Format | parquet |
| File size | 4.1KB |
| Rows | 232 |
| Columns | 3 |
| File created | 2026-07-05T12:54:42.871016+00:00 |
| File last modified | 2026-07-05T12:54:42.873016+00:00 |
| Metadata generated | 2026-07-07T14:11:36.482423+00:00 |

## Schema

| Column | Type | Category | Nullable | Null count | Null % |
| --- | --- | --- | --- | --- | --- |
| `Reporter Country Code` | Int64 | Numeric | No | 0 | 0.0% |
| `M49 Code` | String | Categorical | No | 0 | 0.0% |
| `Reporter Countries` | String | Categorical | No | 0 | 0.0% |

**Sample values:**

| Column | Sample value(s) |
| --- | --- |
| `Reporter Country Code` | 2; 5100; 3 |
| `M49 Code` | '004; '002; '008 |
| `Reporter Countries` | Afghanistan; Africa; Albania |


---

