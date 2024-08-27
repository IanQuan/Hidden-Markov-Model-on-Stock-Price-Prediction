# Stock Price Prediction Using Hidden Markov Model (HMM)

## Overview
Predicting stock market trends remains a complex challenge due to its inherent volatility and the potential for substantial financial returns. In this project, we used the Hidden Markov Model (HMM) to predict stock prices by representing market dynamics through hidden states. This project utilizes Hidden Markov Models (HMMs) to predict stock prices of major companies such as Amazon (AMZN), Nvidia (NVDA), and Apple (AAPL). The study's analysis concludes that the prediction results are elatively accurate, particularly in forecasting the trend of the company's stock fluctuations. However, the variance is significant, indicating a need to incorporate more ontrol variables and combine different prediction methods to achieve more accurate stock prediction results.


## Key Features

- **Data Preprocessing**: Includes extracting OHLC (Open, High, Low, Close) prices, calculating log returns, and standardizing the data for robust model performance.
- **HMM Training**: Trains a Gaussian HMM for each stock with optimized hidden states, using a sliding window approach to adapt to recent market conditions.
- **Prediction and Evaluation**: Predicts future stock prices and evaluates model performance using Mean Absolute Percentage Error (MAPE).
- **Visualization**: Provides plots comparing predicted and actual stock prices, highlighting the model’s accuracy and limitations.
