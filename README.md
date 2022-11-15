# ARIMA MODEL 

The Autoregressive integrated moving average (ARIMA) model uses time-series data and statistical analysis to interpret the data and make future predictions. The model aims to explain data by using time series data on its past values and uses linear regression to make predictions.

# Model Description
The components are included in the model as a parameter. The parameters are assigned specific integer values that indicate the type of ARIMA model. A common notation for the ARMA parameters is shown and explained below:
MA (p, d, q)
*	The parameter p is the number of autoregressive terms or the number of “lag observations.” It is also called the “lag order” and it determines the outcome of the model by providing lagged data points.
*	The parameter d is known as the degree of differencing. it indicates the number of times the lagged indicators have been subtracted to make the data stationary.
*	The parameter q is the number of forecast errors in the model and is also referred to as the size of the moving average window.
Once the parameters (p, d, q) have been defined, the ARIMA model aims to estimate the coefficients α and θ, which is the result of using previous data points to forecast values.

# Advantages of the ARIMA Model

In business and finance, the ARIMA model can be used to forecast future quantities (or even prices) based on historical data. Therefore, for the model to be reliable, the data must be reliable and must show a relatively long time span over which it’s been collected. Some of the applications of the ARIMA model in business are listed below:
*	Forecasting stock prices based on historical data.(This is briefly discussed in the project/code).
*	Forecasting no of vehicles passing through that road.
*	Forecasting the quantity of a good needed for the next time period based on historical data.
*	Forecasting sales and interpreting seasonal changes in sales
*	Estimating the impact of marketing events, new product launches, and so on.

# Limitations of the ARIMA Model

* Although ARIMA models can be highly accurate and reliable under the appropriate conditions and data availability, one of the key limitations of the model is that the parameters (p, d, q) need to be manually defined(briefly discussed in the html/code file).
* Therefore, finding the most accurate fit can be a long trial-and-error process.
* Similarly, the model depends highly on the reliability of historical data and the differencing of the data. 
* It is important to ensure that data was collected accurately and over a long period of time so that the model provides accurate results and forecasts.



