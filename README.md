# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# North Carolina Json

This shapefile was processed by Professor Ellen Veomett and her student Arbie Hsu using the corresponding jupyter notebook.  As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30 m) were changed to queen adjacencies.

# **Sources**
All data retrieved 02/21/25:

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/north-carolina-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2024-north-carolina-congressional-districts-approved-plan/): Enacted by the NC General Assembly on October 25, 2023 as Senate Bill 757, becoming Session Law 2023-145.

[State House District data](https://redistrictingdatahub.org/dataset/2024-north-carolina-house-of-representatives-districts-approved-plan/): Enacted by the NC General Assembly on October 25, 2023 as House Bill 898, becoming Session Law 2023-149.

[State Senate District data](https://redistrictingdatahub.org/dataset/2022-north-carolina-senate-districts-approved-plan/): Enacted by the NC General Assembly on October 25, 2023 as Senate Bill 758, becoming Session Law 2023-146

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-north-carolina-precinct-boundaries-and-election-results-shapefile/)**:**  VEST 2020 North Carolina precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-north-carolina-precinct-boundaries-and-election-results-shapefile/)**:**  VEST 2018 North Carolina precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-north-carolina-precinct-and-election-results/)**:**  VEST 2016 North Carolina precinct and election results

[2020 County data](https://redistrictingdatahub.org/dataset/north-carolina-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

## Preprocessing
Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup). 

## Metadata
- `COUNTY_ID20`: County ID
- `COUNTY_NAM20`: County Name
- `ENR_DESC20`: Voting District name
- `PREC_ID20`: Precinct ID
- `CD`: Congressional district ID
- `SEND`: State Senate district
- `HDIST`: State House district
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
- 'AGR16D': Number of votes for 2016 Democratic Agriculture Commissioner candidate
- 'AGR16R': Number of votes for 2016 Republican Agriculture Commissioner candidate
- 'AGR20D': Number of votes for 2020 Democratic Agriculture Commissioner candidate
- 'AGR20R': Number of votes for 2020 Republican Agriculture Commissioner candidate
- `ATG16D`: Number of votes for 2016 Democratic attorney general candidate
- `ATG16R`: Number of votes for 2016 Republican attorney general candidate
- `ATG20D`: Number of votes for 2020 Democratic attorney general candidate
- `ATG20R`: Number of votes for 2020 Republican attorney general candidate
- `AUD16D`: Number of votes for 2016 Democratic Auditor candidate
- `AUD16R`: Number of votes for 2016 Republican Auditor candidate
- `AUD20D`: Number of votes for 2020 Democratic Auditor candidate
- `AUD20R`: Number of votes for 2020 Republican Auditor candidate
- `GOV16D`: Number of votes for 2016 Democratic gubernatorial candidate
- `GOV16R`: Number of votes for 2016 Republican gubernatorial candidate
- `GOV16O`: Number of votes for 2016 other party's gubernatorial candidate
- `GOV20D`: Number of votes for 2020 Democratic gubernatorial candidate
- `GOV20R`: Number of votes for 2020 Republican gubernatorial candidate
- `GOV20O`: Number of votes for 2020 other party's gubernatorial candidate
- `INS16D`: Number of votes for 2016 Democratic Insurance Commissioner candidate
- `INS16R`: Number of votes for 2016 Republican Insurance Commissioner candidate
- `INS20D`: Number of votes for 2020 Democratic Insurance Commissioner candidate
- `INS20R`: Number of votes for 2020 Republican Insurance Commissioner candidate
- `LAB16D': Number of votes for 2016 Democratic Labor Commissioner candidate
- `LAB16R': Number of votes for 2016 Republican Labor Commissioner candidate
- `LAB16O': Number of votes for 2016 other party's Labor Commissioner candidate
- `LAB20D': Number of votes for 2020 Democratic Labor Commissioner candidate
- `LAB20R': Number of votes for 2020 Republican Labor Commissioner candidate
- `LTD16D`: Number of votes for 2016 Democratic Lieutenant Governor candidate
- `LTD16R`: Number of votes for 2016 Republican Lieutenant Governor candidate
- `LTD16O`: Number of votes for 2016 other party's Lieutenant Governor candidate
- `LTD20D`: Number of votes for 2020 Democratic Lieutenant Governor candidate
- `LTD20R`: Number of votes for 2020 Republican Lieutenant Governor candidate
- `PRE16D`: Number of votes for 2016 Democratic presidential candidate
- `PRE16R`: Number of votes for 2016 Republican presidential candidate
- `PRE16O`: Number of votes for 2016 other party's presidential candidate
- `PRE20D`: Number of votes for 2020 Democratic presidential candidate
- `PRE20R`: Number of votes for 2020 Republican presidential candidate
- `PRE20O`: Number of votes for 2020 other party's presidential candidate
- `SAC16D`: Number of votes for 2016 Democratic State Appeals Court candidate
- `SAC16R`: Number of votes for 2016 Republican State Appeals Court candidate
- `SAC16O`: Number of votes for 2016 other party's State Appeals Court candidate
- `SAC18D`: Number of votes for 2018 Democratic State Appeals Court candidate
- `SAC18R`: Number of votes for 2018 Republican State Appeals Court candidate
- `SAC18O`: Number of votes for 2018 other party's State Appeals Court candidate
- `SAC20D`: Number of votes for 2020 Democratic State Appeals Court candidate
- `SAC20R`: Number of votes for 2020 Republican State Appeals Court candidate
- `SOS16D`: Number of votes for 2016 Democratic Secretary of State candidate
- `SOS16R`: Number of votes for 2016 Republican Secretary of State candidate
- `SOS20D`: Number of votes for 2020 Democratic Secretary of State candidate
- `SOS20R`: Number of votes for 2020 Republican Secretary of State candidate
- `SPI16D`: Number of votes for 2016 Democratic Superintendent of Public Instruction candidate
- `SPI16R`: Number of votes for 2016 Republican Superintendent of Public Instruction candidate
- `SPI20D`: Number of votes for 2020 Democratic Superintendent of Public Instruction candidate
- `SPI20R`: Number of votes for 2020 Republican Superintendent of Public Instruction candidate
- `SSC16D`: Number of votes for 2016 Democratic State Supreme Court candidate
- `SSC16R`: Number of votes for 2016 Republican State Supreme Court candidate
- `SSC18D`: Number of votes for 2018 Democratic State Supreme Court candidate
- `SSC18R`: Number of votes for 2018 Republican State Supreme Court candidate
- `SSC20D`: Number of votes for 2020 Democratic State Supreme Court candidate
- `SSC20R`: Number of votes for 2020 Republican State Supreme Court candidate
- `TRE16D`: Number of votes for 2016 Democratic Treasurer candidate
- `TRE16R`: Number of votes for 2016 Republican Treasurer candidate
- `TRE20D`: Number of votes for 2020 Democratic Treasurer candidate
- `TRE20R`: Number of votes for 2020 Republican Treasurer candidate
- `USS16D`: Number of votes for 2016 Democratic senate candidate
- `USS16R`: Number of votes for 2016 Republican senate candidate
- `USS16O`: Number of votes for 2016 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate

