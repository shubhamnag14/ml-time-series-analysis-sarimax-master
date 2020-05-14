![Image](https://c1.sfdcstatic.com/content/dam/blogs/ca/Blog%20Posts/sales-forecasting-header.jpg)

# ml-time-series-analysis-sarimax-master

In this experiment, we use time series analysis technique to decompose our data into 3 components like the below:

    1-Trend (T)
    2-Seasonility (S)
    3-Residual (R)

Once we need to get a statinory dataset before performing Time Series Analysis (TSA) flawlessly beacuse it would be easy making a predicition over a stationary dataset since it would already satisfy the preoperties of Normal Distribution in terms of mean and variance, roughly. So, we need to delve into the raw dataset by applying some EDA techniques to expose valuable insight of data related to trend, and seasonility if it is possible to observe in EDA. After we complete data analyis stage, we need to pick best available techniques
 (e.g ARIMA, SARIMAX) to perform on the dataset according to our knowledge we would get in EDA.
 
 In EDA stage, we will be applying a bunch of techniques such as, boxploting, rolling statictics (mean, std) by time based features (year, month, day, weekday and quarter) to find out 2 components (trend, seasonility) out of 3 time series components over specific plots, rougly. Those plots will give reasonable feedback for TSA before starting it.

In TSA stage, we will build different models
