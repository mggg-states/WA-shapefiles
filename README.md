# Benton County, Washington Election Shapefiles
This shapefile was obtained from the State of Washington and processed by members of the Metric Geometry and Gerrymandering Group (MGGG) and Geodata Bootcamp (GDBC) alum Camryn Hollarsmith.

## Sources
The Benton county precinct shapefile was obtained from the [Washington Secretary of State](https://www.sos.wa.gov/elections/research/precinct-shapefiles.aspx). Election data come from the [Washington Secretary of State Elections Division](https://results.vote.wa.gov/results/20161108/benton/). 2010 Decennial Census demographic data were downloaded from the [Census API](https://api.census.gov/data/2010/dec/sf1). The 2010 census block shapefile for all of Washington state was downloaded from the US Census Bureau’s [TIGER/Line Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html).


## Processing
Some very minor boundary edits were necessary to validate the geometry. Demographic data was aggregated from the block level using MGGG’s proration software. 

## Metadata
* `STATE`: State
* `STATEFP`: State FIPS code
* `COUNTY`: County name
* `COUNTYFP`: County FIPS code
* `Precinct`: Precinct name
* `CODE`: Precinct code
*	`PRES16D`: Number of votes for 2016 Democratic presidential candidate
*	`PRES16R`: Number of votes for 2016 Republican presidential candidate
*	`SEN18D`: Number of votes for 2018 Democratic senate candidate
*	`SEN18R`: Number of votes for 2018 Republican senate candidate
*	`GOV16D`: Number of votes for 2016 Democratic gubernatorial candidate
*	`GOV16R`: Number of votes for 2016 Republican gubernatorial candidate
*	`AUD16D`: Number of votes for 2016 Democratic auditor candidate
*	`AUD16R`: Number of votes for 2016 Republican auditor candidate
*	`LG16D`: Number of votes for 2016 Democratic lieutenant governor candidate
*	`LG16R`: Number of votes for 2016 Republican lieutenant governor candidate
*	`TRE16D`: Number of votes for 2016 Democratic treasurer candidate
*	`TRE16R`: Number of votes for 2016 Republican treasurer candidate
*	`AG16D`: Number of votes for 2016 Democratic attorney general candidate
*	`AG16R`: Number of votes for 2016 Republican attorney general candidate
*	`SOS16D`: Number of votes for 2016 Democratic secretary of state candidate
*	`SOS16R`: Number of votes for 2016 Republican secretary of state candidate
* `TOTPOP`: Total population from 2010 Decennial Census
* `NH_WHITE`: White, non-hispanic, population from 2010 Decennial Census
* `NH_BLACK`: Black, non-hispanic, population from 2010 Decennial Census
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population from 2010 Decennial Census
* `NH_ASIAN`: Asian, non-hispanic, population from 2010 Decennial Census
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population from 2010 Decennial Census
* `NH_OTHER`: Other race, non-hispanic, population from 2010 Decennial Census
* `NH_2MORE`: Two or more races, non-hispanic, population from 2010 Decennial Census
* `HISP`: Hispanic population from 2010 Decennial Census
* `VAP`: Total voting age population from 2010 Decennial Census
* `HVAP`: Hispanic voting age population from 2010 Decennial Census
* `WVAP`: White, non-hispanic, voting age population from 2010 Decennial Census
* `BVAP`: Black, non-hispanic, voting age population from 2010 Decennial Census
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population from 2010 Decennial Census
* `ASIANVAP`: Asian, non-hispanic, voting age population from 2010 Decennial Census
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population from 2010 Decennial Census
* `OTHERVAP`: Other race, non-hispanic, voting age population from 2010 Decennial Census
* `2MOREVAP`: Two or more races, non-hispanic, voting age population from 2010 Decennial Census

## Projection
This shapefile uses a NAD83/UTM Zone 10N projection (ESPG:6339).

## Rating
We give this shapefiles an A rating. All data were obtained from the state government and were processed under MGGG supervision.
