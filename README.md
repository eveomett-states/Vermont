# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Vermont Json and Shapefile

This json and shapefile were created by Professor Ellen Veomett and her student Ananya Agarwal using the corresponding jupyter notebook.

# **Sources**
All data retrieved 05/29/24:

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/vermont-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[State House District data](https://redistrictingdatahub.org/dataset/2022-vermont-house-of-representatives-districts-approved-plan/): 2022 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2022-vermont-senate-districts-approved-plan/): 2022 State Senate Approved Plan

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-vermont-precinct-boundaries-and-election-results-shapefile/)**:**  VEST 2020 vermont precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-vermont-precinct-and-election-results/)**:**  VEST 2018 vermont precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-vermont-precinct-and-election-results/)**:**  VEST 2016 vermont precinct and election results

## Processing
Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup). 

## Metadata
- `COUNTYFP20`: County FIPS code of 2020
- `STATEFP20`: State FIPS code of 2020
- `NAME20`: Census tabulation block name of 2020
- `SEND`: State Senate district for 2021 State Senate Adopted Plan
- `HDIST`: State House district for 2021 State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `ATG16D`: Number of votes for 2016 Democratic attorney general candidate
- `ATG16R`: Number of votes for 2016 Republican attorney general candidate
- `ATG16O`: Number of votes for 2016 other party's attorney general candidate
- `ATG18D`: Number of votes for 2018 Democratic attorney general candidate
- `ATG18R`: Number of votes for 2018 Republican attorney general candidate
- `ATG18O`: Number of votes for 2018 other party's attorney general candidate
- `ATG20D`: Number of votes for 2020 Democratic attorney general candidate
- `ATG20R`: Number of votes for 2020 Republican attorney general candidate
- `ATG20O`: Number of votes for 2020 other party's attorney general candidate
- `AUD16O`: Number of votes for 2016 Democratic Auditor
- `AUD16R`: Number of votes for 2016 Republican Auditor
- `AUD16O`: Number of votes for 2016 other party's Auditor
- `AUD18O`: Number of votes for 2018 Democratic Auditor
- `AUD18R`: Number of votes for 2018 Republican Auditor
- `AUD18O`: Number of votes for 2018 other party's Auditor
- `AUD20O`: Number of votes for 2020 other party's Auditor
- `GOV16D`: Number of votes for 2016 Democratic gubernatorial candidate
- `GOV16R`: Number of votes for 2016 Republican gubernatorial candidate
- `GOV16O`: Number of votes for 2016 other party's gubernatorial candidate
- `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
- `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
- `GOV18O`: Number of votes for 2018 other party's gubernatorial candidate
- `GOV20D`: Number of votes for 2020 Democratic gubernatorial candidate
- `GOV20R`: Number of votes for 2020 Republican gubernatorial candidate
- `GOV20O`: Number of votes for 2020 other party's gubernatorial candidate
- `HAL16O`: Number of votes for 2016 other party's congressional candidate
- `HAL18D`: Number of votes for 2018 Democratic congressional candidate
- `HAL18R`: Number of votes for 2018 Republican congressional candidate
- `HAL18O`: Number of votes for 2018 other party's congressional candidate
- `HAL20D`: Number of votes for 2020 Democratic congressional candidate
- `HAL20O`: Number of votes for 2020 other party's congressional candidate
- `LTG16D`: Number of votes for 2016 Democratic Lieutenant Governor candidate
- `LTG16R`: Number of votes for 2016 Republican Lieutenant Governor candidate
- `LTG16O`: Number of votes for 2016 other party's Lieutenant Governor candidate
- `LTG18R`: Number of votes for 2018 Republican Lieutenant Governor candidate
- `LTG18O`: Number of votes for 2018 other party's Lieutenant Governor candidate
- `LTG20D`: Number of votes for 2020 Democratic Lieutenant Governor candidate
- `LTG20R`: Number of votes for 2020 Republican Lieutenant Governor candidate
- `LTG20O`: Number of votes for 2020 other party's Lieutenant Governor candidate
- `PRE16D`: Number of votes for 2016 Democratic President
- `PRE16R`: Number of votes for 2016 Republican President
- `PRE16O`: Number of votes for 2016 other party's President
- `PRE20D`: Number of votes for 2020 Democratic President
- `PRE20R`: Number of votes for 2020 Republican President
- `PRE20O`: Number of votes for 2020 other party's President
- 'SOS16O': Number of votes for 2016 other party's Secretary of State
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State
- `SOS18R`: Number of votes for 2018 Republican Secretary of State
- `SOS18O`: Number of votes for 2018 other party's Secretary of State
- `SOS20D`: Number of votes for 2020 Democratic Secretary of State
- `SOS20R`: Number of votes for 2020 Republican Secretary of State
- `SOS20O`: Number of votes for 2020 other party's Secretary of State
- `TRE16O`: Number of votes for 2016 other party's Treasurer
- `TRE18D`: Number of votes for 2018 Democratic Treasurer
- `TRE18R`: Number of votes for 2018 Republican Treasurer
- `TRE18O`: Number of votes for 2018 other party's Treasurer
- `TRE20D`: Number of votes for 2020 Democratic Treasurer
- `TRE20R`: Number of votes for 2020 Republican Treasurer
- `TRE20O`: Number of votes for 2020 other party's Treasurer
- `USS16D`: Number of votes for 2016 Democratic senate candidate
- `USS16R`: Number of votes for 2016 Republican senate candidate
- `USS16O`: Number of votes for 2016 other party's senate candidate
- `USS18R`: Number of votes for 2018 Republican senate candidate
- `USS18O`: Number of votes for 2018 other party's senate candidate
