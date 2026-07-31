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
