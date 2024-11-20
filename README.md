Stock Price Prediction

This project predicts stock prices for Tata Global Beverages Limited (NSE) using historical data and a machine learning approach. The project leverages a Long Short-Term Memory (LSTM) neural network to analyze and forecast stock closing prices based on time series data.

Features

Data Visualization: Displays stock price trends over time for better insights.

Machine Learning Model: Implements an LSTM neural network for time series prediction.

Scalable Framework: Easily adaptable for other stocks with similar data formats.

Dataset

The dataset contains 1,235 rows and includes the following columns:

Date: The trading date.

Open, High, Low, Last, Close: Various price points for the stock.

Total Trade Quantity: Number of shares traded.

Turnover (Lacs): Total turnover in lakh rupees.


Prerequisites

Python 3.8+

Key Libraries:

pandas, numpy: Data manipulation.

matplotlib: Data visualization.

keras: Deep learning framework for LSTM.

Installation

Clone the repository:

    git clone https://github.com/your-username/stock-price-prediction.git
    cd stock-price-prediction
    
Install dependencies:

    pip install -r requirements.txt
    
Place the dataset (NSE-Tata-Global-Beverages-Limited.csv) in the working directory.

Usage

Open the Jupyter Notebook:

    jupyter notebook stockPricePrediction.ipynb
    
Follow the steps in the notebook to:

Load and visualize the data.

Preprocess the data for training.

Train the LSTM model.

Evaluate and visualize the predictions.

Project Workflow

Data Preparation:

Reads the dataset and parses dates.

Normalizes the data for improved model performance.

Data Visualization:

Plots historical closing prices for trend analysis.

Model Training:

Uses LSTM layers for capturing temporal dependencies in the data.

Includes dropout layers to prevent overfitting.

Prediction:

Forecasts future stock prices and compares them with actual values.

Results

The LSTM model predicts the stock closing prices with reasonable accuracy. Visualization of predictions versus actual values helps in assessing performance.

Future Improvements

Enhance the model with additional features like technical indicators.

Test other machine learning models for comparison.

Automate data fetching from APIs like Alpha Vantage or Yahoo Finance.
