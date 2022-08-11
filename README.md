# Surf Shop Analysis

# Overview

For this project, we analyzed weather data as part of an proposal to present to potential investors. The business idea was to open a surf and ice cream shop on the island of Oahu and the primary concerns centered around whether or not the weather was conducive to making this endeavour successful. For this specific summary, we looked at temperature from two different months - June and December.

# Results

There are (obvioulsy) differences in temperature between June and December, specifically when looking at the mean, maximum and minimum temperature. Our dataset included 1700 temperature readings in June and 1517 in December.

## June

- The mean temperature is 75.0 degrees Fahrenheit.
- The maximum temperature is 85.0 degrees Fahrenheit.
- The minimum temperature is 64.0 degrees Fahrenheit.

![June](https://github.com/brianbutler08/surfs_up/blob/main/images%20for%20summary/June%20temperature%20summary.png)

## December

- The mean temperature is 71.0 degrees Fahrenheit.
- The maximum temperature is 83.0 degrees Fahrenheit.
- The minimum temperature is 56.0 degrees Fahrenheit.

![Dec](https://github.com/brianbutler08/surfs_up/blob/main/images%20for%20summary/December%20temperature%20summary.png)

# Summary

When looking only at temperature summary statistics, it appears that June and December do not vary as much as one might expect. Their relatively similar temperature profiles strengthens the idea for a surfing and ice cream shop on the island. One could expect a steady flow of locals and tourists throughout the year to take advantage of the nice weather conditions that would visit the shop and provide enough of a customer base to make it successful. 

## Additional Queries

Of course temperature alone is only one component of weather and there are multiple other factors to investigate in order to get a more complete picture of the climate on Oahu. The most obvious place to start would be to do a deeper dive into our precipitation data from earlier on in the analysis. Our preliminary work was to quickly graph a multi-year dataset to identify cycles of precipitation, but we should probably be looking at it in a similar manner to the temperature data above and see how temperature and rainfall are related. 

![precip](https://github.com/brianbutler08/surfs_up/blob/main/images%20for%20summary/precip%20graph.png)

The second important factor to develop a query for would be wave conditions. It doesn't matter how nice the weather is, there won't be any surfers if there aren't any waves to surf. Obtaining a datset of wave data and querying it to look at general wave conditions throughout the year would be an essential step to take in order to convince investors to fund a surfing enterprise. For example, the Pacific Islands Ocean Observing System (PacIOOS) website (http://www.pacioos.hawaii.edu/) provides a large amount of wave data with measurements every thirty minutes. They have six measurement buoys around Oahu alone and provide observation and forecast data in many forms. Historical data could be downloaded or scraped and queried to look for trends. 

Example of wave data chart from PacIOOS:
![PacIOOS](https://github.com/brianbutler08/surfs_up/blob/main/images%20for%20summary/wave%20graph.png)
