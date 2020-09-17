# countrydetails-data
Data used in the countrydetails python package

> all files are in json only

### Data Structure
- `name`
    - `official` - official name in english
    - `alt_spellings` - alternative spellings
    - `native` - list of all native names
- `area` - Area of the country in (km)2
- `borders` - Borders of the country
- `calling code` - International calling code of the country
- `demonym` - name of residents
- `timezones` - List of time zones of a country
- `continent` - Continent of the country
- `governement` - Type of Governement 
- `independence` - Independence year of a country
- `temperature` - Average temperature of a country
- `expectancy` - Average life expectancy of a country
- `dish` - National dish of a country
- `symbol` - National symbol of a country
- `density` - Density of a country
- `location` - Region of a country
- `religion` - Religion of a country
- `capital` - capital city
- `capital_latlng` - capital city longitude and latitude
- `ISO` - ISO code alpha-2 alpha-3
- `currency` - currency code(s)
- `latlng` - Longitude and latitude of a country
- `tld` - country code top-level domain
- `languages` - list of spoken languages in the country
- `translations` - list of name translations
- `flag` - SVG link for the country flag
- `states` - List of states with thier state codes and cities
- `wiki` - Wikipedia page of a country
- `geo`
    - `continent` - continents that country lies in
        - key: two-letter continent code
        - value: name of the continent in english
    - `postal_code` - geographical area postal code
    - `latitude` - short form of latitude coordinate point
    - `latitude_dec` - described latitude coordinate point
    - `longitude` - short form of longitude coordinate point
    - `longitude_dec` - described longitude coordinate point
    - `max_latitude` - maximum latitude coordinate point
    - `max_longitude` - maximum longitude coordinate point
    - `min_latitude` - minimum latitude coordinate point
    - `min_longitude` - minimum longitude coordinate point
    - `area` - land area in km²
    - `region` - geographical region
    - `subregion` - geographical sub-region
    - `world_region` - geographical world region
    - `region_code` - geographical region numeric code
    - `subregion_code` - geographical sub-region numeric code 
    - `landlocked` - landlocked status
    - `borders` - land borders
    - `independent` - independent status


------------

### Credits

The data used above is the combination of [Samayo](https://github.com/samayo/country-json "Samayo ") and [therebelrobot](https://github.com/therebelrobot/countryjs "therebelrobot")

