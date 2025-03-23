# Time_Series_Analysis
Task:


Analyze stock price trends using Moving Average and Exponential Moving Average. 
1. Compare their effectiveness with ARIMA for forecasting. 
2. Which method provides better predictions and why?
3. Use visualizations and performance metrics to support your conclusion.

 You can create a CSV file named and populate it with the following data as per your need:  

Sample python code:

import pandas as pd

data = {
    "Date": pd.date_range(start="2024-01-01", periods=20, freq='D'),
    "Close": [100, 102, 101, 105, 107, 110, 112, 115, 118, 120, 122, 121, 123, 126, 128, 127, 130, 133, 135, 137]
}

df = pd.DataFrame(data)
df.to_csv("stock_prices.csv", index=False)

print("Dataset saved as stock_prices.csv")
