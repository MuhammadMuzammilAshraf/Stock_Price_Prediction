# Stock Price Prediction

This GitHub repository contains code for analyzing historical stock price data and creating a stock price prediction model using a Long Short-Term Memory (LSTM) neural network. Below is an overview of the project's structure and key components.

## Overview

Stock price prediction is a common task in finance and investment. In this project, we use historical stock price data to build an LSTM model that predicts future stock prices. The project includes data retrieval, preprocessing, model building, and evaluation.

## Project Structure

The project is organized into several main components:

1. **Data Retrieval**: Download historical stock price data from Yahoo Finance using the `yfinance` library.

2. **Data Exploration**: Explore and analyze the downloaded data by calculating statistical information, plotting historical prices, and calculating moving averages.

3. **Data Preprocessing**: Prepare the data for training the LSTM model by scaling it using Min-Max scaling and creating sequences of data for training.

4. **LSTM Model Building**: Build an LSTM neural network model for stock price prediction.

5. **Model Training**: Train the LSTM model using historical stock price data.

6. **Model Evaluation**: Evaluate the model's performance using root mean squared error (RMSE) and visualize the predictions against actual stock prices.

## Usage

- Run the Python scripts provided in each section to execute the corresponding tasks.


Please feel free to contribute to this project or use it as a reference for your own stock price prediction tasks.

