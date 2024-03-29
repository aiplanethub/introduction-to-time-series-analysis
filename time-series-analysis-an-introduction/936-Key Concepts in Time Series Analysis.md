When we talk about time series data, there are some key concepts that we need to understand:
* Trend
* Seasonality
* Cyclic
* Stationarity
​



## Trend






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_e24da09bc2084ae78c31c5d27d644c85.png)






A trend exists when we see a long-term increase or decrease in the data. You can observe the above graph of the International Air Travel Series; the data is continuously increasing starting from 1949 till 1961. In the above example, the trend is increasing but can also decrease.

The trend need not be linear; it can also be exponential. There can also be a change in direction. First, the trend may be increasing, and after a certain point, the trend can be decreasing.

## Seasonality
​




![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_67e192d659b242cfa71f1235fc5c3aec.png)



A seasonal pattern occurs in the data when a time series is typically affected by the regular occurring pattern, i.e., every year, or maybe every month, etc., the sales may pick up, or every weekend the sales may go up. In other words, a periodic pattern exists due to the calendar (e.g., quarterly, monthly, daily).

### Additive Seasonality
​






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_879a1c01d3f34898a77be418b00d1ed6.png)




​This is the case of additive seasonality.

### Multiplicative Seasonality
​






​![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_95464d11a0d9416995f9712998dc704a.png)
​



This is the case of Multiplicative Seasonality as the seasonal fluctuation magnitude increases with time.
​

## Cyclic

The variations in a time series that operate themselves over more than one year are cyclic variations.

For starters, look at the simplest cycle.






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_acfecc29cc664081aef68df6986a2e10.png)
_[Image Source](https://towardsdatascience.com/exploring-cycles-in-data-a1746fb19735)_
​
​

In the graph below, you can see the repeating patterns at every
100,000th years.

​
​





​![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_21f3933032c941a8b7f4fea1ef2c6c94.png)

_[Image Source](https://towardsdatascience.com/exploring-cycles-in-data-a1746fb19735)_



## Stationary

We call the data stationary when:
* The mean is constant (the data is centered around the mean)
* The standard deviation is constant, and
* There is no seasonality and trend





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_15c673a81d03497496d7ee03e46be5c0.png)

In the above graph, the data fluctuates, but it’s fluctuating around its mean. The standard deviation is also constant. There are not many variations in the data. Hence, it has a constant standard deviation. There is no seasonality or trend.


![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_8b61a5266ef248f38b040e40253b5ff2.png)



In the case of the above graph, you can see the data is not centered around any mean. If any one condition is not satisfied, it is said as non-stationary.



If you observe the graphs above, the last two stationarity conditions are not always clearly observed from the graph; hence, some statistical tests help to check whether the data is stationary.

The first two conditions for stationarity are very important, and for the third one, there are techniques to make the data stationary.

## Things to Remember

* Time series can be irregularly spaced.
* External factors can contribute to the target variable and needs to be factored in
* Time series is mostly data analysis
* Understanding Seasonality and Cyclic can be a little confusing
* Be careful with missing information