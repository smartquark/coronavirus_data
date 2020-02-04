
# coronavirus_data

## Notes

- data here are used mainly for my own visualizations at https://nyem69.github.io/coronavirus_dashboard



## Data sources:


### WHO

- https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports



### JHU CSSE

- https://systems.jhu.edu/research/public-health/ncov/
- [OpsDashboard](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)
- Google Sheets :
[v1](https://docs.google.com/spreadsheets/d/169AP3oaJZSMTquxtrkgFYMSp4gTApLTTWqo25qCpjL0/htmlview?usp=sharing&sle=true#), [v2](https://docs.google.com/spreadsheets/d/1yZv9w9zRKwrGTaR-YzmAqMefw4wMlaXocejdxZaTs6w/htmlview?usp=sharing&sle=true#), [v3](https://docs.google.com/spreadsheets/d/1wQVypefm946ch4XDp37uZ-wartW4V7ILdg-qYiDXUHM/htmlview?usp=sharing&sle=tru#e)
- [Google sheet (Time series)](https://docs.google.com/spreadsheets/d/1UF2pSkFTURko2OvfHWWlFpDFAr1UxCBA4JLwlSP6KFo/htmlview?usp=sharing&sle=true#)

	Data:

	* [jhu.tsv](data/jhu.tsv) : Latest by region/country
	* [jhu-confirmed_daily.tsv](data/jhu-confirmed_daily.tsv) : Daily total of confirmed cases
	* [jhu-coordinates.tsv](data/jhu-coordinates.tsv) : Latest by country with coordinates





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



