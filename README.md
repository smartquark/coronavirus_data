
# coronavirus_data

## data sources:

### JHU CSSE

- https://systems.jhu.edu/research/public-health/ncov/
- [OpsDashboard](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)
- [Google sheet](https://docs.google.com/spreadsheets/d/1yZv9w9zRKwrGTaR-YzmAqMefw4wMlaXocejdxZaTs6w/htmlview?usp=sharing&sle=true#)
- [Google sheet (Time series)](https://docs.google.com/spreadsheets/d/1UF2pSkFTURko2OvfHWWlFpDFAr1UxCBA4JLwlSP6KFo/htmlview?usp=sharing&sle=true#)

	Data:

	* [jhu.tsv](data/jhu.tsv) : Latest
	* [jhu-confirmed_daily.tsv](data/jhu-confirmed_daily.tsv) : Daily total of confirmed cases




### BNO News

- https://bnonews.com/index.php/2020/01/the-latest-coronavirus-cases/

	Data:

	* [bno-cities.tsv](data/bno-cities.tsv) : List of cities (with coordinates)

	* [bno-events.tsv](data/bno-events.tsv) : events by location (need to join with [bno-cities.tsv](data/bno-cities.tsv) by location_id (location_id is not fixed, might change during next updates)

	* [bno.tsv](data/bno.tsv) : List by countries/region





### Coronavirus - case tracking worksheets

- https://www.reddit.com/r/China_Flu/comments/exelra/new_suspected_cases_february_2nd_edition_all_new/
- https://docs.google.com/spreadsheets/d/1qbE-UuJYw5V4FkyMZ-LplvUQZlut4oa5Zl3lrSmN_mk/htmlview

	Data:

	* [casetracking.tsv](data/casetracking.tsv)

