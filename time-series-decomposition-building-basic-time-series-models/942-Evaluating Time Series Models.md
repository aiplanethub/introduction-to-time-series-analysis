​​Before we proceed further, it’s important to understand the time series model evaluation techniques. This helps you to know how good is your model performance on an unseen dataset.
​​
## Learning Objectives

* Time Series Model Evaluation
* Different Metrics to Evaluate Time Series Models
​
## Time Series Model Evaluation​

Evaluating a time series model has certain similarities with evaluating general machine learning algorithms but also has certain intricacies that are very unique because of the time component involved in this case.

If you remember general machine learning models, in order to evaluate them, the first thing we did was split the dataset using train_test_split, which was randomly splitting the dataset into train and validation sets. In normal machine learning models, the order of the data was not very important.

​But in the case of time series, we have been observing that the order of the data is the most important thing. So, in this case, we cannot use train_test_split to split the dataset into train and validation sets. If you remember the Autoregressive model implementation in the previous lesson, the tutor had taken the first 80% of the data in sequence as the train set and the remaining 20% in sequence as the validation set. This way of splitting the dataset for model evaluation works for time series data.

## Evaluation Metrics For Time Series Data

Time series generally focus on predicting real values, called regression problems. Therefore the performance measures used for normal regression problems work for time series problems too. Some of the standard metrics are listed below:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* Root Mean Log Squared Error (RMSLE)

This course assumes that you know all the evaluation metrics used for regression analysis. So we will not dive deeper into these metrics.