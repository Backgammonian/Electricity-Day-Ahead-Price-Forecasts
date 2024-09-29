# Electricity-Day-Ahead-Price-Forecasts

The comparative framework for forecasting day-ahead wholesale electricity market price (using Russian market as an example).

Attempt to use different (regression, machine learning, deep learning, etc.) algorithms in order to accurately predict the future hourly values of electricity price in the 2nd price zone of Russian wholesale day-ahead electricity market.

In a broader sense this project allows to perform forecasts for any time series datasets.

The hourly electricity price data is provided by the [administrator of the trading system (rus. АО «АТС»)](https://www.atsenergo.ru/results/rsv/index?zone=2)

The key steps of the project:
* Data downloading (web-scraping)
* Dataset preprocessing: time features engineering & hourly data format generation
* Dataset lookup & visual analysis
* Conduction of statistical tests in order to determine normality, stationarity & autocorrelation of the dataset and the forecasts residuals
* Statistical comparison of models' predictive abilities (Diebold-Mariano test)
* Prediction tests using different types of time series cross-validation (expanding & sliding window approaches, etc.)
* Application of different error metrics in order to compare the forecasts quality


