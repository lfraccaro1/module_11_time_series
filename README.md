# Module 11 Time Series
## Overview
In this project I am tasked with the following four steps.

First, I looked for patterns in hourly Google search traffic for Mercado Libre, to see if I could connect results to any financial events. I used hvPlot to create visual representations and compared monthly median values to see if traffic increased when financial statements were released.

Second, I mined the search traffic data to check for any predictable seasonal patterns. This was achieved by using `groupby` function to group the data by day of the week, and then usng hvPlot to visualise the traffic as a heatmap. Finally, I grouped the data by week of the year to look for traffic increases during winter holidays.

Third, I compared the search traffic with stock price patterns. This was achieved by concatenating two dataframes, calculating stock volatility and hourly percentage returns, and then reviewing the time series correlation. 

Last, I created a time series model that analyses and forecasts patterns in hourly search data. I achieved this using the `Prophet` forecasting model.
