# Stock Price Prediction with ARIMA: Insights from Intel Corporation

This repository contains the analysis and code for predicting stock prices using the ARIMA (AutoRegressive Integrated Moving Average) model, focusing on Intel Corporation's historical stock data.

## Objective

The primary objective of this study is to investigate the application of the ARIMA model in forecasting the stock prices of Intel Corporation. By utilizing actual historical stock data, this work aims to showcase the predictive power of the ARIMA model and its relevance in financial analysis and stock market forecasting.

## Methodology

The analysis follows a structured approach starting from data pre-processing, and visualization, to implementing the ARIMA model.

- **Data Collection**: Historical daily stock prices of Intel Corporation were sourced from Yahoo! Finance, covering the period from January 4, 2010, to November 29, 2021.
- **Pre-processing**: The dataset was assessed for missing values and prepared for analysis.
- **Stationarity Testing**: The Augmented Dickey-Fuller (ADF) test was applied to ensure the stationarity of the time series data, which is a prerequisite for ARIMA modeling.
- **Model Implementation**: The ARIMA model was carefully tuned to the optimal parameters and applied to forecast stock prices.
- **Evaluation**: The model's performance was evaluated using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## Key Findings

- The ARIMA model demonstrated excellent predictive capability on the test dataset, with a tight alignment between the forecasted and actual stock prices.
- The evaluation metrics consistently showed low values, indicating the model's effectiveness in predicting stock price movements.

## Future Work

Further research might explore the integration of more advanced machine learning techniques, like Prophet or LSTM networks, to enhance the model's forecasting ability.
