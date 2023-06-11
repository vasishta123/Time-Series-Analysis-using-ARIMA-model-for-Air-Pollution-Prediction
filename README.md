# Project Summary

This project focuses on analyzing and forecasting air quality data in Hyderabad, India. The project utilizes time series analysis techniques to understand the patterns and trends in the air quality data and make predictions for future values.

## Dataset

The project uses the "hyd_No2_pollution_data_completeValues.csv" dataset, which contains the air quality data for Hyderabad. The dataset is read using the Pandas library and converted into a time series by setting the 'Date' column as the index.

## Exploratory Data Analysis

The project begins with exploratory data analysis, including visualizing the time series data and determining rolling statistics such as the rolling mean and standard deviation. The plots help understand the overall trend and identify any seasonality or irregularities in the data.

## Stationarity Test

To perform time series analysis, it is important to check if the data is stationary. The project uses the Dickey-Fuller test to determine the stationarity of the data. The test results provide information about the test statistic, p-value, and critical values at different confidence levels.

## Data Transformation

To achieve stationarity, the project applies data transformations such as logarithmic scaling and differencing. These transformations help stabilize the mean and reduce the trend and seasonality in the data. Moving averages and exponential decay weighted averages are also used to smooth the data.

## Seasonal Decomposition

The project applies seasonal decomposition to decompose the time series data into trend, seasonality, and residual components. This helps understand the individual components and their contributions to the overall pattern in the data.

## Autocorrelation and Partial Autocorrelation

Autocorrelation and partial autocorrelation functions are plotted to determine the order of the autoregressive integrated moving average (ARIMA) model. These plots provide insights into the correlation between the time series and its lagged values.

## ARIMA Modeling

The project builds ARIMA models based on the identified order. ARIMA models are widely used for time series forecasting. The project fits ARIMA models with different orders and evaluates their performance using the residual sum of squares (RSS).

## Forecasting

The final step of the project involves making predictions for future values of the time series using the trained ARIMA model. The predicted values are then plotted against the actual values to visualize the forecasted trend.

Please note that the code provided in this README is a summary of the project and may not include all the necessary details and steps. Refer to the actual code files for a complete understanding of the implementation.

