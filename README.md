# Electricity-Day-Ahead-Price-Forecasts

The project for forecasting Russian day-ahead wholesale electricity market price.

Attempt to use different (autoregressive, machine learning and deep learning) algorithms in order to accurately predict the future hourly values of electricity price in the 2nd price zone of Russian wholesale day-ahead electricity market.

In a broad sense this project allows to perform forecasts using any time series datasets.

The data is provided by the [administrator of the trading system (rus. АО «АТС»)](https://www.atsenergo.ru/results/rsv/index?zone=2)

The key steps of the project:
* Data downloading (web-scraping)
* Dataset preprocessing: time features engineering & hourly data format generation
* Dataset lookup & visual analysis
* Conduction of statistical tests in order to determine normality, stationarity & autocorrelation of the dataset and the forecasts residuals
* Statistical comparison of models' predictive abilities (Diebold-Mariano test)
* Prediction tests using N-fold time series cross-validation, featuring expanding & sliding window (WIP)
* Application of different error metrics in order to compare the quality of the forecasts (WIP)


