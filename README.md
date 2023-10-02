# Stock Price Analysis Dashboard

This is a web-based dashboard for analyzing stock price data using Dash, Plotly, and machine learning models. The dashboard provides insights into stock price trends and allows users to visualize and compare stock data.

## Features

- Displays NSE-TATAGLOBAL stock data including actual closing prices and LSTM-predicted closing prices.
- Provides interactive graphs for comparing high and low prices of various stocks (Tesla, Apple, Facebook, Microsoft).
- Offers visualizations of market volume for selected stocks over time.

## Technologies Used

- Dash: A Python framework for building interactive web applications.
- Plotly: A data visualization library for creating interactive and shareable plots.
- Keras: A deep learning framework used to load and run the LSTM model for stock price prediction.
- Scikit-Learn: A machine learning library for data preprocessing (MinMax scaling).
- Pandas: A data manipulation library for handling and analyzing data.
- Numpy: A library for numerical computations in Python.

## Data Sources

- NSE-TATAGLOBAL stock data is loaded from a CSV file (`NSE-TATA.csv`).
- High, low, and volume data for Tesla, Apple, Facebook, and Microsoft are loaded from a CSV file (`stock_data.csv`).

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/stock-price-analysis-dashboard.git
2. Install the required Python packages:

   ```
    pip install -r requirements.txt
3. Run the application:

    ```
      python stock_app.py

4. Access the dashboard by opening a web browser and navigating to ` http://localhost:8050. `

# Usage
- `NSE-TATAGLOBAL Stock Data:` View actual closing prices and LSTM-predicted closing prices for NSE-TATAGLOBAL stock.

- `Facebook Stock Data:` Use the dropdown menu to select stocks (Tesla, Apple, Facebook, Microsoft) and visualize high and low prices as well as market volume over time

# Output 
![output](https://github.com/Spraveen8-chary/stock-price-prediction/assets/108536707/c4b4a28a-286d-419d-ad54-42339f3b4edf)


