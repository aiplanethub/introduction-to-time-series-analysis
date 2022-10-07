## Learning Objectives

* Importance of Time Series Data Analysis
* Hands-on Time Series Data Analysis
* Notebook


## Importance of Time Series Data Analysis

* Data analysis is a very important part of time series data. There are multiple factors to it.
* Some time series problems are often solved by proper data analysis.
* When we talk about data analysis for time series data, these are both statistical techniques and exploratory analysis.
* It helps to find the patterns of the data as well as the structure of the data. When we say pattern, we want to check if the data has seasonality, or increasing or decreasing trend in the data, if the data is cyclic, or if the data is stationary or non-stationary.
* It also helps you deal with missing data in time series data. For normal machine learning problems, we fill the missing values with mean, median, mode or drop the data. But in the case of time series data, to fill the missing values, we need to understand the structure of the data. In time series data, we cannot even drop the data as the order of the events that are happening in the time series world are very important.

​In the video below, the tutor will discuss the following things:
* The importance of data analysis for time series data in
detail
* Show different data analysis techniques, like,
autocorrelation plot, line plot, lag plot, range selector,
slider plot, etc., with running Python codes in the Google
Colab Notebook.
​
​









​<iframe width="560" height="315" src="https://www.youtube.com/embed/3sH1kisAK9s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
​













### Notebook
https://github.com/srivatsan88/End-to-End-Time-Series/blob/master/Timeseries_Data_analysis.ipynb

​
​

## Autocorrelation and Partial Autocorrelation

* Autocorrelation and partial autocorrelation plots are heavily used in time series analysis and forecasting.
* These are plots that graphically summarize the strength of a relationship between two observations:
  * The current observation in time series, and 
  * The observations at prior time steps

**Note:** Don’t worry if you have difficulty understanding these terms. You will make it as you progress ​through the course.

### Autocorrelation

* We can calculate the correlation for time series observations with previous time steps, called lags. 
* Because the correlation of the time series observations is calculated with values of the same series at previous times, this is called a serial correlation or an autocorrelation.









​![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_c5cb3376eb604260ac6000189823cda2.png)
​
​




### Partial Autocorrelation

A partial autocorrelation is a summary of the relationship
between an observation in a time series with observations at
prior time steps with the relationships of intervening
(occurring between) observations removed.










![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_be0d7019b3524d6db9dbebdd15220132.png)
​






### Intuitive Article On Autocorrelation and Partial Autocorrelation​
https://machinelearningmastery.com/gentle-introduction-autocorrelation-partial-autocorrelation/

The video below is optional to watch. It explains Autocorrelation and Partial Autocorrelation.

​
​
​<iframe width="560" height="315" src="https://www.youtube.com/embed/DeORzP0go5I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>