#Shapefiles

Common shapefiles for mapping projects on WRAL, mostly adapted/simplified from [TIGER files](https://www.census.gov/geo/maps-data/data/tiger.html).

Protip: Simplify shapefiles for publication [using mapshaper](http://mapshaper.org/).

Click the links below to download the zip files.

##Counties
**[county_water.zip](https://github.com/wraldata/shapefiles/blob/master/counties/county_water.zip?raw=true)**: Shapefile includes all 100 North Carolina counties with water features subtracted from geometry.

**Notable Attributes**

- County name stored in `NAME`
- County FIPS code stored in `COUNTYFP`

##Election precincts
**[precinct_water](https://github.com/wraldata/shapefiles/blob/master/precincts/precinct_water.zip?raw=true)**: Shapefille includes all North Carolina precincts with water features subtracted from geometry.

**Notable Attributes**

- County name stored in `County`
- Precinct designation stored in `Name` (not unique)
- "County-Precinct" stored in `co-prec` (unique)
