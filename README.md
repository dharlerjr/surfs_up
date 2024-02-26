# Surfs Up

## Overview of Analysis

### Background

In this module, we are tasked with analyzing precipitation data in support of our business venture: opening up a surf and ice cream shop on the island of Oahu. Our objective is to ensure that our surf and ice cream shop will not be driven out of business by poor weather conditions. To complete our task, we will need the following tools: anaconda and jupyter notebook to perform the bulk of our analysis, SQLAlchemy to query our SQLite weather database, and Flask to build a web application to share our results.

### Purpose

After analyzing one year's worth of precipitation data, we have determined that Oahu is an ideal location for our new surf and ice cream shop. However, our investor W. Avy has now asked us to further solidify our conclusion by examining temperature trends during the months of June and December from the years 2010 to 2017. 

## Results

Here are two screenshots displaying the summary statistics for the months of June and December, respectively.

<img src="https://github.com/dharlerjr/surfs_up/blob/main/Resources/D1_June_Temps.PNG" width="300" height="375"> <img src="https://github.com/dharlerjr/surfs_up/blob/main/Resources/D2_Dec_Temps.PNG" width="300" height="375">

From these summary statistics, we can see that...

- Despte being sixth months apart, the average temperatures for the months of June and December are only 3°F apart!
- The maximum temperature for the month of December is 83°F. Thus, during a month which one may reasonably expect to be consistenly cold, December still holds at least a few quality-weather surf days.
- Expanding further on our previous point, by examining the Standard Deviation for the month of December, we can conclude that a majority of our temperatures lie close to our mean of 71°F. Thus, not only does December hold "at least a few" quality-weather surf days, but rather, December holds plenty of quality-weather surf days.

## Summary

In summary, despite being sixth months apart, the months of June and December in Oahu both provide plenty of quality-weather surf days. Therefore, the surf and ice cream shop will be sustainable year-round. Listed below are two additional queries we could perform to further our analysis:

1. Determine how rapidly temperatures in Oahu are increasing or decreasing from year to year. For instance, we could compare the average temperature from each month, for each year in our dataset and plot the results as they change over time.
2. Similarly, from year to year, we could examine the standard deviations of the temperatures to determine if temperatures in Oahu are staying consistent or starting to vary more and more.
