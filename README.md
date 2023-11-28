# Sales-Prediction-using-SARIMA-LSTM-Hybrid_Model

## Overview

This repository presents the implementation of a hybrid SARIMA-LSTM model designed for accurate sales prediction. The model combines time series analysis and deep learning techniques to enhance forecasting precision, leveraging the strengths of both SARIMA and LSTM models. This approach allows for more robust predictions by capturing both temporal patterns and complex dependencies within the sales data.

## Importance of Sales Analysis

Sales analysis is a crucial aspect of any industry as it facilitates the recording and prediction of sales in the near future. Understanding sales trends and patterns is essential for informed decision-making and effective business planning.

## Dataset

The project utilizes a public dataset containing four years of sales history from a retail store. The focus is on forecasting furniture sales, which exhibits seasonality in its trend.

## Forecasting Models Applied

1. **SARIMA Model:**
   - A conventional Seasonal Autoregressive Integrated Moving Average (SARIMA) model is initially applied.

2. **LSTM Model:**
   - A Long Short-Term Memory (LSTM), a type of Recurrent Neural Network (RNN), is employed for its ability to capture long-term dependencies in sequential data.

3. **SARIMA-LSTM Hybrid Model:**
   - The data is decomposed into seasonal and non-seasonal components, and a SARIMA-LSTM hybrid model is applied to predict future sales.

## Performance Evaluation

The performance of each model is evaluated using two common metrics:
   - Root Mean Squared Error (RMSE)
   - Mean Absolute Error (MAE)

     
## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/Shayankr/Sales-Prediction-using-SARIMA-LSTM-Hybrid_Model.git
   ```
2. Navigate to the project directory:
   
   ```bash
   cd Sales-Prediction-using-SARIMA-LSTM-Hybrid_Model
   ```
3. Run the forecasting models and analyze the results using the provided source code.


**Feel free to explore and contribute to this project!


