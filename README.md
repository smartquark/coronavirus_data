
# coronavirus_data

## data sources:

### JHU CSSE

Source:

- https://docs.google.com/spreadsheets/d/1yZv9w9zRKwrGTaR-YzmAqMefw4wMlaXocejdxZaTs6w/htmlview?usp=sharing&sle=true

Data:

* [jhu-report_date.tsv](data/jhu-report_date.tsv) : Daily total

* [jhu.tsv](data/jhu.tsv) : Latest



### BNO News

Source:

- https://bnonews.com/index.php/2020/01/the-latest-coronavirus-cases/

Data:

* [bno-cities.tsv](data/bno-cities.tsv) : List of cities (with coordinates)

* [bno-events.tsv](data/bno-events.tsv) : events by location (need to join with [bno-cities.tsv](data/bno-cities.tsv) by location_id (location_id is not fixed, might change during next updates)

* [bno.tsv](data/bno.tsv) : List by countries/region





### Coronavirus - case tracking worksheets

Source:

- https://www.reddit.com/r/China_Flu/comments/exelra/new_suspected_cases_february_2nd_edition_all_new/
- https://docs.google.com/spreadsheets/d/1qbE-UuJYw5V4FkyMZ-LplvUQZlut4oa5Zl3lrSmN_mk/htmlview

Data:

* [casetracking.tsv](data/casetracking.tsv)


