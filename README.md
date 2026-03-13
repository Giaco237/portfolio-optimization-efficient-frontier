# Portfolio Optimization – Efficient Frontier
Portfolio optimization using Modern Portfolio Theory and Efficient Frontier in Python.
## Objective
This project applies Modern Portfolio Theory to build and analyze an optimal ETF portfolio using historical market data.

## Assets Used
- SPY
- QQQ
- GLD
- AGG
- EFA

## Methodology
The project:
- downloads historical prices from Yahoo Finance,
- computes daily and annualized returns,
- estimates the covariance matrix,
- simulates 10,000 random portfolios,
- identifies the maximum Sharpe ratio portfolio,
- identifies the minimum volatility portfolio,
- visualizes the efficient frontier.

## Key Results
- Maximum Sharpe Portfolio:
  - Annual Return: 19.94%
  - Annual Volatility: 15.10%
  - Sharpe Ratio: 1.19

- Minimum Volatility Portfolio:
  - Annual Return: 6.25%
  - Annual Volatility: 7.30%
  - Sharpe Ratio: 0.58

## Tools Used
- Python
- NumPy
- Pandas
- Matplotlib
- yfinance

## Conclusion
This project demonstrates how portfolio allocation can be optimized by balancing expected return and risk through Efficient Frontier analysis.
