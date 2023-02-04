# Stock Price Forecasting
This repository contains the code for stock price forecasting using the ARIMA model. The model was tested on three stocks: EXX5, IQQE, and IUS4. Data for these stocks was collected from [Yahoo Finance](https://finance.yahoo.com/) for the time window of May 2021 to May 2022.

## Steps in the code

### Importing Required Libraries 
The code starts by importing the required libraries such as pandas, numpy, matplotlib, and statsmodels.

### Data Collection 
The data for the stocks is collected from Yahoo Finance for the time window of May 2021 to May 2022. The data is loaded into a pandas dataframe.

### Data Preprocessing 
The data is preprocessed by checking for missing values, transforming the data into log-returns, and making the time series stationary.

### Model Selection 
The code uses the statsmodels library to fit the ARIMA model on the stationary time series data. The parameters of the ARIMA model are selected using the **`auto_arima`** function.

### Model Fitting and Forecasting 
The selected ARIMA model is fit on the data and used to make forecasts for future stock prices. The code also calculates the mean absolute error (MAE) to evaluate the performance of the model.

### Visualizing Results 
Finally, the code plots the original stock prices and the forecasted stock prices for comparison.

## Conclusion
This repository provides a basic implementation of forecasting stock prices using the ARIMA model. For further development and experimentation, the code can be used as a starting point.
