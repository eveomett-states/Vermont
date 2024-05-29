# vermont Election Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Ananya Agarwal.

# **Sources**
@author: eveomett AI for Redistricting, USF All data retrieved 05/29/24:

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/vermont-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[State House District data](https://redistrictingdatahub.org/dataset/2022-vermont-house-of-representatives-districts-approved-plan/): 2022 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2022-vermont-senate-districts-approved-plan/): 2022 State Senate Approved Plan

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-vermont-precinct-boundaries-and-election-results-shapefile/)**:**  VEST 2020 vermont precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-vermont-precinct-and-election-results/)**:**  VEST 2018 vermont precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-vermont-precinct-and-election-results/)**:**  VEST 2016 vermont precinct and election results

## Processing
Demographic and election data were joined to the shapefile using QGIS. Vermont does not release election results for towns with a total population under 50, thus 9 towns have been excluded from this module.

## Metadata
* `STATEFP10`: State FIPS code
* `COUNTYFP10`: County FIPS code
* `COUSUBFP10`: Sub-county FIPS code
* `GEOID10`: Town ID
* `NAME10`: Town name
* `NAMELSAD10`: Town legal and statistical name
* `ALAND10`: Area land in square meters
* `AWATER10`: Area water in square meters
* `INTPTLAT10`: Latitude of internal point
* `INTPTLON10`: Longitude of internal point
* `TOTPOP`: Total population from 2010 Decennial Census
* `WHITE`: White population from 2010 Decennial Census
* `BLACK`: Black population from 2010 Decennial Census
* `AMIN`: American Indian and Alaska Native population from 2010 Decennial Census
* `ASIAN`: Asian population from 2010 Decennial Census
* `NHPI`: Native Hawaiian and Pacific Islander population from 2010 Decennial Census
* `OTHER`: Population of other race from 2010 Decennial Census
* `2MORE`: Population of two or more races from 2010 Decennial Census
* `VAP`:  Population over the age of 18 from 2010 Decennial Census
* `HISP`: Hispanic population from the 2010 Decennial Census
* `SENDIST`: State Senate district ID
* `DISTNAME`: State Senate district name
* `PRES16D`: Number of votes for 2016 Democratic presidential candidate
* `PRES16R`: Number of votes for 2016 Republican presidential candidate
* `PRES16L`: Number of votes for 2016 Libertarian presidential candidate
* `PRES16G`: Number of votes for 2016 Green Party presidential candidate
* `TOTV16`: Total votes cast in 2016
* `SEN16D`: Number of votes for 2016 Democratic senate candidate
* `SEN16R`: Number of votes for 2016 Republican senate candidate
* `USH14D`: Number of votes for 2014 Democratic US house candidate
* `USH14R`: Number of votes for 2014 Republican US house candidate
* `TOTV14`: Total votes cast in 2014
* `PRES12D`: Number of votes for 2012 Democratic presidential candidate
* `PRES12R`: Number of votes for 2012 Republican presidential candidate
* `PRES12L`: Number of votes for 2012 Libertarian presidential candidate
* `TOTV12`: Total votes cast in 2012
* `SEN12B`: Number of votes for Bernie Sanders in 2012 senate race
* `SEN12R`: Number of votes for 2012 Republican senate candidate
* `USH12D`: Number of votes for 2012 Democratic US house candidate
* `USH12R`: Number of votes for 2012 Republican US house candidate

## Rating
We give this shapefile an A rating. All data was obtained from the state government and was processed by MGGG staff.