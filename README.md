# surfs_up
Module 9

## Overview of Project
I am using python and a sqlite file with weather data to help a client determine 
the viability of opening a shop that sells surfing equipment and ice cream. To do
this, I am looking at temperature and rain totals per month. The client is also
concerned about the amount of data collected per station. Specifically, the client 
wants to know if Oahu is warm and dry enough to have a surf/ice cream shop.

## Results
### three major points from two analysis 
•	The temperatures in June and December are very similar to each other. The standard 
deviation of both has a delta of only .5 degrees (Jun. sd = 3.25 and Dec. sd = 3.75).
•	June has a slightly higher maximum temperature than December (Jun. = 85 and Dec. = 
83) but the minimum temperature for December is almost 10 degrees lower than June.
•	Part of the reason for the difference in descriptive statistics between June and 
December is that December has almost 200 more 70 degree observations than June. However, 
June in general has more 12% observations than December (see the graphs below).  

## Summary
### Observation
The client wanted to know about temperatures in June and December and was curious
about rain totals for the year but did not ask about precipitation vs temperature
for those months. 

### Limitation
In addition to temperature and precipitation, it may be helpful to look at population
density. Since Oahu is a tourist destination, knowing how many potential customers
will be on the island would provide insights into pricing strategies.

### Suggestions
1). Create a table that shows population density and date.
2). Create a querry that shows precipitation, temperature and date.
3). Create a querry from the new table showing population density and
precipitation, merged on date (the rise in population density might be greater than
reduced demand durring rain or may have no effect on demand or may have a greater
impact on demand...we should investigate this for the client).