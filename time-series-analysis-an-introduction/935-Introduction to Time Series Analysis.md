## Learning Objectives

* What is Time Series?
* Why is time series analysis important?
* Uses of Time Series Analysis
* What is Time Series Data
* Examples of Time Series Data

## What is Time Series?

A time series is a sequence of numerical data points ordered in time.

Time series can have one or more variables that change over time.







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_40e6c4e4b4304bf88ba9703fb3fa4f1e.png)









## Why is time series analysis important?

* Time series analysis gives one the ability to see ahead of time.
* Time series analysis extracts meaningful statistics and other dataset characteristics to understand it.
* Time series allows you to analyze significant patterns such as trends, seasonality, cyclicity, and irregularity. Don't worry if you are unaware of some of these terms - we will soon understand them in detail.
* Time series analysis is essential to understand the underlying structure and function that produce the observations.
* Time series analysis can help to make better predictions
* Understanding the mechanisms of a time series allows a model to be developed that explains the data so that prediction, monitoring, or control can occur.





## Uses of Time Series Analysis

* Time series analysis can be helpful to see how a given asset, security, or economic variable changes over time.
* It can also be used to examine how the changes associated with the chosen data point compared to shifts in other variables over the same period.





## A case study

For example, suppose you wanted to analyze a time series of daily closing stock prices for a given stock over one year. You would obtain a list of all the closing prices for the stock from each day for the past year and list them in chronological order. This would be a one-year daily closing price time series for the stock.

Delving a bit deeper, you might analyze time series data with technical analysis tools to know whether the stock's time series shows any seasonality (We will delve more into seasonality in the upcoming slides).

This will help determine if the stock price reaches its maximum and minimum value at regular times each year. 

One can analyze this by taking the observed prices and correlating them to a chosen season.

Seasons can be traditional calendar seasons, such as summer and winter, or retail seasons, such as holiday seasons.


## What is Time Series Data?

* Sequentially ordered data over time
* Observations are typically collected at regular intervals
  * Every second / minute / hourly
  * Daily
  * Monthly
  * Quarterly / Yearly
* For example, if you run an IoT sensor, the data comes/streams continuously. When you talk about weather data, you may get weather updates every hour or maybe every 10 minutes or 20 minutes.
* So, depending on the data source, we can have various frequencies at which the data is being collected.


### Assumptions About Time Series Data
* The primary assumption in time series data is that it assumes that the past patterns and behaviors will continue in the future.


### How is it Different From Normal Machine Learning Problems?
In both types of problems, time plays a role, with historical data being used to train a model to predict the future. Both machine learning datasets are a collection of observations. So, what is the difference?

In a normal machine learning dataset, all historical observations are treated equally, whereas time series is a sequence of observations. These are captured sequentially in time; therefore, in the case of time series, the observations follow some order.

## Examples of Time Series Data

Some examples of time series data are:

* Energy Forecasting
* IoT Sensors in Industries and Smart Devices
* Hourly Weather Data / Wind Speed
* Quarterly / Annual Revenue
* Monthly Sales Data