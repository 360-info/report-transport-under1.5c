# `/data`

## `pt-access.csv`

Data on the percentage of people in cities with convenient public transport access—meaning a bus stop within 500m or a major stop (rail, metro or ferry) within 1km. Data is from:

- the [UN's SDG Data Portal](https://unstats.un.org/sdgs/dataportal/database)
- [OpenDataSoft's dataset of cities over 1000 people](https://public.opendatasoft.com/explore/dataset/geonames-all-cities-with-a-population-1000)
- [the UN's hierarchy of country regions](https://unstats.un.org/unsd/methodology/m49)

Columns include:

- `country_iso2`: country's ISO 3166-1 alpha-2 code
- `country_name`: country name
- `city`: city name
- `city_std`: ascii version of city name
- `year`: year of observation
- `region`: region the city is in according to the UN's hierarchy
- `subregion`: subregion according to the UN's hierarchy
- `geoname_id`: matched city in OpenDataSoft's dataset
- `lat`: latitude of the city
- `lon`: longitude of the city
- `population`: city's population
- `pct_pt_access`: percentage of people with convenient public transport access

`pt-access-ap.csv` is a version of this dataset limited to the Indo-Pacific.

## `transport-emissions.csv`

Data on the breakdown of greenhouse gas emissions into transport sub-sectors, as well as non-transport emissions (ie. everything else). Data is from:

- [Climate Trace](https://climatetrace.org)

Columns include:

- `iso2`: country's ISO 3166-1 alpha-2 code
- `iso3`: country's ISO 3166-1 alpha-3 code
- `name`: country name
- `gross_*`: gross greenhouse emissions in 2022, in units of tonnes of CO2-equivalent
- `population`: country's population
- `percapita_*`: per capita greenhouse emissions in 2022, in units of tonnes of CO2-equivalent per person

`transport-emissions-ap.csv` is a version of this dataset limited to the Indo-Pacific.