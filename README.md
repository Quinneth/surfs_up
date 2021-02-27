# surfs_up

## Purpose

Refactor code to provide query resuts for temperature trends in the months of June and December in Oahu, Hawaii to determine the feasibllity of a year-round ice cream shop.

## Resouces
- Data source:  hawaii.sqlite
- Software:  Python, Jupyter Notebook, Pandas, SQLAlchemy

## Overview 
The analysis is comprised of summary statistics using hawaii.sqlite database for the months of June and December. Statistics include:
- count
- Mean
- standard deviation
- Minimum
- Maximum
- Quartiles

### Temperature Results:

***June***
- count:         1700 
- Mean:          75
- sd:            3.3
- Minimum:       64
- Maximum:       85
- 25%:           73
- 50%:           75
- 75%:           77<br>

***December***  
- count:        1517 
- Mean:         71
- sd:           3.7
- Minimum:      56
- Maximum:      83
- 25%:          69
- 50%:          71
- 75%:          74


Three key differences in weather between June and December.
1. There is a singificant difference in minimum temperatures between June and December
2. There is a greater variation from the mean in December.
3. The sample size is less for December.

## Summary

Oahu has an overall temperate climate. The average temperatures are slightly high for June and the standard deviation indicates higher variations in December.<br> 

Additional queries to perform to gather more weather data for June and Decembber:
1. Query daily results
2. Query weather station results closest to optimal surfing terrain. 
