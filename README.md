# Stock Market Portfolio Optimization Project

## Description
This project focuses on optimizing a stock portfolio to maximize the Sharpe ratio, which measures the performance of an investment compared to a risk-free asset, after adjusting for its risk. Using historical stock data and advanced statistical methods, this project identifies the optimal allocation of assets to achieve the best risk-adjusted return.

## Features
- **Data Collection**: Retrieved historical price data for a set of assets using the Yahoo Finance API.
- **Data Preprocessing**: Cleaned and processed data to calculate daily returns, mean returns, and the covariance matrix.
- **Portfolio Simulation**: Generated and evaluated 10,000 random portfolios to calculate expected returns, volatility, and Sharpe ratios.
- **Optimization**: Identified the portfolio with the highest Sharpe ratio, resulting in an expected return of ~32.81%, volatility of ~17%, and a Sharpe ratio of ~1.93.
- **Visualization**: Created visual representations of adjusted close prices, moving averages, volume traded, daily returns distributions, and the efficient frontier.
- **Balanced Allocation**: Achieved a balanced portfolio allocation with the following characteristics:
  - HDFC Bank: 33.13%
  - Infosys: 23.04%
  - Reliance: 34.18%
  - TCS: 9.64%

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Yahoo Finance API
