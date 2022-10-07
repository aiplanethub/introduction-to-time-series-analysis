​
You already know about stationary data from the earlier lessons. But before moving further to understand the different
techniques to check the stationarity of the data, it is worth
considering why the concept of stationarity has become
important in time series analysis and its various applications.

## Learning Objectives

* Why is Stationarity Important?
* Different Ways of Detecting Stationarity
* ADF & KPSS Tests
* Implementing ADF and KPSS Tests on Real-World Dataset
* Notebook​
​
## Why is Stationarity Important?

* First, because the stationary processes are easier to analyze
* When forecasting or predicting the future, most time series models assume that each point is independent of one another. The best indication of this is when the dataset of past instances is stationary. For data to be stationary, the statistical properties of a system do not change over time. This does not mean that the values for each data point have to be the same, but the overall behavior of the data should remain constant.






​![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_6ef9094719c6455abb6944fcde25929b.png)





## Techniques to Detect Stationarity in Data

* The ability to determine whether a time series is stationary is important.
* Different techniques to detect stationarity in time series data are:
  * Visualizations: Looking at the data or the autocorrelation function plots. As the name suggests, autocorrelation means the correlation of the data with itself. You will understand this in detail in upcoming lessons
  * Parametric / Statistical tests: Tests like the Augmented Dickey Fuller Test, the KPSS test

​





### Visualizations

* The most basic methods for stationarity detection rely on
plotting the data, or functions of it, and determining
visually whether they present some known property of
stationary (or non-stationary) data. This we have already
seen in the lesson 2 (i.e. Key Concepts in Time Series
Analysis) of module 1 (i.e. Fundamentals of Time Series)
* But don’t worry if you don’t remember it, you will again
see it in the upcoming video.

​



## ADF and KPSS Test

* Augmented Dickey Fuller test (ADF Test) is a common statistical test used to test whether a given Time series is stationary or not. It is one of the most commonly used statistical test when it comes to analyzing the stationarity of a series.
* The Kwiatkowski–Phillips–Schmidt–Shin (KPSS) test figures out if a time series is stationary around a mean or linear trend. Like ADF test, the KPSS test is also commonly used to analyse the stationarity of a series.
* The tutor in the upcoming video discusses more about these tests in detail.

**Note 1**: Don’t worry if you are not able to understand these
two tests on the first go. These are a little mathematical
topics. You will be able to make it as you progress ahead
learning time series

**Note 2**: The tutor mentions about AR, MA and ARMA models
in the video. Don’t worry about these terms you will be
learning this in the upcoming lessons.
​








​
​<iframe width="560" height="315" src="https://www.youtube.com/embed/YNm0h-qZo9g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

​







### Notebook

https://github.com/srivatsan88/End-to-End-Time-Series/blob/master/TimeSeries_Stationary_Test.ipynb