# Electricity-Day-Ahead-Price-Forecasts

Russian day-ahead wholesale electricity market price forecasts.

Attempt to use different (autoregressive, machine learning and deep learning) algorithms in order to accurately predict the future hourly values of electricity price in the 2nd price zone of Russian wholesale day-ahead electricity market.

The data is provided by the [administrator of the trading system (rus. АО «АТС»)](https://www.atsenergo.ru/results/rsv/index?zone=2)

The key steps of the project:
* Data downloading (web-scraping)
* Dataset preprocessing
* Time features engineering
* Dataset lookup & visual analysis
* Statistical tests to determine normality, stationarity, autocorrelation of residuals and to compare predictive abilities of the models
* Prediction tests using N-fold time series cross-validation (expanding & sliding window) (WIP)
* Application of different error metrics in order to compare the quality of the forecasts (WIP)


