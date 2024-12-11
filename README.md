# Stock Market Analysis with Python

This project provides tools to analyze and visualize stock market data using Python. It focuses on price trends, Z-Score normalization, and Delta Volume analysis to assist in understanding market behaviors and patterns. 

## Features
- **Data Retrieval**: Fetches historical stock data (e.g., MSFT, AAPL, GOOG) using the `yfinance` library for a customizable period.
- **Price Charting**: Includes functions to visualize stock closing prices with overlays for Simple Moving Averages (SMA).
- ![image](https://github.com/user-attachments/assets/ed038829-1d4c-4e53-9f31-d1b0b0f4f0aa)
- 
- **Z-Score Normalization**: Calculates Z-scores for stock prices to identify deviations from the mean, revealing potential overbought or oversold conditions.
![image](https://github.com/user-attachments/assets/77b1fa2f-caa0-4d16-8860-ad400227c99f)
![image](https://github.com/user-attachments/assets/f085a51a-6c70-4d6c-9ef6-2ac3fdc68947)

- **Delta Volume Analysis**: Tracks cumulative volume changes (bullish or bearish) to assess market sentiment.
- ![image](https://github.com/user-attachments/assets/9ed683a1-ca8b-40a8-8adf-422e84fef8b8)


## Functionalities
1. **Draw Price Charts**:
   - Plots closing price trends for selected stocks over a specified timeframe.
   - Adds a 15-day Simple Moving Average (SMA) line for better trend identification.

2. **Z-Score Normalization**:
   - Normalizes closing prices to Z-scores for trend and deviation analysis.
   - Visualizes Z-scores over time and presents histograms of the latest close Z-scores.

3. **Delta Volume Analysis**:
   - Calculates and visualizes cumulative volume changes (bullish or bearish).
   - Highlights significant shifts in volume pressure for predictive insights.

## Applications
- Analyzing stock price trends with SMA overlays.
- Identifying overbought or oversold conditions using Z-scores.
- Evaluating volume dynamics to assess market momentum and sentiment.
- Visualizing key metrics for data-driven trading decisions.

## Requirements
- Python (>= 3.7)
- Libraries: `yfinance`, `pandas`, `matplotlib`

## Usage
1. Clone the repository and install the required libraries.
2. Use the provided scripts to:
   - Fetch financial data for chosen stocks.
   - Generate price trend visualizations with SMA overlays.
   - Perform Z-score and Delta Volume analyses.

**This project is intended solely for educational purposes and should not be considered financial advice.**
