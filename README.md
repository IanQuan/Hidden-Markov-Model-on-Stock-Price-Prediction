# Stock Price Prediction Using Hidden Markov Model (HMM)

## Overview
This project utilizes Hidden Markov Models (HMMs) to predict stock prices of major companies such as Amazon (AMZN), Nvidia (NVDA), and Apple (AAPL). By modeling the underlying market conditions as hidden states, this project aims to provide accurate predictions of future stock prices, aiding investors in making informed decisions.

## Key Features

- **Data Preprocessing**: Includes extracting OHLC (Open, High, Low, Close) prices, calculating log returns, and standardizing the data for robust model performance.
- **HMM Training**: Trains a Gaussian HMM for each stock with optimized hidden states, using a sliding window approach to adapt to recent market conditions.
- **Prediction and Evaluation**: Predicts future stock prices and evaluates model performance using Mean Absolute Percentage Error (MAPE).
- **Visualization**: Provides plots comparing predicted and actual stock prices, highlighting the model’s accuracy and limitations.
