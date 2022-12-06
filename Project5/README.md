# Flights Data Exploration
## Thi My Hao PHAM


## Dataset

The data consists of information regarding 7,000,000 flights, including
departure delay, actual flights nimutes, schedure flights minutes, origin, and reason delay,.. The dataset can be found in:
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7
"2007.csv.bz2" : Have flight on-time or delay in 2007. The reason I dont chose 2008 is data of 2008 have 4 first month, it's not enought data.
"plane-data.csv" : Have manufacture of airline
"airports.csv" : Have city, state of airline


## Summary of Findings

Departure delay had a surprisingly high amount of correlation with the reason delay (LateAircraftDelay, WeatherDelay, NASDelay, CarrierDelay, TaxiIn)
LateAircraftDelay, WeatherDelay, NASDelay, CarrierDelay, TaxiIn dont have correction clearly beetwen each orther. A small negative correlation was observed between Cancelled, Diverted, Distance, ArrTime, but neither of these variables show a strong correlation with price, so they won't be explored further. There was also 2 cols StateDest and Manufacturer have link with delay minutes


## Key Insights for Presentation

For the presentation, I focus on just the influence of the reason delay, month, manufacture, city, state to Departure Delay. I start by introducing theprice variable, followed by the reason delay, then group by month and chart, group by manufacture and chart, group by city origin and chart, group by state origin and chart.