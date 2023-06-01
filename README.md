# Time Series Forecasting with LSTMs

This project demonstrates time series forecasting using Long Short-Term Memory (LSTM) neural networks. LSTM is a type of recurrent neural network (RNN) that is specifically designed for processing sequential data, making it an ideal choice for analyzing and predicting time series data.

# Overview
Time series forecasting plays a crucial role in various domains, including finance, weather prediction, sales forecasting, and more. LSTM models excel at capturing long-term dependencies in sequential data, which is essential for accurate forecasting. This project provides a practical implementation of LSTM-based time series forecasting using PyTorch.

# Key Features

* Data retrieval: The project utilizes the Yahoo Finance API to download historical stock price data.
* Data preparation: The "Adj Close" prices are extracted and preprocessed to create input-output pairs using a sliding window technique.
* LSTM model: The LSTM model is defined using PyTorch's nn.LSTM module, with customizable hyperparameters such as the number of LSTM layers and hidden size.
* Training and validation: The model is trained using the mean squared error (MSE) loss function and the AdamW optimizer. Early stopping based on validation loss is implemented to prevent overfitting.
* Evaluation: The trained model is evaluated on a separate validation set to assess its performance.

# Source Code
Link to Notebook on GitHub: https://github.com/danplotkin/LSTM_Time_Series/blob/main/TimeSeriesLSTM.ipynb
To run in Google Colab, refer to the link below:

