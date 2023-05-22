# Arima
Time Series Forecasting

With the ARIMA procedure you can build an autoregressive integrated moving average (ARIMA) model that is ideal for generating correctly fitted time series models. ARIMA models provide more sophisticated methods for modeling the trend and seasonal components than exponential smoothing models and have the added advantage of being able to include predictor variables in the model.

In the example of a catalog retail company that wants to develop a forecasting model, we have seen that the company has collected monthly menswear sales data along with several series that could be used to explain some of the variation in sales. Possible predictors include the number of catalogs mailed and the number of catalog pages, the number of phone lines open for ordering, the capital spent on print advertising, as well as the number of customer service representatives.

Are any of these predictors useful for forecasting, and is a model with predictors actually better than one without? With the ARIMA procedure, we can create forecasting models with predictors and see if there is any significant difference in their predictive ability compared to the exponential smoothing model without predictors.

With the ARIMA method, you can fit the model by specifying autoregression, differencing and moving average orders, as well as the corresponding seasonal values for these components. Manually determining the best values for these components can take a long time and a large number of trials and errors, so in this example we will let the expert modeler choose an ARIMA model for us.
