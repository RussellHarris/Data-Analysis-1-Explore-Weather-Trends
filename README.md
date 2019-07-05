# Udacity-Data-Analyst-Project1-Explore-Weather-Trends
Since I was living in New York City (NYC) at the time of this project, I compared its temperature trend against the global trend.

## Project Summary (from Udacity)
In this project, you will analyze local and global temperature data and compare the temperature trends where you live to overall global temperature trends.

## Steps Performed
1. Extract the data from the provided database using SQL
2. Paste reslts into Excel
3. Plot the line chart using **moving average** rather than yearly average to smooth out the lines and make trends more observable

## Observations
1. The global 10 year moving average line is “smoother” than the NYC moving average line. The most likely explanation is that the global average is made from more data points (345 cities are returned when using the query: SELECT COUNT(*) FROM city_list).
2. Besides colder temperatures in the late 1700s, on average the 10 Year Moving Average of New York City is 1 degree Celcius GREATER than the Global Average (NYC is hotter than the global average).
a. Besides the late 1700s, the 10 Year Moving Average for New York City roughly follows the same slope as the 10 Year Moving Average for the global temperature.
3. From 1750 to 2013, both the NYC moving average and Global moving average temperature have gone up nearly 2 degrees Celcius. The gains in the last 100 years (between 1900- 2000) were greater than the previous 100 years (1800-1900).
4. The 10-year moving average temperature increase from the last 50 years (1963-2013) does NOT appear to be slowing down nor leveling off. The consequences are unknown at this time, but could have grave impacts in the future.
