# Data Dictionary - Global Agriculture Market Intelligence
**Database:** global_agriculature_market_intelligence.duckdb
**Generated At:** 2026-07-31 17:13:11

> This document is automatically generated from database metadata.
> It provides schema, table, column, and datatype information.
> Business definitions are documented separately for analytical models.
---
## Layer Description

| Layer | Tables |
|---|---:|
| raw | 369 |
| staging | 350 |
| intermediate | 73 |
| marts | 76 |
| reporting | 16 |
---
# Schema: raw (369 tables)
## 1. Table: raw.asti_expenditures
**Row Count (estimated):** 7,789
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Cost Category Code | BIGINT |
| Cost Category | VARCHAR |
| Institution Code | BIGINT |
| Institution | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 2. Table: raw.asti_expenditures_archive
**Row Count (estimated):** 3,094
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 3. Table: raw.asti_expenditures_archive_areacodes
**Row Count (estimated):** 121
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 4. Table: raw.asti_expenditures_archive_elements
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 5. Table: raw.asti_expenditures_archive_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 6. Table: raw.asti_expenditures_archive_itemcodes
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 7. Table: raw.asti_expenditures_areacodes
**Row Count (estimated):** 163
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 8. Table: raw.asti_expenditures_costcategorys
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Cost Category Code | BIGINT |
| Cost Category | VARCHAR |
---
## 9. Table: raw.asti_expenditures_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 10. Table: raw.asti_expenditures_indicators
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
---
## 11. Table: raw.asti_expenditures_institutions
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Institution Code | BIGINT |
| Institution | VARCHAR |
---
## 12. Table: raw.asti_researchers
**Row Count (estimated):** 3,800
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Degree Code | BIGINT |
| Degree | VARCHAR |
| Sex Code | BIGINT |
| Sex Code (SDG) | VARCHAR |
| Sex | VARCHAR |
| Institution Code | BIGINT |
| Institution | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 13. Table: raw.asti_researchers_archive
**Row Count (estimated):** 3,154
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 14. Table: raw.asti_researchers_archive_areacodes
**Row Count (estimated):** 121
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 15. Table: raw.asti_researchers_archive_elements
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 16. Table: raw.asti_researchers_archive_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 17. Table: raw.asti_researchers_archive_itemcodes
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 18. Table: raw.asti_researchers_areacodes
**Row Count (estimated):** 168
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 19. Table: raw.asti_researchers_degrees
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Degree Code | BIGINT |
| Degree | VARCHAR |
---
## 20. Table: raw.asti_researchers_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 21. Table: raw.asti_researchers_indicators
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
---
## 22. Table: raw.asti_researchers_institutions
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Institution Code | BIGINT |
| Institution | VARCHAR |
---
## 23. Table: raw.asti_researchers_sexes
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Sex Code | BIGINT |
| Sex | VARCHAR |
---
## 24. Table: raw.climate_change_emissions_indicators
**Row Count (estimated):** 678,370
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 25. Table: raw.climate_change_emissions_indicators_areacodes
**Row Count (estimated):** 279
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 26. Table: raw.climate_change_emissions_indicators_elements
**Row Count (estimated):** 10
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 27. Table: raw.climate_change_emissions_indicators_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 28. Table: raw.climate_change_emissions_indicators_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 29. Table: raw.commodity_indices
**Row Count (estimated):** 798
### Columns
| Column Name | Data Type |
|---|---|
| Total Index | DOUBLE |
| Energy | DOUBLE |
| Non-energy ** | DOUBLE |
| Agriculture ** | DOUBLE |
| Beverages | DOUBLE |
| Food ** | DOUBLE |
| Oils & Meals | DOUBLE |
| Grains | DOUBLE |
| Other Food ** | DOUBLE |
| Raw Materials | DOUBLE |
| Timber | DOUBLE |
| Other Raw Mat. | DOUBLE |
| Fertilizers ** | DOUBLE |
| Metals  & Minerals | DOUBLE |
| Base Metals (ex. iron ore) | DOUBLE |
| Precious Metals | DOUBLE |
| Date | DATE |
---
## 30. Table: raw.commodity_prices
**Row Count (estimated):** 798
### Columns
| Column Name | Data Type |
|---|---|
| Crude oil, average ($/bbl) | DOUBLE |
| Crude oil, Brent ($/bbl) | DOUBLE |
| Crude oil, Dubai ($/bbl) | DOUBLE |
| Crude oil, WTI ($/bbl) | DOUBLE |
| Coal, Australian ($/mt) | DOUBLE |
| Coal, South African ** ($/mt) | DOUBLE |
| Natural gas, US ($/mmbtu) | DOUBLE |
| Natural gas, Europe ($/mmbtu) | DOUBLE |
| Liquefied natural gas, Japan ($/mmbtu) | DOUBLE |
| Natural gas index (2010=100) | DOUBLE |
| Cocoa ($/kg) | DOUBLE |
| Coffee, Arabica ($/kg) | DOUBLE |
| Coffee, Robusta ($/kg) | DOUBLE |
| Tea, avg 3 auctions ($/kg) | DOUBLE |
| Tea, Colombo ($/kg) | DOUBLE |
| Tea, Kolkata ($/kg) | DOUBLE |
| Tea, Mombasa ($/kg) | DOUBLE |
| Coconut oil ($/mt) | BIGINT |
| Groundnuts ($/mt) | DOUBLE |
| Fish meal ($/mt) | DOUBLE |
| Groundnut oil ** ($/mt) | BIGINT |
| Palm oil ($/mt) | BIGINT |
| Palm kernel oil ($/mt) | DOUBLE |
| Soybeans ($/mt) | BIGINT |
| Soybean oil ($/mt) | BIGINT |
| Soybean meal ($/mt) | BIGINT |
| Rapeseed oil ($/mt) | DOUBLE |
| Sunflower oil ($/mt) | DOUBLE |
| Barley ($/mt) | DOUBLE |
| Maize ($/mt) | DOUBLE |
| Sorghum ($/mt) | DOUBLE |
| Rice, Thai 5% ($/mt) | DOUBLE |
| Rice, Thai 25% ($/mt) | DOUBLE |
| Rice, Thai A.1 ($/mt) | DOUBLE |
| Rice, Viet Namese 5% ($/mt) | DOUBLE |
| Wheat, US SRW ($/mt) | DOUBLE |
| Wheat, US HRW ($/mt) | DOUBLE |
| Banana, Europe ($/kg) | DOUBLE |
| Banana, US ($/kg) | DOUBLE |
| Orange ($/kg) | DOUBLE |
| Beef ** ($/kg) | DOUBLE |
| Chicken ** ($/kg) | DOUBLE |
| Lamb ** ($/kg) | DOUBLE |
| Shrimps, Mexican ($/kg) | DOUBLE |
| Sugar, EU ($/kg) | DOUBLE |
| Sugar, US ($/kg) | DOUBLE |
| Sugar, world ($/kg) | DOUBLE |
| Tobacco, US import u.v. ($/mt) | DOUBLE |
| Logs, Cameroon ($/cubic meter) | DOUBLE |
| Logs, Malaysian ($/cubic meter) | DOUBLE |
| Sawnwood, Cameroon ($/cubic meter) | DOUBLE |
| Sawnwood, Malaysian ($/cubic meter) | DOUBLE |
| Plywood (cents/sheet) | DOUBLE |
| Cotton, A Index ($/kg) | DOUBLE |
| Rubber, TSR20 ** ($/kg) | DOUBLE |
| Rubber, RSS3 ($/kg) | DOUBLE |
| Phosphate rock ($/mt) | DOUBLE |
| DAP ($/mt) | DOUBLE |
| TSP ($/mt) | DOUBLE |
| Urea ($/mt) | DOUBLE |
| Potassium chloride ** ($/mt) | DOUBLE |
| Aluminum ($/mt) | BIGINT |
| Iron ore, cfr spot ($/dmtu) | DOUBLE |
| Copper ($/mt) | BIGINT |
| Lead ($/mt) | BIGINT |
| Tin ($/mt) | BIGINT |
| Nickel ($/mt) | BIGINT |
| Zinc ($/mt) | BIGINT |
| Gold ($/troy oz) | BIGINT |
| Platinum ($/troy oz) | BIGINT |
| Silver ($/troy oz) | DOUBLE |
| Date | DATE |
---
## 31. Table: raw.commoditybalances_non_food
**Row Count (estimated):** 1,184,986
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 32. Table: raw.commoditybalances_non_food_2010
**Row Count (estimated):** 127,558
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 33. Table: raw.commoditybalances_non_food_2010_areacodes
**Row Count (estimated):** 213
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 34. Table: raw.commoditybalances_non_food_2010_elements
**Row Count (estimated):** 7
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 35. Table: raw.commoditybalances_non_food_2010_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 36. Table: raw.commoditybalances_non_food_2010_itemcodes
**Row Count (estimated):** 13
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 37. Table: raw.commoditybalances_non_food_2013_old_methodology
**Row Count (estimated):** 1,184,986
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 38. Table: raw.commoditybalances_non_food_2013_old_methodology_areacodes
**Row Count (estimated):** 217
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 39. Table: raw.commoditybalances_non_food_2013_old_methodology_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 40. Table: raw.commoditybalances_non_food_2013_old_methodology_itemcodes
**Row Count (estimated):** 22
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 41. Table: raw.commoditybalances_non_food_areacodes
**Row Count (estimated):** 217
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 42. Table: raw.commoditybalances_non_food_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 43. Table: raw.commoditybalances_non_food_itemcodes
**Row Count (estimated):** 28
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 44. Table: raw.consumerpriceindices
**Row Count (estimated):** 248,394
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Months Code | BIGINT |
| Months | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 45. Table: raw.consumerpriceindices_areacodes
**Row Count (estimated):** 252
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 46. Table: raw.consumerpriceindices_elements
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 47. Table: raw.consumerpriceindices_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 48. Table: raw.consumerpriceindices_itemcodes
**Row Count (estimated):** 9
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 49. Table: raw.cost_affordability_healthy_diet_coahd
**Row Count (estimated):** 11,672
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Release Code | VARCHAR |
| Release | VARCHAR |
| Unit | VARCHAR |
| Value | VARCHAR |
| Flag | VARCHAR |
---
## 50. Table: raw.cost_affordability_healthy_diet_coahd_areacodes
**Row Count (estimated):** 263
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 51. Table: raw.cost_affordability_healthy_diet_coahd_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 52. Table: raw.cost_affordability_healthy_diet_coahd_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 53. Table: raw.cost_affordability_healthy_diet_coahd_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 54. Table: raw.cost_affordability_healthy_diet_coahd_releases
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Release Code | VARCHAR |
|  Release | VARCHAR |
---
## 55. Table: raw.country_codes
**Row Count (estimated):** 245
### Columns
| Column Name | Data Type |
|---|---|
| country | VARCHAR |
| latitude | DOUBLE |
| longitude | DOUBLE |
| name | VARCHAR |
---
## 56. Table: raw.deflators
**Row Count (estimated):** 92,776
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 57. Table: raw.deflators_areacodes
**Row Count (estimated):** 252
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 58. Table: raw.deflators_elements
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 59. Table: raw.deflators_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 60. Table: raw.deflators_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 61. Table: raw.development_assistance_to_agriculture
**Row Count (estimated):** 13,020,275
### Columns
| Column Name | Data Type |
|---|---|
| Donor Code | BIGINT |
| Donor Code (M49) | VARCHAR |
| Donor | VARCHAR |
| Recipient Country Code | BIGINT |
| Recipient Country Code (M49) | VARCHAR |
| Recipient Country | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Purpose Code | BIGINT |
| Purpose | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 62. Table: raw.development_assistance_to_agriculture_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 63. Table: raw.development_assistance_to_agriculture_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 64. Table: raw.development_assistance_to_agriculture_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 65. Table: raw.development_assistance_to_agriculture_purposes
**Row Count (estimated):** 58
### Columns
| Column Name | Data Type |
|---|---|
|  Purpose Code | BIGINT |
|  Purpose | VARCHAR |
---
## 66. Table: raw.emdat
**Row Count (estimated):** 27,681
### Columns
| Column Name | Data Type |
|---|---|
| DisNo. | VARCHAR |
| Historic | VARCHAR |
| Classification Key | VARCHAR |
| Disaster Group | VARCHAR |
| Disaster Subgroup | VARCHAR |
| Disaster Type | VARCHAR |
| Disaster Subtype | VARCHAR |
| External IDs | VARCHAR |
| Event Name | VARCHAR |
| ISO | VARCHAR |
| Country | VARCHAR |
| Subregion | VARCHAR |
| Region | VARCHAR |
| Location | VARCHAR |
| Origin | VARCHAR |
| Associated Types | VARCHAR |
| OFDA/BHA Response | VARCHAR |
| Appeal | VARCHAR |
| Declaration | VARCHAR |
| AID Contribution ('000 US$) | DOUBLE |
| Magnitude | DOUBLE |
| Magnitude Scale | VARCHAR |
| Latitude | DOUBLE |
| Longitude | DOUBLE |
| River Basin | VARCHAR |
| Start Year | BIGINT |
| Start Month | DOUBLE |
| Start Day | DOUBLE |
| End Year | BIGINT |
| End Month | DOUBLE |
| End Day | DOUBLE |
| Total Deaths | DOUBLE |
| No. Injured | DOUBLE |
| No. Affected | DOUBLE |
| No. Homeless | DOUBLE |
| Total Affected | DOUBLE |
| Reconstruction Costs ('000 US$) | DOUBLE |
| Reconstruction Costs, Adjusted ('000 US$) | DOUBLE |
| Insured Damage ('000 US$) | DOUBLE |
| Insured Damage, Adjusted ('000 US$) | DOUBLE |
| Total Damage ('000 US$) | DOUBLE |
| Total Damage, Adjusted ('000 US$) | DOUBLE |
| CPI | DOUBLE |
| Admin Units | VARCHAR |
| GADM Admin Units | VARCHAR |
| Entry Date | DATE |
| Last Update | DATE |
---
## 67. Table: raw.emissions_agriculture_energy
**Row Count (estimated):** 120,740
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 68. Table: raw.emissions_agriculture_energy_areacodes
**Row Count (estimated):** 280
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 69. Table: raw.emissions_agriculture_energy_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 70. Table: raw.emissions_agriculture_energy_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 71. Table: raw.emissions_agriculture_energy_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 72. Table: raw.emissions_crops
**Row Count (estimated):** 766,730
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Source Code | BIGINT |
| Source | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 73. Table: raw.emissions_crops_areacodes
**Row Count (estimated):** 282
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 74. Table: raw.emissions_crops_elements
**Row Count (estimated):** 23
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 75. Table: raw.emissions_crops_flags
**Row Count (estimated):** 8
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 76. Table: raw.emissions_crops_itemcodes
**Row Count (estimated):** 14
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 77. Table: raw.emissions_crops_sources
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Source Code | BIGINT |
| Source | VARCHAR |
---
## 78. Table: raw.emissions_drained_organic_soils
**Row Count (estimated):** 87,484
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Source Code | BIGINT |
| Source | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 79. Table: raw.emissions_drained_organic_soils_areacodes
**Row Count (estimated):** 280
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 80. Table: raw.emissions_drained_organic_soils_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 81. Table: raw.emissions_drained_organic_soils_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 82. Table: raw.emissions_drained_organic_soils_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 83. Table: raw.emissions_drained_organic_soils_sources
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Source Code | BIGINT |
|  Source | VARCHAR |
---
## 84. Table: raw.emissions_land_use_fires
**Row Count (estimated):** 428,963
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Source Code | BIGINT |
| Source | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 85. Table: raw.emissions_land_use_fires_areacodes
**Row Count (estimated):** 280
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 86. Table: raw.emissions_land_use_fires_elements
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 87. Table: raw.emissions_land_use_fires_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 88. Table: raw.emissions_land_use_fires_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 89. Table: raw.emissions_land_use_fires_sources
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Source Code | BIGINT |
|  Source | VARCHAR |
---
## 90. Table: raw.emissions_land_use_forests
**Row Count (estimated):** 65,639
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Source Code | BIGINT |
| Source | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 91. Table: raw.emissions_land_use_forests_areacodes
**Row Count (estimated):** 285
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 92. Table: raw.emissions_land_use_forests_elements
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 93. Table: raw.emissions_land_use_forests_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 94. Table: raw.emissions_land_use_forests_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 95. Table: raw.emissions_land_use_forests_sources
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Source Code | BIGINT |
|  Source | VARCHAR |
---
## 96. Table: raw.emissions_livestock
**Row Count (estimated):** 6,650,421
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Source Code | BIGINT |
| Source | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 97. Table: raw.emissions_livestock_areacodes
**Row Count (estimated):** 281
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 98. Table: raw.emissions_livestock_elements
**Row Count (estimated):** 29
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 99. Table: raw.emissions_livestock_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 100. Table: raw.emissions_livestock_itemcodes
**Row Count (estimated):** 24
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | BIGINT |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 101. Table: raw.emissions_livestock_sources
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Source Code | BIGINT |
|  Source | VARCHAR |
---
## 102. Table: raw.emissions_pre_post_production
**Row Count (estimated):** 522,216
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 103. Table: raw.emissions_pre_post_production_areacodes
**Row Count (estimated):** 302
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 104. Table: raw.emissions_pre_post_production_elements
**Row Count (estimated):** 11
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 105. Table: raw.emissions_pre_post_production_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 106. Table: raw.emissions_pre_post_production_itemcodes
**Row Count (estimated):** 15
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 107. Table: raw.emissions_totals
**Row Count (estimated):** 2,500,090
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Source Code | BIGINT |
| Source | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 108. Table: raw.emissions_totals_areacodes
**Row Count (estimated):** 281
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 109. Table: raw.emissions_totals_elements
**Row Count (estimated):** 9
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 110. Table: raw.emissions_totals_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 111. Table: raw.emissions_totals_itemcodes
**Row Count (estimated):** 47
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 112. Table: raw.emissions_totals_sources
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Source Code | BIGINT |
| Source | VARCHAR |
---
## 113. Table: raw.employment_indicators_agriculture
**Row Count (estimated):** 256,389
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Source Code | BIGINT |
| Source | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Sex Code | BIGINT |
| Sex | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 114. Table: raw.employment_indicators_agriculture_areacodes
**Row Count (estimated):** 270
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 115. Table: raw.employment_indicators_agriculture_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 116. Table: raw.employment_indicators_agriculture_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 117. Table: raw.employment_indicators_agriculture_indicators
**Row Count (estimated):** 38
### Columns
| Column Name | Data Type |
|---|---|
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
---
## 118. Table: raw.employment_indicators_agriculture_sexes
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
| Sex Code | BIGINT |
| Sex | VARCHAR |
---
## 119. Table: raw.employment_indicators_agriculture_sources
**Row Count (estimated):** 15
### Columns
| Column Name | Data Type |
|---|---|
| Source Code | BIGINT |
| Source | VARCHAR |
---
## 120. Table: raw.employment_indicators_rural
**Row Count (estimated):** 113,187
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Source Code | BIGINT |
| Source | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Sex Code | BIGINT |
| Sex | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 121. Table: raw.employment_indicators_rural_areacodes
**Row Count (estimated):** 265
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 122. Table: raw.employment_indicators_rural_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 123. Table: raw.employment_indicators_rural_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 124. Table: raw.employment_indicators_rural_indicators
**Row Count (estimated):** 28
### Columns
| Column Name | Data Type |
|---|---|
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
---
## 125. Table: raw.employment_indicators_rural_sexes
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
| Sex Code | BIGINT |
| Sex | VARCHAR |
---
## 126. Table: raw.employment_indicators_rural_sources
**Row Count (estimated):** 11
### Columns
| Column Name | Data Type |
|---|---|
| Source Code | BIGINT |
| Source | VARCHAR |
---
## 127. Table: raw.environment_bioenergy
**Row Count (estimated):** 128,457
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 128. Table: raw.environment_bioenergy_areacodes
**Row Count (estimated):** 288
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 129. Table: raw.environment_bioenergy_elements
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 130. Table: raw.environment_bioenergy_flags
**Row Count (estimated):** 6
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 131. Table: raw.environment_bioenergy_itemcodes
**Row Count (estimated):** 15
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 132. Table: raw.environment_cropland_nutrient_budget
**Row Count (estimated):** 827,796
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 133. Table: raw.environment_cropland_nutrient_budget_areacodes
**Row Count (estimated):** 248
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 134. Table: raw.environment_cropland_nutrient_budget_elements
**Row Count (estimated):** 9
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 135. Table: raw.environment_cropland_nutrient_budget_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 136. Table: raw.environment_cropland_nutrient_budget_itemcodes
**Row Count (estimated):** 12
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 137. Table: raw.environment_emissions_by_sector
**Row Count (estimated):** 509,153
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 138. Table: raw.environment_emissions_by_sector_areacodes
**Row Count (estimated):** 279
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 139. Table: raw.environment_emissions_by_sector_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 140. Table: raw.environment_emissions_intensities
**Row Count (estimated):** 409,511
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 141. Table: raw.environment_emissions_intensities_areacodes
**Row Count (estimated):** 289
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 142. Table: raw.environment_emissions_intensities_elements
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 143. Table: raw.environment_emissions_intensities_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 144. Table: raw.environment_emissions_intensities_itemcodes
**Row Count (estimated):** 14
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 145. Table: raw.environment_food_waste_disposal
**Row Count (estimated):** 67,264
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 146. Table: raw.environment_food_waste_disposal_areacodes
**Row Count (estimated):** 271
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 147. Table: raw.environment_food_waste_disposal_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 148. Table: raw.environment_landcover
**Row Count (estimated):** 210,986
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 149. Table: raw.environment_landcover_areacodes
**Row Count (estimated):** 282
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 150. Table: raw.environment_landcover_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 151. Table: raw.environment_landcover_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 152. Table: raw.environment_landcover_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 153. Table: raw.environment_landuse
**Row Count (estimated):** 165,960
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 154. Table: raw.environment_landuse_areacodes
**Row Count (estimated):** 275
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 155. Table: raw.environment_landuse_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 156. Table: raw.environment_landuse_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | VARCHAR |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 157. Table: raw.environment_livestockmanure
**Row Count (estimated):** 2,555,034
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 158. Table: raw.environment_livestockmanure_areacodes
**Row Count (estimated):** 281
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 159. Table: raw.environment_livestockmanure_elements
**Row Count (estimated):** 10
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 160. Table: raw.environment_livestockmanure_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 161. Table: raw.environment_livestockmanure_itemcodes
**Row Count (estimated):** 24
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | BIGINT |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 162. Table: raw.environment_livestockpatterns
**Row Count (estimated):** 470,577
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 163. Table: raw.environment_livestockpatterns_areacodes
**Row Count (estimated):** 274
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 164. Table: raw.environment_livestockpatterns_elements
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 165. Table: raw.environment_livestockpatterns_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 166. Table: raw.environment_livestockpatterns_itemcodes
**Row Count (estimated):** 14
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | BIGINT |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 167. Table: raw.environment_pesticides
**Row Count (estimated):** 15,452
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 168. Table: raw.environment_pesticides_areacodes
**Row Count (estimated):** 207
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 169. Table: raw.environment_pesticides_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 170. Table: raw.environment_pesticides_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | VARCHAR |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 171. Table: raw.environment_soil_nutrient_budget
**Row Count (estimated):** 196,030
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 172. Table: raw.environment_soil_nutrient_budget_areacodes
**Row Count (estimated):** 242
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 173. Table: raw.environment_soil_nutrient_budget_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 174. Table: raw.environment_temperature_change
**Row Count (estimated):** 590,512
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Months Code | BIGINT |
| Months | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 175. Table: raw.environment_temperature_change_areacodes
**Row Count (estimated):** 288
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 176. Table: raw.environment_temperature_change_elements
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 177. Table: raw.environment_temperature_change_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 178. Table: raw.exchange_rate
**Row Count (estimated):** 145,821
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Element Code | VARCHAR |
| Element | VARCHAR |
| ISO Currency Code | VARCHAR |
| Currency | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Months Code | BIGINT |
| Months | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 179. Table: raw.exchange_rate_areacodes
**Row Count (estimated):** 266
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 180. Table: raw.exchange_rate_currencys
**Row Count (estimated):** 294
### Columns
| Column Name | Data Type |
|---|---|
| ISO Currency Code | VARCHAR |
| Currency | VARCHAR |
---
## 181. Table: raw.exchange_rate_elements
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | VARCHAR |
| Element | VARCHAR |
---
## 182. Table: raw.exchange_rate_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 183. Table: raw.fertilizers_detailedtradematrix
**Row Count (estimated):** 5,300,910
### Columns
| Column Name | Data Type |
|---|---|
| Reporter Country Code | BIGINT |
| Reporter Country Code (M49) | VARCHAR |
| Reporter Countries | VARCHAR |
| Partner Country Code | BIGINT |
| Partner Country Code (M49) | VARCHAR |
| Partner Countries | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 184. Table: raw.fertilizers_detailedtradematrix_elements
**Row Count (estimated):** 10
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 185. Table: raw.fertilizers_detailedtradematrix_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 186. Table: raw.fertilizers_detailedtradematrix_itemcodes
**Row Count (estimated):** 23
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | BIGINT |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 187. Table: raw.food_aid_shipments_wfp
**Row Count (estimated):** 31,114
### Columns
| Column Name | Data Type |
|---|---|
| Recipient Country Code | BIGINT |
| Recipient Country Code (M49) | VARCHAR |
| Recipient Country | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 188. Table: raw.food_aid_shipments_wfp_areacodes
**Row Count (estimated):** 183
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 189. Table: raw.food_aid_shipments_wfp_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 190. Table: raw.food_and_diet_individual_quantitative_dietary_data
**Row Count (estimated):** 1,164,769
### Columns
| Column Name | Data Type |
|---|---|
| Survey Code | VARCHAR |
| Survey | VARCHAR |
| Geographic Level Code | BIGINT |
| Geographic Level | VARCHAR |
| Population Group Code | VARCHAR |
| Population Group | VARCHAR |
| Food Group Code | VARCHAR |
| Food Group | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Sex Code | BIGINT |
| Sex | VARCHAR |
| Unit | VARCHAR |
| Value | VARCHAR |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 191. Table: raw.food_and_diet_individual_quantitative_dietary_data_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 192. Table: raw.food_security_data
**Row Count (estimated):** 279,470
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | VARCHAR |
| Unit | VARCHAR |
| Value | VARCHAR |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 193. Table: raw.food_security_data_areacodes
**Row Count (estimated):** 249
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 194. Table: raw.food_security_data_elements
**Row Count (estimated):** 14
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 195. Table: raw.food_security_data_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 196. Table: raw.food_security_data_itemcodes
**Row Count (estimated):** 75
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | VARCHAR |
| Item | VARCHAR |
---
## 197. Table: raw.foodbalancesheets
**Row Count (estimated):** 4,820,497
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (FBS) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 198. Table: raw.foodbalancesheets_areacodes
**Row Count (estimated):** 426
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 199. Table: raw.foodbalancesheets_elements
**Row Count (estimated):** 21
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 200. Table: raw.foodbalancesheets_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 201. Table: raw.foodbalancesheets_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 202. Table: raw.foodbalancesheetshistoric
**Row Count (estimated):** 11,479,903
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (FBS) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 203. Table: raw.foodbalancesheetshistoric_areacodes
**Row Count (estimated):** 434
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 204. Table: raw.foodbalancesheetshistoric_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 205. Table: raw.foodbalancesheetshistoric_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | VARCHAR |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 206. Table: raw.forestry
**Row Count (estimated):** 2,457,869
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 207. Table: raw.forestry_areacodes
**Row Count (estimated):** 285
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 208. Table: raw.forestry_elements
**Row Count (estimated):** 8
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 209. Table: raw.forestry_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 210. Table: raw.forestry_itemcodes
**Row Count (estimated):** 104
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 211. Table: raw.forestry_pulp_paper_survey
**Row Count (estimated):** 67,538
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 212. Table: raw.forestry_pulp_paper_survey_areacodes
**Row Count (estimated):** 89
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 213. Table: raw.forestry_pulp_paper_survey_elements
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 214. Table: raw.forestry_pulp_paper_survey_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 215. Table: raw.forestry_pulp_paper_survey_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 216. Table: raw.forestry_trade_flows
**Row Count (estimated):** 2,829,802
### Columns
| Column Name | Data Type |
|---|---|
| Reporter Country Code | BIGINT |
| Reporter Country Code (M49) | VARCHAR |
| Reporter Countries | VARCHAR |
| Partner Country Code | BIGINT |
| Partner Country Code (M49) | VARCHAR |
| Partner Countries | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 217. Table: raw.forestry_trade_flows_areacodes
**Row Count (estimated):** 423
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 218. Table: raw.forestry_trade_flows_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 219. Table: raw.forestry_trade_flows_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | VARCHAR |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 220. Table: raw.holidays
**Row Count (estimated):** 88,537
### Columns
| Column Name | Data Type |
|---|---|
| country_code | VARCHAR |
| country_name | VARCHAR |
| local_name | VARCHAR |
| name | VARCHAR |
| fixed | INTEGER |
| global | INTEGER |
| counties | INTEGER |
| launch_year | INTEGER |
| types | VARCHAR |
| date | DATE |
---
## 221. Table: raw.household_consumption_and_expenditure_surveys_food_and_diet
**Row Count (estimated):** 1,166,330
### Columns
| Column Name | Data Type |
|---|---|
| Survey Code | VARCHAR |
| Survey | VARCHAR |
| Geographic Level Code | VARCHAR |
| Geographic Level | VARCHAR |
| Food Group Code | VARCHAR |
| Food Group | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Element Code | VARCHAR |
| Element | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 222. Table: raw.household_consumption_and_expenditure_surveys_food_and_diet_elements
**Row Count (estimated):** 12
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | VARCHAR |
| Element | VARCHAR |
---
## 223. Table: raw.household_consumption_and_expenditure_surveys_food_and_diet_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 224. Table: raw.household_consumption_and_expenditure_surveys_food_and_diet_geographiclevels
**Row Count (estimated):** 774
### Columns
| Column Name | Data Type |
|---|---|
| Geographic Level Code | VARCHAR |
| M49 Code | VARCHAR |
| Geographic Level | VARCHAR |
---
## 225. Table: raw.household_consumption_and_expenditure_surveys_food_and_diet_indicators
**Row Count (estimated):** 19
### Columns
| Column Name | Data Type |
|---|---|
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
---
## 226. Table: raw.household_consumption_and_expenditure_surveys_food_and_diet_surveys
**Row Count (estimated):** 59
### Columns
| Column Name | Data Type |
|---|---|
| Survey Code | VARCHAR |
| Survey | VARCHAR |
---
## 227. Table: raw.indicators_from_household_surveys
**Row Count (estimated):** 148,620
### Columns
| Column Name | Data Type |
|---|---|
| Survey Code | VARCHAR |
| Survey | VARCHAR |
| Breakdown Variable Code | BIGINT |
| Breakdown Variable | VARCHAR |
| Breadown by Sex of the Household Head Code | BIGINT |
| Breadown by Sex of the Household Head | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 228. Table: raw.indicators_from_household_surveys_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 229. Table: raw.individual_quantitative_dietary_data_food_and_diet
**Row Count (estimated):** 2,191,084
### Columns
| Column Name | Data Type |
|---|---|
| Survey Code | VARCHAR |
| Survey | VARCHAR |
| Geographic Level Code | BIGINT |
| Geographic Level | VARCHAR |
| Population Age Group Code | VARCHAR |
| Population Age Group | VARCHAR |
| Food Group Code | VARCHAR |
| Food Group | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Sex Code | BIGINT |
| Sex | VARCHAR |
| Unit | VARCHAR |
| Value | VARCHAR |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 230. Table: raw.individual_quantitative_dietary_data_food_and_diet_elements
**Row Count (estimated):** 6
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 231. Table: raw.individual_quantitative_dietary_data_food_and_diet_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 232. Table: raw.individual_quantitative_dietary_data_food_and_diet_indicators
**Row Count (estimated):** 27
### Columns
| Column Name | Data Type |
|---|---|
|  Indicator Code | BIGINT |
|  Indicator | VARCHAR |
---
## 233. Table: raw.individual_quantitative_dietary_data_food_and_diet_populationagegroups
**Row Count (estimated):** 11
### Columns
| Column Name | Data Type |
|---|---|
|  Population Age Group | VARCHAR |
|  Population Age Group_duplicated_0 | VARCHAR |
---
## 234. Table: raw.individual_quantitative_dietary_data_food_and_diet_sexs
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
|  Sex Code | BIGINT |
|  Sex | VARCHAR |
---
## 235. Table: raw.individual_quantitative_dietary_data_food_and_diet_surveys
**Row Count (estimated):** 8
### Columns
| Column Name | Data Type |
|---|---|
|  Survey Code | VARCHAR |
|  Survey | VARCHAR |
---
## 236. Table: raw.inputs_fertilizersarchive
**Row Count (estimated):** 178,192
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 237. Table: raw.inputs_fertilizersarchive_areacodes
**Row Count (estimated):** 273
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 238. Table: raw.inputs_fertilizersarchive_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 239. Table: raw.inputs_fertilizersnutrient
**Row Count (estimated):** 241,859
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 240. Table: raw.inputs_fertilizersnutrient_areacodes
**Row Count (estimated):** 311
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 241. Table: raw.inputs_fertilizersnutrient_elements
**Row Count (estimated):** 7
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 242. Table: raw.inputs_fertilizersnutrient_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 243. Table: raw.inputs_fertilizersnutrient_itemcodes
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | BIGINT |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 244. Table: raw.inputs_fertilizersproduct
**Row Count (estimated):** 303,498
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 245. Table: raw.inputs_fertilizersproduct_areacodes
**Row Count (estimated):** 310
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 246. Table: raw.inputs_fertilizersproduct_elements
**Row Count (estimated):** 6
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 247. Table: raw.inputs_fertilizersproduct_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 248. Table: raw.inputs_fertilizersproduct_itemcodes
**Row Count (estimated):** 23
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | BIGINT |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 249. Table: raw.inputs_landuse
**Row Count (estimated):** 413,211
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 250. Table: raw.inputs_landuse_areacodes
**Row Count (estimated):** 284
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 251. Table: raw.inputs_landuse_elements
**Row Count (estimated):** 9
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 252. Table: raw.inputs_landuse_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 253. Table: raw.inputs_landuse_itemcodes
**Row Count (estimated):** 51
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 254. Table: raw.inputs_pesticides_trade
**Row Count (estimated):** 190,740
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 255. Table: raw.inputs_pesticides_trade_areacodes
**Row Count (estimated):** 300
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 256. Table: raw.inputs_pesticides_trade_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 257. Table: raw.inputs_pesticides_trade_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 258. Table: raw.inputs_pesticides_trade_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 259. Table: raw.inputs_pesticides_use
**Row Count (estimated):** 103,622
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 260. Table: raw.inputs_pesticides_use_areacodes
**Row Count (estimated):** 256
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 261. Table: raw.inputs_pesticides_use_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 262. Table: raw.inputs_pesticides_use_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 263. Table: raw.inputs_pesticides_use_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 264. Table: raw.investment_capitalstock
**Row Count (estimated):** 144,944
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 265. Table: raw.investment_capitalstock_areacodes
**Row Count (estimated):** 232
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 266. Table: raw.investment_capitalstock_elements
**Row Count (estimated):** 16
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 267. Table: raw.investment_capitalstock_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 268. Table: raw.investment_capitalstock_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 269. Table: raw.investment_countryinvestmentstatisticsprofile
**Row Count (estimated):** 66,447
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 270. Table: raw.investment_countryinvestmentstatisticsprofile_areacodes
**Row Count (estimated):** 258
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 271. Table: raw.investment_countryinvestmentstatisticsprofile_elements
**Row Count (estimated):** 8
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 272. Table: raw.investment_countryinvestmentstatisticsprofile_flags
**Row Count (estimated):** 6
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 273. Table: raw.investment_countryinvestmentstatisticsprofile_itemcodes
**Row Count (estimated):** 6
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 274. Table: raw.investment_creditagriculture
**Row Count (estimated):** 62,899
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 275. Table: raw.investment_creditagriculture_areacodes
**Row Count (estimated):** 212
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 276. Table: raw.investment_creditagriculture_elements
**Row Count (estimated):** 7
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 277. Table: raw.investment_creditagriculture_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 278. Table: raw.investment_creditagriculture_itemcodes
**Row Count (estimated):** 8
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 279. Table: raw.investment_foreigndirectinvestment
**Row Count (estimated):** 40,442
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 280. Table: raw.investment_foreigndirectinvestment_areacodes
**Row Count (estimated):** 282
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 281. Table: raw.investment_foreigndirectinvestment_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 282. Table: raw.investment_foreigndirectinvestment_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 283. Table: raw.investment_foreigndirectinvestment_itemcodes
**Row Count (estimated):** 0
### Columns
| Column Name | Data Type |
|---|---|
|  Item Code | VARCHAR |
|  CPC Code | VARCHAR |
|  Item | VARCHAR |
---
## 284. Table: raw.investment_governmentexpenditure
**Row Count (estimated):** 156,256
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 285. Table: raw.investment_governmentexpenditure_areacodes
**Row Count (estimated):** 287
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 286. Table: raw.investment_governmentexpenditure_elements
**Row Count (estimated):** 7
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 287. Table: raw.investment_governmentexpenditure_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 288. Table: raw.investment_governmentexpenditure_itemcodes
**Row Count (estimated):** 47
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 289. Table: raw.investment_machinery
**Row Count (estimated):** 146,834
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 290. Table: raw.investment_machinery_areacodes
**Row Count (estimated):** 277
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 291. Table: raw.investment_machinery_flags
**Row Count (estimated):** 3
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
| Description | VARCHAR |
---
## 292. Table: raw.investment_machineryarchive
**Row Count (estimated):** 328,932
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 293. Table: raw.investment_machineryarchive_areacodes
**Row Count (estimated):** 277
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 294. Table: raw.investment_machineryarchive_elements
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 295. Table: raw.investment_machineryarchive_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 296. Table: raw.investment_machineryarchive_itemcodes
**Row Count (estimated):** 7
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 297. Table: raw.macro_statistics_key_indicators
**Row Count (estimated):** 708,632
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 298. Table: raw.macro_statistics_key_indicators_areacodes
**Row Count (estimated):** 252
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 299. Table: raw.macro_statistics_key_indicators_elements
**Row Count (estimated):** 20
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 300. Table: raw.macro_statistics_key_indicators_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 301. Table: raw.macro_statistics_key_indicators_itemcodes
**Row Count (estimated):** 11
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 302. Table: raw.minimum_dietary_diversity_for_women_mdd_w_food_and_diet
**Row Count (estimated):** 1,223
### Columns
| Column Name | Data Type |
|---|---|
| Survey Code | VARCHAR |
| Survey | VARCHAR |
| Food Group Code | VARCHAR |
| Food Group | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Geographic Level Code | BIGINT |
| Geographic Level | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 303. Table: raw.minimum_dietary_diversity_for_women_mdd_w_food_and_diet_elements
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 304. Table: raw.minimum_dietary_diversity_for_women_mdd_w_food_and_diet_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 305. Table: raw.minimum_dietary_diversity_for_women_mdd_w_food_and_diet_indicators
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
|  Indicator Code | BIGINT |
|  Indicator | VARCHAR |
---
## 306. Table: raw.minimum_dietary_diversity_for_women_mdd_w_food_and_diet_surveys
**Row Count (estimated):** 25
### Columns
| Column Name | Data Type |
|---|---|
|  Survey Code | VARCHAR |
|  Survey | VARCHAR |
---
## 307. Table: raw.population
**Row Count (estimated):** 168,405
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 308. Table: raw.population_areacodes
**Row Count (estimated):** 282
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 309. Table: raw.population_elements
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 310. Table: raw.population_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 311. Table: raw.population_itemcodes
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| Item | VARCHAR |
---
## 312. Table: raw.prices
**Row Count (estimated):** 1,319,563
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Months Code | BIGINT |
| Months | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 313. Table: raw.prices_areacodes
**Row Count (estimated):** 233
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 314. Table: raw.prices_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 315. Table: raw.prices_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 316. Table: raw.prices_itemcodes
**Row Count (estimated):** 242
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 317. Table: raw.pricesarchive
**Row Count (estimated):** 139,713
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 318. Table: raw.pricesarchive_areacodes
**Row Count (estimated):** 185
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 319. Table: raw.pricesarchive_elements
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 320. Table: raw.pricesarchive_flags
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 321. Table: raw.pricesarchive_itemcodes
**Row Count (estimated):** 236
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 322. Table: raw.production_crops_livestock
**Row Count (estimated):** 4,209,110
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 323. Table: raw.production_crops_livestock_areacodes
**Row Count (estimated):** 244
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 324. Table: raw.production_crops_livestock_elements
**Row Count (estimated):** 20
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 325. Table: raw.production_crops_livestock_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 326. Table: raw.production_crops_livestock_itemcodes
**Row Count (estimated):** 312
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | VARCHAR |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 327. Table: raw.production_indices
**Row Count (estimated):** 1,995,192
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
---
## 328. Table: raw.production_indices_areacodes
**Row Count (estimated):** 245
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 329. Table: raw.production_indices_elements
**Row Count (estimated):** 2
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 330. Table: raw.production_indices_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 331. Table: raw.production_indices_itemcodes
**Row Count (estimated):** 204
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 332. Table: raw.rural_livelihoods_indicators
**Row Count (estimated):** 38,918
### Columns
| Column Name | Data Type |
|---|---|
| Survey Code | VARCHAR |
| Survey | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Qualifier Code | VARCHAR |
| Qualifier | VARCHAR |
| Source Code | BIGINT |
| Source | VARCHAR |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 333. Table: raw.rural_livelihoods_indicators_elements
**Row Count (estimated):** 13
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 334. Table: raw.rural_livelihoods_indicators_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 335. Table: raw.rural_livelihoods_indicators_indicators
**Row Count (estimated):** 143
### Columns
| Column Name | Data Type |
|---|---|
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
---
## 336. Table: raw.rural_livelihoods_indicators_qualifiers
**Row Count (estimated):** 9
### Columns
| Column Name | Data Type |
|---|---|
| Qualifier Code | VARCHAR |
| Qualifier | VARCHAR |
---
## 337. Table: raw.rural_livelihoods_indicators_sources
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Source Code | BIGINT |
| Source | VARCHAR |
---
## 338. Table: raw.rural_livelihoods_indicators_surveys
**Row Count (estimated):** 103
### Columns
| Column Name | Data Type |
|---|---|
| Survey Code | VARCHAR |
| Survey | VARCHAR |
---
## 339. Table: raw.sdg_bulkdownloads
**Row Count (estimated):** 464,787
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | VARCHAR |
| Item Code (SDG) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | VARCHAR |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 340. Table: raw.sdg_bulkdownloads_areacodes
**Row Count (estimated):** 305
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 341. Table: raw.sdg_bulkdownloads_elements
**Row Count (estimated):** 16
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 342. Table: raw.sdg_bulkdownloads_flags
**Row Count (estimated):** 7
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 343. Table: raw.sdg_bulkdownloads_itemcodes
**Row Count (estimated):** 279
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | VARCHAR |
| SDG Code | VARCHAR |
| Item | VARCHAR |
---
## 344. Table: raw.sua_crops_livestock
**Row Count (estimated):** 11,615,212
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 345. Table: raw.sua_crops_livestock_areacodes
**Row Count (estimated):** 213
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 346. Table: raw.sua_crops_livestock_elements
**Row Count (estimated):** 21
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 347. Table: raw.sua_crops_livestock_flags
**Row Count (estimated):** 6
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 348. Table: raw.sua_crops_livestock_itemcodes
**Row Count (estimated):** 485
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | VARCHAR |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 349. Table: raw.suite_of_gender_indicators
**Row Count (estimated):** 315,014
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Item Code | VARCHAR |
| Item Code (SDG) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Sex Code | BIGINT |
| Sex Code (SDG) | VARCHAR |
| Sex | VARCHAR |
| Population Age Group Code | VARCHAR |
| Population Age Group | VARCHAR |
| Geographic Level Code | BIGINT |
| Geographic Level | VARCHAR |
| Activity Code | BIGINT |
| Activity Code (SDG) | VARCHAR |
| Activity | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 350. Table: raw.suite_of_gender_indicators_activities
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Activity Code | BIGINT |
| Activity | VARCHAR |
---
## 351. Table: raw.suite_of_gender_indicators_areacodes
**Row Count (estimated):** 278
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| M49 Code | VARCHAR |
| Area | VARCHAR |
---
## 352. Table: raw.suite_of_gender_indicators_elements
**Row Count (estimated):** 6
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 353. Table: raw.suite_of_gender_indicators_flags
**Row Count (estimated):** 5
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 354. Table: raw.suite_of_gender_indicators_geographiclevels
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Geographic Level Code | BIGINT |
| Geographic Level | VARCHAR |
---
## 355. Table: raw.suite_of_gender_indicators_itemcodes
**Row Count (estimated):** 146
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | VARCHAR |
| SDG Code | VARCHAR |
| Item | VARCHAR |
---
## 356. Table: raw.suite_of_gender_indicators_populationagegroups
**Row Count (estimated):** 40
### Columns
| Column Name | Data Type |
|---|---|
| Population Age Group Code | VARCHAR |
| Population Age Group | VARCHAR |
---
## 357. Table: raw.suite_of_gender_indicators_sexes
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Sex Code | BIGINT |
| Sex | VARCHAR |
---
## 358. Table: raw.supply_utilization_accounts_food_and_diet
**Row Count (estimated):** 743,139
### Columns
| Column Name | Data Type |
|---|---|
| Area Code | BIGINT |
| Area Code (M49) | VARCHAR |
| Area | VARCHAR |
| Food Group Code | VARCHAR |
| Food Group | VARCHAR |
| Indicator Code | BIGINT |
| Indicator | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Year Code | BIGINT |
| Year | BIGINT |
| Unit | VARCHAR |
| Value | DOUBLE |
| Flag | VARCHAR |
| Note | VARCHAR |
---
## 359. Table: raw.supply_utilization_accounts_food_and_diet_areacodes
**Row Count (estimated):** 213
### Columns
| Column Name | Data Type |
|---|---|
|  Area Code | BIGINT |
|  M49 Code | VARCHAR |
|  Area | VARCHAR |
---
## 360. Table: raw.supply_utilization_accounts_food_and_diet_elements
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
|  Element Code | BIGINT |
|  Element | VARCHAR |
---
## 361. Table: raw.supply_utilization_accounts_food_and_diet_flags
**Row Count (estimated):** 1
### Columns
| Column Name | Data Type |
|---|---|
|  Flag | VARCHAR |
|  Description | VARCHAR |
---
## 362. Table: raw.supply_utilization_accounts_food_and_diet_indicators
**Row Count (estimated):** 26
### Columns
| Column Name | Data Type |
|---|---|
|  Indicator Code | BIGINT |
|  Indicator | VARCHAR |
---
## 363. Table: raw.trade_elements
**Row Count (estimated):** 10
### Columns
| Column Name | Data Type |
|---|---|
| Element Code | BIGINT |
| Element | VARCHAR |
---
## 364. Table: raw.trade_flags
**Row Count (estimated):** 4
### Columns
| Column Name | Data Type |
|---|---|
| Flag | VARCHAR |
|  Description | VARCHAR |
---
## 365. Table: raw.trade_item_codes
**Row Count (estimated):** 572
### Columns
| Column Name | Data Type |
|---|---|
| Item Code | BIGINT |
| CPC Code | VARCHAR |
| Item | VARCHAR |
---
## 366. Table: raw.trade_matrix
**Row Count (estimated):** 6,640,547
### Columns
| Column Name | Data Type |
|---|---|
| Reporter Country Code | BIGINT |
| Reporter Country Code (M49) | VARCHAR |
| Reporter Countries | VARCHAR |
| Partner Country Code | BIGINT |
| Partner Country Code (M49) | VARCHAR |
| Partner Countries | VARCHAR |
| Item Code | BIGINT |
| Item Code (CPC) | VARCHAR |
| Item | VARCHAR |
| Element Code | BIGINT |
| Element | VARCHAR |
| Unit | VARCHAR |
| Y1986 | VARCHAR |
| Y1986F | VARCHAR |
| Y1987 | VARCHAR |
| Y1987F | VARCHAR |
| Y1988 | VARCHAR |
| Y1988F | VARCHAR |
| Y1989 | VARCHAR |
| Y1989F | VARCHAR |
| Y1990 | VARCHAR |
| Y1990F | VARCHAR |
| Y1991 | VARCHAR |
| Y1991F | VARCHAR |
| Y1992 | VARCHAR |
| Y1992F | VARCHAR |
| Y1993 | VARCHAR |
| Y1993F | VARCHAR |
| Y1994 | VARCHAR |
| Y1994F | VARCHAR |
| Y1995 | VARCHAR |
| Y1995F | VARCHAR |
| Y1996 | DOUBLE |
| Y1996F | VARCHAR |
| Y1997 | DOUBLE |
| Y1997F | VARCHAR |
| Y1998 | VARCHAR |
| Y1998F | VARCHAR |
| Y1999 | DOUBLE |
| Y1999F | VARCHAR |
| Y2000 | DOUBLE |
| Y2000F | VARCHAR |
| Y2001 | DOUBLE |
| Y2001F | VARCHAR |
| Y2002 | DOUBLE |
| Y2002F | VARCHAR |
| Y2003 | DOUBLE |
| Y2003F | VARCHAR |
| Y2004 | DOUBLE |
| Y2004F | VARCHAR |
| Y2005 | DOUBLE |
| Y2005F | VARCHAR |
| Y2006 | DOUBLE |
| Y2006F | VARCHAR |
| Y2007 | DOUBLE |
| Y2007F | VARCHAR |
| Y2008 | DOUBLE |
| Y2008F | VARCHAR |
| Y2009 | DOUBLE |
| Y2009F | VARCHAR |
| Y2010 | DOUBLE |
| Y2010F | VARCHAR |
| Y2011 | DOUBLE |
| Y2011F | VARCHAR |
| Y2012 | DOUBLE |
| Y2012F | VARCHAR |
| Y2013 | DOUBLE |
| Y2013F | VARCHAR |
| Y2014 | DOUBLE |
| Y2014F | VARCHAR |
| Y2015 | DOUBLE |
| Y2015F | VARCHAR |
| Y2016 | DOUBLE |
| Y2016F | VARCHAR |
| Y2017 | DOUBLE |
| Y2017F | VARCHAR |
| Y2018 | DOUBLE |
| Y2018F | VARCHAR |
| Y2019 | DOUBLE |
| Y2019F | VARCHAR |
| Y2020 | DOUBLE |
| Y2020F | VARCHAR |
| Y2021 | DOUBLE |
| Y2021F | VARCHAR |
| Y2022 | VARCHAR |
| Y2022F | VARCHAR |
| Y2023 | DOUBLE |
| Y2023F | VARCHAR |
| Y2024 | DOUBLE |
| Y2024F | VARCHAR |
---
## 367. Table: raw.trade_partner_countries
**Row Count (estimated):** 255
### Columns
| Column Name | Data Type |
|---|---|
| Partner Country Code | BIGINT |
| M49 Code | VARCHAR |
| Partner Countries | VARCHAR |
---
## 368. Table: raw.trade_reporter_countries
**Row Count (estimated):** 232
### Columns
| Column Name | Data Type |
|---|---|
| Reporter Country Code | BIGINT |
| M49 Code | VARCHAR |
| Reporter Countries | VARCHAR |
---
## 369. Table: raw.weather
**Row Count (estimated):** 76,440
### Columns
| Column Name | Data Type |
|---|---|
| country_iso2 | VARCHAR |
| country_name | VARCHAR |
| latitude | DOUBLE |
| longitude | DOUBLE |
| year | BIGINT |
| month | BIGINT |
| temp_c | DOUBLE |
| precip_mm_day | DOUBLE |
---
# Schema: staging (350 tables)
## 370. Table: staging.stg_asti_expenditures
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| cost_category_code | VARCHAR |
| cost_category | VARCHAR |
| institution_code | VARCHAR |
| institution | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 371. Table: staging.stg_asti_expenditures_archive
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 372. Table: staging.stg_asti_expenditures_archive_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 373. Table: staging.stg_asti_expenditures_archive_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 374. Table: staging.stg_asti_expenditures_archive_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 375. Table: staging.stg_asti_expenditures_archive_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 376. Table: staging.stg_asti_expenditures_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 377. Table: staging.stg_asti_expenditures_costcategorys
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| cost_category_code | VARCHAR |
| cost_category | VARCHAR |
---
## 378. Table: staging.stg_asti_expenditures_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 379. Table: staging.stg_asti_expenditures_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| indicator_code | VARCHAR |
| indicator | VARCHAR |
---
## 380. Table: staging.stg_asti_expenditures_institutions
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| institution_code | VARCHAR |
| institution | VARCHAR |
---
## 381. Table: staging.stg_asti_researchers
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| degree_code | VARCHAR |
| degree | VARCHAR |
| sex_code | VARCHAR |
| sex_code_sdg | VARCHAR |
| sex | VARCHAR |
| institution_code | VARCHAR |
| institution | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 382. Table: staging.stg_asti_researchers_archive
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 383. Table: staging.stg_asti_researchers_archive_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 384. Table: staging.stg_asti_researchers_archive_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 385. Table: staging.stg_asti_researchers_archive_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 386. Table: staging.stg_asti_researchers_archive_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 387. Table: staging.stg_asti_researchers_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 388. Table: staging.stg_asti_researchers_degrees
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| degree_code | VARCHAR |
| degree | VARCHAR |
---
## 389. Table: staging.stg_asti_researchers_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 390. Table: staging.stg_asti_researchers_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| indicator_code | VARCHAR |
| indicator | VARCHAR |
---
## 391. Table: staging.stg_asti_researchers_institutions
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| institution_code | VARCHAR |
| institution | VARCHAR |
---
## 392. Table: staging.stg_asti_researchers_sexes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| sex_code | VARCHAR |
| sex | VARCHAR |
---
## 393. Table: staging.stg_climate_change_emissions_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 394. Table: staging.stg_climate_change_emissions_indicators_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 395. Table: staging.stg_climate_change_emissions_indicators_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 396. Table: staging.stg_climate_change_emissions_indicators_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 397. Table: staging.stg_commodity_indices
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| total_index | DOUBLE |
| energy | DOUBLE |
| non_energy | DOUBLE |
| agriculture | DOUBLE |
| beverages | DOUBLE |
| food | DOUBLE |
| oils_meals | DOUBLE |
| grains | DOUBLE |
| other_food | DOUBLE |
| raw_materials | DOUBLE |
| timber | DOUBLE |
| other_raw_mat | DOUBLE |
| fertilizers | DOUBLE |
| metals_minerals | DOUBLE |
| base_metals_ex_iron_ore | DOUBLE |
| precious_metals | DOUBLE |
| date | DATE |
---
## 398. Table: staging.stg_commodity_prices
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| date | DATE |
| commodity | VARCHAR |
| unit | VARCHAR |
| price | DOUBLE |
---
## 399. Table: staging.stg_commoditybalances_non_food
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 400. Table: staging.stg_commoditybalances_non_food_2010
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 401. Table: staging.stg_commoditybalances_non_food_2010_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 402. Table: staging.stg_commoditybalances_non_food_2010_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 403. Table: staging.stg_commoditybalances_non_food_2010_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 404. Table: staging.stg_commoditybalances_non_food_2010_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 405. Table: staging.stg_commoditybalances_non_food_2013_old_methodology
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 406. Table: staging.stg_commoditybalances_non_food_2013_old_methodology_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 407. Table: staging.stg_commoditybalances_non_food_2013_old_methodology_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 408. Table: staging.stg_commoditybalances_non_food_2013_old_methodology_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 409. Table: staging.stg_commoditybalances_non_food_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 410. Table: staging.stg_commoditybalances_non_food_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 411. Table: staging.stg_commoditybalances_non_food_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 412. Table: staging.stg_consumerpriceindices
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| months_code | VARCHAR |
| months | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 413. Table: staging.stg_consumerpriceindices_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 414. Table: staging.stg_consumerpriceindices_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 415. Table: staging.stg_consumerpriceindices_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 416. Table: staging.stg_consumerpriceindices_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 417. Table: staging.stg_cost_affordability_healthy_diet_coahd
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| release_code | VARCHAR |
| release | VARCHAR |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
---
## 418. Table: staging.stg_cost_affordability_healthy_diet_coahd_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 419. Table: staging.stg_cost_affordability_healthy_diet_coahd_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 420. Table: staging.stg_cost_affordability_healthy_diet_coahd_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 421. Table: staging.stg_cost_affordability_healthy_diet_coahd_releases
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| release_code | VARCHAR |
| release | VARCHAR |
---
## 422. Table: staging.stg_country_codes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| country | VARCHAR |
| latitude | DOUBLE |
| longitude | DOUBLE |
| name | VARCHAR |
---
## 423. Table: staging.stg_deflators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 424. Table: staging.stg_deflators_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 425. Table: staging.stg_deflators_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 426. Table: staging.stg_deflators_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 427. Table: staging.stg_development_assistance_to_agriculture
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| donor_code | VARCHAR |
| donor_code_m49 | VARCHAR |
| donor | VARCHAR |
| recipient_country_code | VARCHAR |
| recipient_country_code_m49 | VARCHAR |
| recipient_country | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| purpose_code | VARCHAR |
| purpose | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 428. Table: staging.stg_development_assistance_to_agriculture_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 429. Table: staging.stg_development_assistance_to_agriculture_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 430. Table: staging.stg_development_assistance_to_agriculture_purposes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| purpose_code | VARCHAR |
| purpose | VARCHAR |
---
## 431. Table: staging.stg_emdat
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| disno | VARCHAR |
| historic | VARCHAR |
| classification_key | VARCHAR |
| disaster_group | VARCHAR |
| disaster_subgroup | VARCHAR |
| disaster_type | VARCHAR |
| disaster_subtype | VARCHAR |
| external_ids | VARCHAR |
| event_name | VARCHAR |
| iso | VARCHAR |
| country | VARCHAR |
| subregion | VARCHAR |
| region | VARCHAR |
| location | VARCHAR |
| origin | VARCHAR |
| associated_types | VARCHAR |
| ofda_bha_response | VARCHAR |
| appeal | VARCHAR |
| declaration | VARCHAR |
| aid_contribution_000_us | DOUBLE |
| magnitude | DOUBLE |
| magnitude_scale | VARCHAR |
| latitude | DOUBLE |
| longitude | DOUBLE |
| river_basin | VARCHAR |
| start_year | BIGINT |
| start_month | DOUBLE |
| start_day | DOUBLE |
| end_year | BIGINT |
| end_month | DOUBLE |
| end_day | DOUBLE |
| total_deaths | DOUBLE |
| no_injured | DOUBLE |
| no_affected | DOUBLE |
| no_homeless | DOUBLE |
| total_affected | DOUBLE |
| reconstruction_costs_000_us | DOUBLE |
| reconstruction_costs_adjusted_000_us | DOUBLE |
| insured_damage_000_us | DOUBLE |
| insured_damage_adjusted_000_us | DOUBLE |
| total_damage_000_us | DOUBLE |
| total_damage_adjusted_000_us | DOUBLE |
| cpi | DOUBLE |
| admin_units | VARCHAR |
| gadm_admin_units | VARCHAR |
| entry_date | DATE |
| last_update | DATE |
---
## 432. Table: staging.stg_emissions_agriculture_energy
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 433. Table: staging.stg_emissions_agriculture_energy_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 434. Table: staging.stg_emissions_agriculture_energy_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 435. Table: staging.stg_emissions_agriculture_energy_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 436. Table: staging.stg_emissions_crops
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 437. Table: staging.stg_emissions_crops_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 438. Table: staging.stg_emissions_crops_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 439. Table: staging.stg_emissions_crops_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 440. Table: staging.stg_emissions_crops_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 441. Table: staging.stg_emissions_crops_sources
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| source_code | VARCHAR |
| source | VARCHAR |
---
## 442. Table: staging.stg_emissions_drained_organic_soils
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 443. Table: staging.stg_emissions_drained_organic_soils_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 444. Table: staging.stg_emissions_drained_organic_soils_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 445. Table: staging.stg_emissions_drained_organic_soils_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 446. Table: staging.stg_emissions_drained_organic_soils_sources
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| source_code | VARCHAR |
| source | VARCHAR |
---
## 447. Table: staging.stg_emissions_land_use_fires
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 448. Table: staging.stg_emissions_land_use_fires_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 449. Table: staging.stg_emissions_land_use_fires_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 450. Table: staging.stg_emissions_land_use_fires_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 451. Table: staging.stg_emissions_land_use_fires_sources
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| source_code | VARCHAR |
| source | VARCHAR |
---
## 452. Table: staging.stg_emissions_land_use_forests
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 453. Table: staging.stg_emissions_land_use_forests_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 454. Table: staging.stg_emissions_land_use_forests_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 455. Table: staging.stg_emissions_land_use_forests_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 456. Table: staging.stg_emissions_land_use_forests_sources
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| source_code | VARCHAR |
| source | VARCHAR |
---
## 457. Table: staging.stg_emissions_livestock
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 458. Table: staging.stg_emissions_livestock_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 459. Table: staging.stg_emissions_livestock_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 460. Table: staging.stg_emissions_livestock_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 461. Table: staging.stg_emissions_livestock_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 462. Table: staging.stg_emissions_livestock_sources
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| source_code | VARCHAR |
| source | VARCHAR |
---
## 463. Table: staging.stg_emissions_pre_post_production
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 464. Table: staging.stg_emissions_pre_post_production_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 465. Table: staging.stg_emissions_pre_post_production_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 466. Table: staging.stg_emissions_pre_post_production_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 467. Table: staging.stg_emissions_pre_post_production_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 468. Table: staging.stg_emissions_totals
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 469. Table: staging.stg_emissions_totals_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 470. Table: staging.stg_emissions_totals_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 471. Table: staging.stg_emissions_totals_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 472. Table: staging.stg_emissions_totals_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 473. Table: staging.stg_emissions_totals_sources
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| source_code | VARCHAR |
| source | VARCHAR |
---
## 474. Table: staging.stg_employment_indicators_agriculture
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| source_code | VARCHAR |
| source | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 475. Table: staging.stg_employment_indicators_agriculture_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 476. Table: staging.stg_employment_indicators_agriculture_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 477. Table: staging.stg_employment_indicators_agriculture_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 478. Table: staging.stg_employment_indicators_agriculture_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| indicator_code | VARCHAR |
| indicator | VARCHAR |
---
## 479. Table: staging.stg_employment_indicators_agriculture_sexes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| sex_code | VARCHAR |
| sex | VARCHAR |
---
## 480. Table: staging.stg_employment_indicators_agriculture_sources
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| source_code | VARCHAR |
| source | VARCHAR |
---
## 481. Table: staging.stg_employment_indicators_rural
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| source_code | VARCHAR |
| source | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 482. Table: staging.stg_employment_indicators_rural_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 483. Table: staging.stg_employment_indicators_rural_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 484. Table: staging.stg_employment_indicators_rural_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 485. Table: staging.stg_employment_indicators_rural_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| indicator_code | VARCHAR |
| indicator | VARCHAR |
---
## 486. Table: staging.stg_employment_indicators_rural_sexes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| sex_code | VARCHAR |
| sex | VARCHAR |
---
## 487. Table: staging.stg_employment_indicators_rural_sources
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| source_code | VARCHAR |
| source | VARCHAR |
---
## 488. Table: staging.stg_environment_bioenergy
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 489. Table: staging.stg_environment_bioenergy_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 490. Table: staging.stg_environment_bioenergy_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 491. Table: staging.stg_environment_bioenergy_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 492. Table: staging.stg_environment_bioenergy_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 493. Table: staging.stg_environment_cropland_nutrient_budget
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 494. Table: staging.stg_environment_cropland_nutrient_budget_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 495. Table: staging.stg_environment_cropland_nutrient_budget_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 496. Table: staging.stg_environment_cropland_nutrient_budget_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 497. Table: staging.stg_environment_cropland_nutrient_budget_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 498. Table: staging.stg_environment_emissions_by_sector
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 499. Table: staging.stg_environment_emissions_by_sector_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 500. Table: staging.stg_environment_emissions_by_sector_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 501. Table: staging.stg_environment_emissions_intensities
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 502. Table: staging.stg_environment_emissions_intensities_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 503. Table: staging.stg_environment_emissions_intensities_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 504. Table: staging.stg_environment_emissions_intensities_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 505. Table: staging.stg_environment_emissions_intensities_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 506. Table: staging.stg_environment_food_waste_disposal
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 507. Table: staging.stg_environment_food_waste_disposal_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 508. Table: staging.stg_environment_food_waste_disposal_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 509. Table: staging.stg_environment_landcover
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 510. Table: staging.stg_environment_landcover_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 511. Table: staging.stg_environment_landcover_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 512. Table: staging.stg_environment_landcover_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 513. Table: staging.stg_environment_landuse
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 514. Table: staging.stg_environment_landuse_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 515. Table: staging.stg_environment_landuse_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 516. Table: staging.stg_environment_livestockmanure
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 517. Table: staging.stg_environment_livestockmanure_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 518. Table: staging.stg_environment_livestockmanure_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 519. Table: staging.stg_environment_livestockmanure_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 520. Table: staging.stg_environment_livestockmanure_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 521. Table: staging.stg_environment_livestockpatterns
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 522. Table: staging.stg_environment_livestockpatterns_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 523. Table: staging.stg_environment_livestockpatterns_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 524. Table: staging.stg_environment_livestockpatterns_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 525. Table: staging.stg_environment_livestockpatterns_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 526. Table: staging.stg_environment_pesticides
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 527. Table: staging.stg_environment_pesticides_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 528. Table: staging.stg_environment_pesticides_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 529. Table: staging.stg_environment_soil_nutrient_budget
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 530. Table: staging.stg_environment_soil_nutrient_budget_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 531. Table: staging.stg_environment_soil_nutrient_budget_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 532. Table: staging.stg_environment_temperature_change
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| months_code | VARCHAR |
| months | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 533. Table: staging.stg_environment_temperature_change_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 534. Table: staging.stg_environment_temperature_change_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 535. Table: staging.stg_environment_temperature_change_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 536. Table: staging.stg_exchange_rate
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| iso_currency_code | VARCHAR |
| currency | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| months_code | VARCHAR |
| months | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 537. Table: staging.stg_exchange_rate_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 538. Table: staging.stg_exchange_rate_currencys
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| iso_currency_code | VARCHAR |
| currency | VARCHAR |
---
## 539. Table: staging.stg_exchange_rate_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 540. Table: staging.stg_exchange_rate_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 541. Table: staging.stg_fertilizers_detailedtradematrix
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| reporter_country_code | VARCHAR |
| reporter_country_code_m49 | VARCHAR |
| reporter_countries | VARCHAR |
| partner_country_code | VARCHAR |
| partner_country_code_m49 | VARCHAR |
| partner_countries | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 542. Table: staging.stg_fertilizers_detailedtradematrix_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 543. Table: staging.stg_fertilizers_detailedtradematrix_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 544. Table: staging.stg_fertilizers_detailedtradematrix_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 545. Table: staging.stg_food_aid_shipments_wfp
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| recipient_country_code | VARCHAR |
| recipient_country_code_m49 | VARCHAR |
| recipient_country | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 546. Table: staging.stg_food_aid_shipments_wfp_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 547. Table: staging.stg_food_aid_shipments_wfp_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 548. Table: staging.stg_food_and_diet_individual_quantitative_dietary_data
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| population_group_code | VARCHAR |
| population_group | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
---
## 549. Table: staging.stg_food_and_diet_individual_quantitative_dietary_data_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 550. Table: staging.stg_food_security_data
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
---
## 551. Table: staging.stg_food_security_data_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 552. Table: staging.stg_food_security_data_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 553. Table: staging.stg_food_security_data_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 554. Table: staging.stg_food_security_data_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 555. Table: staging.stg_foodbalancesheets
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_fbs | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 556. Table: staging.stg_foodbalancesheets_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | BIGINT |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 557. Table: staging.stg_foodbalancesheets_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 558. Table: staging.stg_foodbalancesheets_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 559. Table: staging.stg_foodbalancesheetshistoric
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_fbs | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 560. Table: staging.stg_foodbalancesheetshistoric_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | BIGINT |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 561. Table: staging.stg_foodbalancesheetshistoric_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 562. Table: staging.stg_forestry
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 563. Table: staging.stg_forestry_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 564. Table: staging.stg_forestry_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 565. Table: staging.stg_forestry_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 566. Table: staging.stg_forestry_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 567. Table: staging.stg_forestry_pulp_paper_survey
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 568. Table: staging.stg_forestry_pulp_paper_survey_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 569. Table: staging.stg_forestry_pulp_paper_survey_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 570. Table: staging.stg_forestry_pulp_paper_survey_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 571. Table: staging.stg_forestry_trade_flows
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| reporter_country_code | VARCHAR |
| reporter_country_code_m49 | VARCHAR |
| reporter_countries | VARCHAR |
| partner_country_code | VARCHAR |
| partner_country_code_m49 | VARCHAR |
| partner_countries | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 572. Table: staging.stg_forestry_trade_flows_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | BIGINT |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 573. Table: staging.stg_forestry_trade_flows_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 574. Table: staging.stg_holidays
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| country_code | VARCHAR |
| country_name | VARCHAR |
| local_name | VARCHAR |
| name | VARCHAR |
| types | VARCHAR |
| date | DATE |
---
## 575. Table: staging.stg_household_consumption_and_expenditure_surveys_food_and_diet
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 576. Table: staging.stg_household_consumption_and_expenditure_surveys_food_and_diet_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 577. Table: staging.stg_household_consumption_and_expenditure_surveys_food_and_diet_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 578. Table: staging.stg_household_consumption_and_expenditure_surveys_food_and_diet_geographiclevels
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
---
## 579. Table: staging.stg_household_consumption_and_expenditure_surveys_food_and_diet_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| indicator_code | VARCHAR |
| indicator | VARCHAR |
---
## 580. Table: staging.stg_household_consumption_and_expenditure_surveys_food_and_diet_surveys
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
---
## 581. Table: staging.stg_indicators_from_household_surveys
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| breakdown_variable_code | VARCHAR |
| breakdown_variable | VARCHAR |
| breadown_by_sex_of_the_household_head_code | VARCHAR |
| breadown_by_sex_of_the_household_head | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 582. Table: staging.stg_indicators_from_household_surveys_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 583. Table: staging.stg_individual_quantitative_dietary_data_food_and_diet
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| population_age_group_code | VARCHAR |
| population_age_group | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
---
## 584. Table: staging.stg_individual_quantitative_dietary_data_food_and_diet_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 585. Table: staging.stg_individual_quantitative_dietary_data_food_and_diet_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 586. Table: staging.stg_individual_quantitative_dietary_data_food_and_diet_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| indicator_code | VARCHAR |
| indicator | VARCHAR |
---
## 587. Table: staging.stg_individual_quantitative_dietary_data_food_and_diet_populationagegroups
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| population_age_group | VARCHAR |
| population_age_group_duplicated_0 | VARCHAR |
---
## 588. Table: staging.stg_individual_quantitative_dietary_data_food_and_diet_sexs
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| sex_code | VARCHAR |
| sex | VARCHAR |
---
## 589. Table: staging.stg_individual_quantitative_dietary_data_food_and_diet_surveys
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
---
## 590. Table: staging.stg_inputs_fertilizersarchive
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 591. Table: staging.stg_inputs_fertilizersarchive_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 592. Table: staging.stg_inputs_fertilizersarchive_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 593. Table: staging.stg_inputs_fertilizersnutrient
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 594. Table: staging.stg_inputs_fertilizersnutrient_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 595. Table: staging.stg_inputs_fertilizersnutrient_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 596. Table: staging.stg_inputs_fertilizersnutrient_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 597. Table: staging.stg_inputs_fertilizersnutrient_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 598. Table: staging.stg_inputs_fertilizersproduct
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 599. Table: staging.stg_inputs_fertilizersproduct_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 600. Table: staging.stg_inputs_fertilizersproduct_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 601. Table: staging.stg_inputs_fertilizersproduct_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 602. Table: staging.stg_inputs_fertilizersproduct_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 603. Table: staging.stg_inputs_landuse
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 604. Table: staging.stg_inputs_landuse_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 605. Table: staging.stg_inputs_landuse_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 606. Table: staging.stg_inputs_landuse_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 607. Table: staging.stg_inputs_landuse_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 608. Table: staging.stg_inputs_pesticides_trade
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 609. Table: staging.stg_inputs_pesticides_trade_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 610. Table: staging.stg_inputs_pesticides_trade_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 611. Table: staging.stg_inputs_pesticides_trade_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 612. Table: staging.stg_inputs_pesticides_use
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 613. Table: staging.stg_inputs_pesticides_use_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 614. Table: staging.stg_inputs_pesticides_use_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 615. Table: staging.stg_inputs_pesticides_use_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 616. Table: staging.stg_investment_capitalstock
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 617. Table: staging.stg_investment_capitalstock_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 618. Table: staging.stg_investment_capitalstock_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 619. Table: staging.stg_investment_capitalstock_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 620. Table: staging.stg_investment_countryinvestmentstatisticsprofile
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 621. Table: staging.stg_investment_countryinvestmentstatisticsprofile_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 622. Table: staging.stg_investment_countryinvestmentstatisticsprofile_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 623. Table: staging.stg_investment_countryinvestmentstatisticsprofile_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 624. Table: staging.stg_investment_countryinvestmentstatisticsprofile_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 625. Table: staging.stg_investment_creditagriculture
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 626. Table: staging.stg_investment_creditagriculture_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 627. Table: staging.stg_investment_creditagriculture_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 628. Table: staging.stg_investment_creditagriculture_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 629. Table: staging.stg_investment_creditagriculture_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 630. Table: staging.stg_investment_foreigndirectinvestment
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 631. Table: staging.stg_investment_foreigndirectinvestment_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 632. Table: staging.stg_investment_foreigndirectinvestment_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 633. Table: staging.stg_investment_foreigndirectinvestment_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 634. Table: staging.stg_investment_governmentexpenditure
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 635. Table: staging.stg_investment_governmentexpenditure_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 636. Table: staging.stg_investment_governmentexpenditure_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 637. Table: staging.stg_investment_governmentexpenditure_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 638. Table: staging.stg_investment_governmentexpenditure_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 639. Table: staging.stg_investment_machinery
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 640. Table: staging.stg_investment_machinery_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 641. Table: staging.stg_investment_machinery_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 642. Table: staging.stg_investment_machineryarchive
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 643. Table: staging.stg_investment_machineryarchive_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 644. Table: staging.stg_investment_machineryarchive_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 645. Table: staging.stg_investment_machineryarchive_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 646. Table: staging.stg_investment_machineryarchive_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 647. Table: staging.stg_macro_statistics_key_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 648. Table: staging.stg_macro_statistics_key_indicators_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 649. Table: staging.stg_macro_statistics_key_indicators_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 650. Table: staging.stg_macro_statistics_key_indicators_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 651. Table: staging.stg_macro_statistics_key_indicators_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 652. Table: staging.stg_minimum_dietary_diversity_for_women_mdd_w_food_and_diet
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 653. Table: staging.stg_minimum_dietary_diversity_for_women_mdd_w_food_and_diet_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 654. Table: staging.stg_minimum_dietary_diversity_for_women_mdd_w_food_and_diet_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 655. Table: staging.stg_minimum_dietary_diversity_for_women_mdd_w_food_and_diet_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| indicator_code | VARCHAR |
| indicator | VARCHAR |
---
## 656. Table: staging.stg_minimum_dietary_diversity_for_women_mdd_w_food_and_diet_surveys
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
---
## 657. Table: staging.stg_population
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 658. Table: staging.stg_population_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 659. Table: staging.stg_population_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 660. Table: staging.stg_population_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 661. Table: staging.stg_population_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| item | VARCHAR |
---
## 662. Table: staging.stg_prices
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| months_code | VARCHAR |
| months | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 663. Table: staging.stg_prices_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 664. Table: staging.stg_prices_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 665. Table: staging.stg_prices_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 666. Table: staging.stg_prices_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 667. Table: staging.stg_pricesarchive
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 668. Table: staging.stg_pricesarchive_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 669. Table: staging.stg_pricesarchive_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 670. Table: staging.stg_pricesarchive_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 671. Table: staging.stg_pricesarchive_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 672. Table: staging.stg_production_crops_livestock
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 673. Table: staging.stg_production_crops_livestock_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 674. Table: staging.stg_production_crops_livestock_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 675. Table: staging.stg_production_crops_livestock_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 676. Table: staging.stg_production_crops_livestock_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 677. Table: staging.stg_production_indices
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
---
## 678. Table: staging.stg_production_indices_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 679. Table: staging.stg_production_indices_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 680. Table: staging.stg_production_indices_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 681. Table: staging.stg_production_indices_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 682. Table: staging.stg_rural_livelihoods_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| qualifier_code | VARCHAR |
| qualifier | VARCHAR |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 683. Table: staging.stg_rural_livelihoods_indicators_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 684. Table: staging.stg_rural_livelihoods_indicators_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 685. Table: staging.stg_rural_livelihoods_indicators_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| indicator_code | VARCHAR |
| indicator | VARCHAR |
---
## 686. Table: staging.stg_rural_livelihoods_indicators_qualifiers
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| qualifier_code | VARCHAR |
| qualifier | VARCHAR |
---
## 687. Table: staging.stg_rural_livelihoods_indicators_sources
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| source_code | VARCHAR |
| source | VARCHAR |
---
## 688. Table: staging.stg_rural_livelihoods_indicators_surveys
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
---
## 689. Table: staging.stg_sdg_bulkdownloads
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_sdg | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
---
## 690. Table: staging.stg_sdg_bulkdownloads_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 691. Table: staging.stg_sdg_bulkdownloads_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 692. Table: staging.stg_sdg_bulkdownloads_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 693. Table: staging.stg_sdg_bulkdownloads_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| sdg_code | VARCHAR |
| item | VARCHAR |
---
## 694. Table: staging.stg_sua_crops_livestock
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 695. Table: staging.stg_sua_crops_livestock_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 696. Table: staging.stg_sua_crops_livestock_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 697. Table: staging.stg_sua_crops_livestock_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 698. Table: staging.stg_sua_crops_livestock_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 699. Table: staging.stg_suite_of_gender_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_sdg | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| sex_code | VARCHAR |
| sex_code_sdg | VARCHAR |
| sex | VARCHAR |
| population_age_group_code | VARCHAR |
| population_age_group | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| activity_code | VARCHAR |
| activity_code_sdg | VARCHAR |
| activity | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 700. Table: staging.stg_suite_of_gender_indicators_activities
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| activity_code | VARCHAR |
| activity | VARCHAR |
---
## 701. Table: staging.stg_suite_of_gender_indicators_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 702. Table: staging.stg_suite_of_gender_indicators_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 703. Table: staging.stg_suite_of_gender_indicators_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 704. Table: staging.stg_suite_of_gender_indicators_geographiclevels
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
---
## 705. Table: staging.stg_suite_of_gender_indicators_itemcodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| sdg_code | VARCHAR |
| item | VARCHAR |
---
## 706. Table: staging.stg_suite_of_gender_indicators_populationagegroups
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| population_age_group_code | VARCHAR |
| population_age_group | VARCHAR |
---
## 707. Table: staging.stg_suite_of_gender_indicators_sexes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| sex_code | VARCHAR |
| sex | VARCHAR |
---
## 708. Table: staging.stg_supply_utilization_accounts_food_and_diet
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
---
## 709. Table: staging.stg_supply_utilization_accounts_food_and_diet_areacodes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
---
## 710. Table: staging.stg_supply_utilization_accounts_food_and_diet_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 711. Table: staging.stg_supply_utilization_accounts_food_and_diet_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 712. Table: staging.stg_supply_utilization_accounts_food_and_diet_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| indicator_code | VARCHAR |
| indicator | VARCHAR |
---
## 713. Table: staging.stg_trade_elements
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| element_code | VARCHAR |
| element | VARCHAR |
---
## 714. Table: staging.stg_trade_flags
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| flag | VARCHAR |
| description | VARCHAR |
---
## 715. Table: staging.stg_trade_item_codes
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| item_code | VARCHAR |
| cpc_code | VARCHAR |
| item | VARCHAR |
---
## 716. Table: staging.stg_trade_matrix
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| reporter_country_code | BIGINT |
| reporter_country_code_m49 | VARCHAR |
| reporter_countries | VARCHAR |
| partner_country_code | BIGINT |
| partner_country_code_m49 | VARCHAR |
| partner_countries | VARCHAR |
| item_code | BIGINT |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | BIGINT |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| year | INTEGER |
| flag | VARCHAR |
---
## 717. Table: staging.stg_trade_partner_countries
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| partner_country_code | VARCHAR |
| m49_code | VARCHAR |
| partner_countries | VARCHAR |
---
## 718. Table: staging.stg_trade_reporter_countries
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| reporter_country_code | VARCHAR |
| m49_code | VARCHAR |
| reporter_countries | VARCHAR |
---
## 719. Table: staging.stg_weather
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| country_iso2 | VARCHAR |
| country_name | VARCHAR |
| latitude | DOUBLE |
| longitude | DOUBLE |
| year | BIGINT |
| month | BIGINT |
| temp_c | DOUBLE |
| precip_mm_day | DOUBLE |
---
# Schema: intermediate (73 tables)
## 720. Table: intermediate.int_asti_expenditures
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| cost_category_code | VARCHAR |
| cost_category | VARCHAR |
| institution_code | VARCHAR |
| institution | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| cost_category_label | VARCHAR |
| description | VARCHAR |
| indicator_label | VARCHAR |
| institution_label | VARCHAR |
---
## 721. Table: intermediate.int_asti_expenditures_archive
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 722. Table: intermediate.int_asti_researchers
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| degree_code | VARCHAR |
| degree | VARCHAR |
| sex_code | VARCHAR |
| sex_code_sdg | VARCHAR |
| sex | VARCHAR |
| institution_code | VARCHAR |
| institution | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| degree_label | VARCHAR |
| description | VARCHAR |
| indicator_label | VARCHAR |
| institution_label | VARCHAR |
| sex_label | VARCHAR |
---
## 723. Table: intermediate.int_asti_researchers_archive
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 724. Table: intermediate.int_climate_change_emissions_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 725. Table: intermediate.int_commoditybalances_non_food
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 726. Table: intermediate.int_commoditybalances_non_food_2010
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 727. Table: intermediate.int_commoditybalances_non_food_2013_old_methodology
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 728. Table: intermediate.int_consumerpriceindices
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| months_code | VARCHAR |
| months | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 729. Table: intermediate.int_cost_affordability_healthy_diet_coahd
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| release_code | VARCHAR |
| release | VARCHAR |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| release_label | VARCHAR |
---
## 730. Table: intermediate.int_deflators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 731. Table: intermediate.int_development_assistance_to_agriculture
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| donor_code | VARCHAR |
| donor_code_m49 | VARCHAR |
| donor | VARCHAR |
| recipient_country_code | VARCHAR |
| recipient_country_code_m49 | VARCHAR |
| recipient_country | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| purpose_code | VARCHAR |
| purpose | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| purpose_label | VARCHAR |
---
## 732. Table: intermediate.int_emissions_agriculture_energy
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 733. Table: intermediate.int_emissions_crops
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
| source_label | VARCHAR |
---
## 734. Table: intermediate.int_emissions_drained_organic_soils
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| source_label | VARCHAR |
---
## 735. Table: intermediate.int_emissions_land_use_fires
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| source_label | VARCHAR |
---
## 736. Table: intermediate.int_emissions_land_use_forests
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| source_label | VARCHAR |
---
## 737. Table: intermediate.int_emissions_livestock
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
| source_label | VARCHAR |
---
## 738. Table: intermediate.int_emissions_pre_post_production
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 739. Table: intermediate.int_emissions_totals
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
| source_label | VARCHAR |
---
## 740. Table: intermediate.int_employment_indicators_agriculture
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| source_code | VARCHAR |
| source | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| indicator_label | VARCHAR |
| sex_label | VARCHAR |
| source_label | VARCHAR |
---
## 741. Table: intermediate.int_employment_indicators_rural
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| source_code | VARCHAR |
| source | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| indicator_label | VARCHAR |
| sex_label | VARCHAR |
| source_label | VARCHAR |
---
## 742. Table: intermediate.int_environment_bioenergy
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 743. Table: intermediate.int_environment_cropland_nutrient_budget
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 744. Table: intermediate.int_environment_emissions_by_sector
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| description | VARCHAR |
---
## 745. Table: intermediate.int_environment_emissions_intensities
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 746. Table: intermediate.int_environment_food_waste_disposal
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| description | VARCHAR |
---
## 747. Table: intermediate.int_environment_landcover
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 748. Table: intermediate.int_environment_landuse
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| description | VARCHAR |
---
## 749. Table: intermediate.int_environment_livestockmanure
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 750. Table: intermediate.int_environment_livestockpatterns
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 751. Table: intermediate.int_environment_pesticides
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| description | VARCHAR |
---
## 752. Table: intermediate.int_environment_soil_nutrient_budget
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| description | VARCHAR |
---
## 753. Table: intermediate.int_environment_temperature_change
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| months_code | VARCHAR |
| months | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 754. Table: intermediate.int_exchange_rate
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| iso_currency_code | VARCHAR |
| currency | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| months_code | VARCHAR |
| months | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| currency_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 755. Table: intermediate.int_fertilizers_detailedtradematrix
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| reporter_country_code | VARCHAR |
| reporter_country_code_m49 | VARCHAR |
| reporter_countries | VARCHAR |
| partner_country_code | VARCHAR |
| partner_country_code_m49 | VARCHAR |
| partner_countries | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 756. Table: intermediate.int_food_aid_shipments_wfp
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| recipient_country_code | VARCHAR |
| recipient_country_code_m49 | VARCHAR |
| recipient_country | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
| description | VARCHAR |
---
## 757. Table: intermediate.int_food_and_diet_individual_quantitative_dietary_data
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| population_group_code | VARCHAR |
| population_group | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
| description | VARCHAR |
---
## 758. Table: intermediate.int_food_security_data
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 759. Table: intermediate.int_foodbalancesheets
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_fbs | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 760. Table: intermediate.int_foodbalancesheetshistoric
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_fbs | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| description | VARCHAR |
---
## 761. Table: intermediate.int_forestry
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 762. Table: intermediate.int_forestry_pulp_paper_survey
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 763. Table: intermediate.int_forestry_trade_flows
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| reporter_country_code | VARCHAR |
| reporter_country_code_m49 | VARCHAR |
| reporter_countries | VARCHAR |
| partner_country_code | VARCHAR |
| partner_country_code_m49 | VARCHAR |
| partner_countries | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
| description | VARCHAR |
---
## 764. Table: intermediate.int_household_consumption_and_expenditure_surveys_food_and_diet
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| geographic_level_label | VARCHAR |
| indicator_label | VARCHAR |
| survey_label | VARCHAR |
---
## 765. Table: intermediate.int_indicators_from_household_surveys
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| breakdown_variable_code | VARCHAR |
| breakdown_variable | VARCHAR |
| breadown_by_sex_of_the_household_head_code | VARCHAR |
| breadown_by_sex_of_the_household_head | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| description | VARCHAR |
---
## 766. Table: intermediate.int_individual_quantitative_dietary_data_food_and_diet
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| population_age_group_code | VARCHAR |
| population_age_group | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| indicator_label | VARCHAR |
| population_age_group_duplicated_0 | VARCHAR |
| sex_label | VARCHAR |
| survey_label | VARCHAR |
---
## 767. Table: intermediate.int_inputs_fertilizersarchive
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| description | VARCHAR |
---
## 768. Table: intermediate.int_inputs_fertilizersnutrient
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 769. Table: intermediate.int_inputs_fertilizersproduct
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 770. Table: intermediate.int_inputs_landuse
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 771. Table: intermediate.int_inputs_pesticides_trade
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 772. Table: intermediate.int_inputs_pesticides_use
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 773. Table: intermediate.int_investment_capitalstock
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 774. Table: intermediate.int_investment_countryinvestmentstatisticsprofile
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 775. Table: intermediate.int_investment_creditagriculture
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 776. Table: intermediate.int_investment_foreigndirectinvestment
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
---
## 777. Table: intermediate.int_investment_governmentexpenditure
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 778. Table: intermediate.int_investment_machinery
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| description | VARCHAR |
---
## 779. Table: intermediate.int_investment_machineryarchive
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 780. Table: intermediate.int_macro_statistics_key_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 781. Table: intermediate.int_minimum_dietary_diversity_for_women_mdd_w_food_and_diet
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| indicator_label | VARCHAR |
| survey_label | VARCHAR |
---
## 782. Table: intermediate.int_population
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| item_label | VARCHAR |
---
## 783. Table: intermediate.int_prices
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| months_code | VARCHAR |
| months | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 784. Table: intermediate.int_pricesarchive
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 785. Table: intermediate.int_production_crops_livestock
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 786. Table: intermediate.int_production_indices
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 787. Table: intermediate.int_rural_livelihoods_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| qualifier_code | VARCHAR |
| qualifier | VARCHAR |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| indicator_label | VARCHAR |
| qualifier_label | VARCHAR |
| source_label | VARCHAR |
| survey_label | VARCHAR |
---
## 788. Table: intermediate.int_sdg_bulkdownloads
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_sdg | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| sdg_code | VARCHAR |
| item_label | VARCHAR |
---
## 789. Table: intermediate.int_sua_crops_livestock
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
---
## 790. Table: intermediate.int_suite_of_gender_indicators
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_sdg | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| sex_code | VARCHAR |
| sex_code_sdg | VARCHAR |
| sex | VARCHAR |
| population_age_group_code | VARCHAR |
| population_age_group | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| activity_code | VARCHAR |
| activity_code_sdg | VARCHAR |
| activity | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| activity_label | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| geographic_level_label | VARCHAR |
| sdg_code | VARCHAR |
| item_label | VARCHAR |
| population_age_group_label | VARCHAR |
| sex_label | VARCHAR |
---
## 791. Table: intermediate.int_supply_utilization_accounts_food_and_diet
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_label | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| indicator_label | VARCHAR |
---
## 792. Table: intermediate.int_trade_matrix
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| reporter_country_code | BIGINT |
| reporter_country_code_m49 | VARCHAR |
| reporter_countries | VARCHAR |
| partner_country_code | BIGINT |
| partner_country_code_m49 | VARCHAR |
| partner_countries | VARCHAR |
| item_code | BIGINT |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | BIGINT |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| year | INTEGER |
| flag | VARCHAR |
| element_label | VARCHAR |
| description | VARCHAR |
| cpc_code | VARCHAR |
| item_label | VARCHAR |
| partner_m49_code | VARCHAR |
| partner_countries_label | VARCHAR |
| reporter_m49_code | VARCHAR |
| reporter_countries_label | VARCHAR |
---
# Schema: marts (76 tables)
## 793. Table: marts.dim_commodity_prices__indices
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| date | DATE |
| total_index | DOUBLE |
| energy | DOUBLE |
| non_energy | DOUBLE |
| agriculture | DOUBLE |
| beverages | DOUBLE |
| food | DOUBLE |
| oils_meals | DOUBLE |
| grains | DOUBLE |
| other_food | DOUBLE |
| raw_materials | DOUBLE |
| timber | DOUBLE |
| other_raw_mat | DOUBLE |
| fertilizers | DOUBLE |
| metals_minerals | DOUBLE |
| base_metals_ex_iron_ore | DOUBLE |
| precious_metals | DOUBLE |
---
## 794. Table: marts.dim_commodity_prices__prices
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| date | DATE |
| commodity | VARCHAR |
| unit | VARCHAR |
| price | DOUBLE |
---
## 795. Table: marts.dim_country_reference
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| country | VARCHAR |
| latitude | DOUBLE |
| longitude | DOUBLE |
| name | VARCHAR |
---
## 796. Table: marts.dim_disasters
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| disno | VARCHAR |
| historic | VARCHAR |
| classification_key | VARCHAR |
| disaster_group | VARCHAR |
| disaster_subgroup | VARCHAR |
| disaster_type | VARCHAR |
| disaster_subtype | VARCHAR |
| external_ids | VARCHAR |
| event_name | VARCHAR |
| iso | VARCHAR |
| country | VARCHAR |
| subregion | VARCHAR |
| region | VARCHAR |
| location | VARCHAR |
| origin | VARCHAR |
| associated_types | VARCHAR |
| ofda_bha_response | VARCHAR |
| appeal | VARCHAR |
| declaration | VARCHAR |
| aid_contribution_000_us | DOUBLE |
| magnitude | DOUBLE |
| magnitude_scale | VARCHAR |
| latitude | DOUBLE |
| longitude | DOUBLE |
| river_basin | VARCHAR |
| start_year | BIGINT |
| start_month | DOUBLE |
| start_day | DOUBLE |
| end_year | BIGINT |
| end_month | DOUBLE |
| end_day | DOUBLE |
| total_deaths | DOUBLE |
| no_injured | DOUBLE |
| no_affected | DOUBLE |
| no_homeless | DOUBLE |
| total_affected | DOUBLE |
| reconstruction_costs_000_us | DOUBLE |
| reconstruction_costs_adjusted_000_us | DOUBLE |
| insured_damage_000_us | DOUBLE |
| insured_damage_adjusted_000_us | DOUBLE |
| total_damage_000_us | DOUBLE |
| total_damage_adjusted_000_us | DOUBLE |
| cpi | DOUBLE |
| admin_units | VARCHAR |
| gadm_admin_units | VARCHAR |
| entry_date | DATE |
| last_update | DATE |
---
## 797. Table: marts.dim_holidays
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| country_code | VARCHAR |
| country_name | VARCHAR |
| date | DATE |
| local_name | VARCHAR |
| name | VARCHAR |
| types | VARCHAR |
---
## 798. Table: marts.dim_weather
**Row Count (estimated):** ERROR
### Columns
| Column Name | Data Type |
|---|---|
| country_iso2 | VARCHAR |
| country_name | VARCHAR |
| latitude | DOUBLE |
| longitude | DOUBLE |
| year | BIGINT |
| month | BIGINT |
| temp_c | DOUBLE |
| precip_mm_day | DOUBLE |
---
## 799. Table: marts.fact_commodity_balances___2010
**Row Count (estimated):** 127,558
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 800. Table: marts.fact_commodity_balances___2013_old_methodology
**Row Count (estimated):** 1,184,986
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 801. Table: marts.fact_commodity_balances__commoditybalances_non_food
**Row Count (estimated):** 1,184,986
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 802. Table: marts.fact_emissions_environment__change
**Row Count (estimated):** 590,512
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| months_code | VARCHAR |
| months | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 803. Table: marts.fact_emissions_environment__emissions_crops
**Row Count (estimated):** 766,730
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
| source_name | VARCHAR |
---
## 804. Table: marts.fact_emissions_environment__emissions_indicators
**Row Count (estimated):** 678,370
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 805. Table: marts.fact_emissions_environment__emissions_land_use_fires
**Row Count (estimated):** 428,963
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| source_name | VARCHAR |
---
## 806. Table: marts.fact_emissions_environment__emissions_land_use_forests
**Row Count (estimated):** 65,639
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| source_name | VARCHAR |
---
## 807. Table: marts.fact_emissions_environment__emissions_livestock
**Row Count (estimated):** 6,650,421
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
| source_name | VARCHAR |
---
## 808. Table: marts.fact_emissions_environment__emissions_totals
**Row Count (estimated):** 2,500,090
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
| source_name | VARCHAR |
---
## 809. Table: marts.fact_emissions_environment__energy
**Row Count (estimated):** 120,740
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 810. Table: marts.fact_emissions_environment__intensities
**Row Count (estimated):** 409,511
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 811. Table: marts.fact_emissions_environment__production
**Row Count (estimated):** 522,216
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 812. Table: marts.fact_emissions_environment__sector
**Row Count (estimated):** 509,153
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| flag_description | VARCHAR |
---
## 813. Table: marts.fact_emissions_environment__soils
**Row Count (estimated):** 87,484
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| source_code | VARCHAR |
| source | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| source_name | VARCHAR |
---
## 814. Table: marts.fact_food_security__data
**Row Count (estimated):** 279,470
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 815. Table: marts.fact_food_security__food_and_diet
**Row Count (estimated):** 743,139
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| indicator_name | VARCHAR |
---
## 816. Table: marts.fact_food_security__food_and_diet_individual_quantitative_dietary_data
**Row Count (estimated):** 1,164,769
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| population_group_code | VARCHAR |
| population_group | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
| flag_description | VARCHAR |
---
## 817. Table: marts.fact_food_security__foodbalancesheets
**Row Count (estimated):** 4,820,497
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_fbs | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 818. Table: marts.fact_food_security__historic
**Row Count (estimated):** 11,479,903
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_fbs | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| flag_description | VARCHAR |
---
## 819. Table: marts.fact_food_security__household_consumption_and_expenditure_surveys_food_and_diet
**Row Count (estimated):** 1,166,330
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| geographic_level_name | VARCHAR |
| indicator_name | VARCHAR |
| survey_name | VARCHAR |
---
## 820. Table: marts.fact_food_security__individual_quantitative_dietary_data_food_and_diet
**Row Count (estimated):** 2,191,084
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| population_age_group_code | VARCHAR |
| population_age_group | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| indicator_name | VARCHAR |
| population_age_group_duplicated_0 | VARCHAR |
| sex_name | VARCHAR |
| survey_name | VARCHAR |
---
## 821. Table: marts.fact_food_security__minimum_dietary_diversity_for_women_mdd_w_food_and_diet
**Row Count (estimated):** 1,223
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| food_group_code | VARCHAR |
| food_group | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| indicator_name | VARCHAR |
| survey_name | VARCHAR |
---
## 822. Table: marts.fact_food_security__shipments_wfp
**Row Count (estimated):** 31,114
### Columns
| Column Name | Data Type |
|---|---|
| recipient_country_code | VARCHAR |
| recipient_country_code_m49 | VARCHAR |
| recipient_country | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
| flag_description | VARCHAR |
---
## 823. Table: marts.fact_forestry__flows
**Row Count (estimated):** 2,829,802
### Columns
| Column Name | Data Type |
|---|---|
| reporter_country_code | VARCHAR |
| reporter_country_code_m49 | VARCHAR |
| reporter_countries | VARCHAR |
| partner_country_code | VARCHAR |
| partner_country_code_m49 | VARCHAR |
| partner_countries | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area | VARCHAR |
| flag_description | VARCHAR |
---
## 824. Table: marts.fact_forestry__forestry
**Row Count (estimated):** 2,457,869
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 825. Table: marts.fact_forestry__pulp_paper_survey
**Row Count (estimated):** 67,538
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 826. Table: marts.fact_investment_finance__agriculture
**Row Count (estimated):** 13,020,275
### Columns
| Column Name | Data Type |
|---|---|
| donor_code | VARCHAR |
| donor_code_m49 | VARCHAR |
| donor | VARCHAR |
| recipient_country_code | VARCHAR |
| recipient_country_code_m49 | VARCHAR |
| recipient_country | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| purpose_code | VARCHAR |
| purpose | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| purpose_name | VARCHAR |
---
## 827. Table: marts.fact_investment_finance__archive
**Row Count (estimated):** 328,932
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 828. Table: marts.fact_investment_finance__indicators
**Row Count (estimated):** 708,632
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 829. Table: marts.fact_investment_finance__investment_capitalstock
**Row Count (estimated):** 144,944
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 830. Table: marts.fact_investment_finance__investment_countryinvestmentstatisticsprofile
**Row Count (estimated):** 66,447
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 831. Table: marts.fact_investment_finance__investment_creditagriculture
**Row Count (estimated):** 62,899
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 832. Table: marts.fact_investment_finance__investment_foreigndirectinvestment
**Row Count (estimated):** 40,442
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 833. Table: marts.fact_investment_finance__investment_governmentexpenditure
**Row Count (estimated):** 156,256
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 834. Table: marts.fact_investment_finance__investment_machinery
**Row Count (estimated):** 146,834
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| flag_description | VARCHAR |
---
## 835. Table: marts.fact_land_resources__budget
**Row Count (estimated):** 196,030
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| flag_description | VARCHAR |
---
## 836. Table: marts.fact_land_resources__disposal
**Row Count (estimated):** 67,264
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| flag_description | VARCHAR |
---
## 837. Table: marts.fact_land_resources__environment_bioenergy
**Row Count (estimated):** 128,457
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 838. Table: marts.fact_land_resources__environment_landcover
**Row Count (estimated):** 210,986
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 839. Table: marts.fact_land_resources__environment_landuse
**Row Count (estimated):** 165,960
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| flag_description | VARCHAR |
---
## 840. Table: marts.fact_land_resources__environment_livestockmanure
**Row Count (estimated):** 2,555,034
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 841. Table: marts.fact_land_resources__environment_livestockpatterns
**Row Count (estimated):** 470,577
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 842. Table: marts.fact_land_resources__environment_pesticides
**Row Count (estimated):** 15,452
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| flag_description | VARCHAR |
---
## 843. Table: marts.fact_land_resources__inputs_fertilizersarchive
**Row Count (estimated):** 178,192
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| flag_description | VARCHAR |
---
## 844. Table: marts.fact_land_resources__inputs_fertilizersnutrient
**Row Count (estimated):** 241,859
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 845. Table: marts.fact_land_resources__inputs_fertilizersproduct
**Row Count (estimated):** 303,498
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 846. Table: marts.fact_land_resources__inputs_landuse
**Row Count (estimated):** 413,211
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 847. Table: marts.fact_land_resources__use
**Row Count (estimated):** 103,622
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 848. Table: marts.fact_prices__coahd
**Row Count (estimated):** 11,672
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| release_code | VARCHAR |
| release | VARCHAR |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| release_name | VARCHAR |
---
## 849. Table: marts.fact_prices__consumerpriceindices
**Row Count (estimated):** 248,394
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| months_code | VARCHAR |
| months | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 850. Table: marts.fact_prices__deflators
**Row Count (estimated):** 92,776
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 851. Table: marts.fact_prices__prices
**Row Count (estimated):** 1,319,563
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| months_code | VARCHAR |
| months | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 852. Table: marts.fact_prices__pricesarchive
**Row Count (estimated):** 139,713
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 853. Table: marts.fact_prices__rate
**Row Count (estimated):** 145,821
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| iso_currency_code | VARCHAR |
| currency | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| months_code | VARCHAR |
| months | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| currency_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
## 854. Table: marts.fact_production__crops_livestock
**Row Count (estimated):** 4,209,110
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 855. Table: marts.fact_production__indices
**Row Count (estimated):** 1,995,192
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 856. Table: marts.fact_production__sua_crops_livestock
**Row Count (estimated):** 11,615,212
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 857. Table: marts.fact_research_capacity___archive
**Row Count (estimated):** 3,154
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 858. Table: marts.fact_research_capacity__asti_expenditures
**Row Count (estimated):** 7,789
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| cost_category_code | VARCHAR |
| cost_category | VARCHAR |
| institution_code | VARCHAR |
| institution | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| cost_category_name | VARCHAR |
| flag_description | VARCHAR |
| indicator_name | VARCHAR |
| institution_name | VARCHAR |
---
## 859. Table: marts.fact_research_capacity__asti_researchers
**Row Count (estimated):** 3,800
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| degree_code | VARCHAR |
| degree | VARCHAR |
| sex_code | VARCHAR |
| sex_code_sdg | VARCHAR |
| sex | VARCHAR |
| institution_code | VARCHAR |
| institution | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| degree_name | VARCHAR |
| flag_description | VARCHAR |
| indicator_name | VARCHAR |
| institution_name | VARCHAR |
| sex_name | VARCHAR |
---
## 860. Table: marts.fact_socioeconomic__employment_indicators_agriculture
**Row Count (estimated):** 256,389
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| source_code | VARCHAR |
| source | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| indicator_name | VARCHAR |
| sex_name | VARCHAR |
| source_name | VARCHAR |
---
## 861. Table: marts.fact_socioeconomic__employment_indicators_rural
**Row Count (estimated):** 113,187
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| source_code | VARCHAR |
| source | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| sex_code | VARCHAR |
| sex | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| indicator_name | VARCHAR |
| sex_name | VARCHAR |
| source_name | VARCHAR |
---
## 862. Table: marts.fact_socioeconomic__indicators
**Row Count (estimated):** 315,014
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_sdg | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| sex_code | VARCHAR |
| sex_code_sdg | VARCHAR |
| sex | VARCHAR |
| population_age_group_code | VARCHAR |
| population_age_group | VARCHAR |
| geographic_level_code | VARCHAR |
| geographic_level | VARCHAR |
| activity_code | VARCHAR |
| activity_code_sdg | VARCHAR |
| activity | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| note | VARCHAR |
| activity_name | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| geographic_level_name | VARCHAR |
| sdg_code | VARCHAR |
| item_name | VARCHAR |
| population_age_group_name | VARCHAR |
| sex_name | VARCHAR |
---
## 863. Table: marts.fact_socioeconomic__indicators_from_household_surveys
**Row Count (estimated):** 148,620
### Columns
| Column Name | Data Type |
|---|---|
| survey_code | VARCHAR |
| survey | VARCHAR |
| breakdown_variable_code | VARCHAR |
| breakdown_variable | VARCHAR |
| breadown_by_sex_of_the_household_head_code | VARCHAR |
| breadown_by_sex_of_the_household_head | VARCHAR |
| indicator_code | VARCHAR |
| indicator | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| flag_description | VARCHAR |
---
## 864. Table: marts.fact_socioeconomic__population
**Row Count (estimated):** 168,405
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| item_name | VARCHAR |
---
## 865. Table: marts.fact_socioeconomic__sdg_bulkdownloads
**Row Count (estimated):** 464,787
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item_code_sdg | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | VARCHAR |
| flag | VARCHAR |
| note | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| sdg_code | VARCHAR |
| item_name | VARCHAR |
---
## 866. Table: marts.fact_trade__fertilizers_detailedtradematrix
**Row Count (estimated):** 5,300,910
### Columns
| Column Name | Data Type |
|---|---|
| reporter_country_code | VARCHAR |
| reporter_country_code_m49 | VARCHAR |
| reporter_countries | VARCHAR |
| partner_country_code | VARCHAR |
| partner_country_code_m49 | VARCHAR |
| partner_countries | VARCHAR |
| item_code | VARCHAR |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
---
## 867. Table: marts.fact_trade__matrix
**Row Count (estimated):** 52,410,630
### Columns
| Column Name | Data Type |
|---|---|
| reporter_country_code | BIGINT |
| reporter_country_code_m49 | VARCHAR |
| reporter_countries | VARCHAR |
| partner_country_code | BIGINT |
| partner_country_code_m49 | VARCHAR |
| partner_countries | VARCHAR |
| item_code | BIGINT |
| item_code_cpc | VARCHAR |
| item | VARCHAR |
| element_code | BIGINT |
| element | VARCHAR |
| unit | VARCHAR |
| value | DOUBLE |
| year | INTEGER |
| flag | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
| cpc_code | VARCHAR |
| item_name | VARCHAR |
| partner_m49_code | VARCHAR |
| partner_country_name | VARCHAR |
| reporter_m49_code | VARCHAR |
| reporter_country_name | VARCHAR |
---
## 868. Table: marts.fact_trade__trade
**Row Count (estimated):** 190,740
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area_code_m49 | VARCHAR |
| area | VARCHAR |
| item_code | VARCHAR |
| item | VARCHAR |
| element_code | VARCHAR |
| element | VARCHAR |
| year_code | BIGINT |
| year | BIGINT |
| unit | VARCHAR |
| value | DOUBLE |
| flag | VARCHAR |
| m49_code | VARCHAR |
| area_name | VARCHAR |
| element_name | VARCHAR |
| flag_description | VARCHAR |
---
# Schema: reporting (16 tables)
## 869. Table: reporting.kpi_food_security_adequacy_ratio
**Row Count (estimated):** 3,373
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area | VARCHAR |
| year | BIGINT |
| supply_kcal | DOUBLE |
| requirement_kcal | DOUBLE |
| adequacy_ratio | DOUBLE |
---
## 870. Table: reporting.kpi_food_security_below_threshold
**Row Count (estimated):** 20
### Columns
| Column Name | Data Type |
|---|---|
| year | BIGINT |
| countries_below_threshold | HUGEINT |
| countries_total | BIGINT |
| pct_below_threshold | DOUBLE |
---
## 871. Table: reporting.kpi_food_security_risk_trend
**Row Count (estimated):** 167
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area | VARCHAR |
| ratio_2001 | DOUBLE |
| ratio_2020 | DOUBLE |
| change | DOUBLE |
---
## 872. Table: reporting.kpi_food_security_undernourishment
**Row Count (estimated):** 20
### Columns
| Column Name | Data Type |
|---|---|
| year | BIGINT |
| weighted_sum | DOUBLE |
| total_population | DOUBLE |
| population_weighted_ratio | DOUBLE |
| countries_matched | BIGINT |
---
## 873. Table: reporting.kpi_prices_cpi_passthrough
**Row Count (estimated):** 198
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area | VARCHAR |
| avg_inflation_gap_pct_pts | DOUBLE |
| n_years | BIGINT |
---
## 874. Table: reporting.kpi_prices_fx_effect
**Row Count (estimated):** 224
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area | VARCHAR |
| avg_fx_yoy_pct | DOUBLE |
| avg_local_price_yoy_pct | DOUBLE |
| n_years | BIGINT |
| fx_share_of_swing_pct | DOUBLE |
---
## 875. Table: reporting.kpi_prices_index
**Row Count (estimated):** 20
### Columns
| Column Name | Data Type |
|---|---|
| year | BIGINT |
| avg_agriculture_index | DOUBLE |
| avg_food_index | DOUBLE |
| avg_fertilizers_index | DOUBLE |
---
## 876. Table: reporting.kpi_prices_volatility
**Row Count (estimated):** 20
### Columns
| Column Name | Data Type |
|---|---|
| year | BIGINT |
| volatility_stddev_pct | DOUBLE |
| avg_mom_change_pct | DOUBLE |
| avg_price | DOUBLE |
---
## 877. Table: reporting.kpi_productivity_fertilizer_intensity
**Row Count (estimated):** 3,930
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area | VARCHAR |
| year | BIGINT |
| fertilizer_kg_per_ha | DOUBLE |
---
## 878. Table: reporting.kpi_productivity_pesticide_intensity
**Row Count (estimated):** 3,200
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area | VARCHAR |
| year | BIGINT |
| pesticide_kg_per_ha | DOUBLE |
---
## 879. Table: reporting.kpi_productivity_wheat_yield
**Row Count (estimated):** 2,481
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area | VARCHAR |
| year | BIGINT |
| yield_value | DOUBLE |
---
## 880. Table: reporting.kpi_productivity_yield_trend
**Row Count (estimated):** 121
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area | VARCHAR |
| yield_2001 | DOUBLE |
| yield_2020 | DOUBLE |
| change | DOUBLE |
| pct_change | DOUBLE |
---
## 881. Table: reporting.kpi_trade_dependency_trend
**Row Count (estimated):** 216
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area | VARCHAR |
| dependency_2001 | DOUBLE |
| dependency_2020 | DOUBLE |
| dependency_change_pct_pts | DOUBLE |
---
## 882. Table: reporting.kpi_trade_export_concentration
**Row Count (estimated):** 2,713
### Columns
| Column Name | Data Type |
|---|---|
| area_code | BIGINT |
| area | VARCHAR |
| year | INTEGER |
| top_partner | VARCHAR |
| top_partner_value | DOUBLE |
| total_export_value | DOUBLE |
| top_partner_share_pct | DOUBLE |
---
## 883. Table: reporting.kpi_trade_import_dependency
**Row Count (estimated):** 4,414
### Columns
| Column Name | Data Type |
|---|---|
| area_code | VARCHAR |
| area | VARCHAR |
| year | BIGINT |
| import_quantity | DOUBLE |
| export_quantity | DOUBLE |
| total_trade_qty | DOUBLE |
| import_dependency_pct | DOUBLE |
---
## 884. Table: reporting.kpi_trade_import_diversification
**Row Count (estimated):** 2,870
### Columns
| Column Name | Data Type |
|---|---|
| area_code | BIGINT |
| area | VARCHAR |
| year | INTEGER |
| n_significant_partners | BIGINT |
---
