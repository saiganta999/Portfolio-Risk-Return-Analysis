# Portfolio-Risk-Return-Analysis
Portfolio risk and return analysis of NSE-listed stocks using Python, including returns

A quantitative finance project analyzing the historical risk and return
characteristics of selected NSE-listed stocks and constructing diversified
multi-asset portfolios.

*Stocks Analyzed

- Reliance Industries
- TCS
- HDFC Bank
- ITC
- Sun Pharmaceutical Industries

*Project Objectives
- Analyze historical stock-price performance
- Calculate daily and annualized returns
- Measure annualized volatility
- Analyze covariance and correlation between assets
- Construct an equal-weight portfolio
- Calculate portfolio expected return and risk
- Evaluate risk-adjusted performance using the Sharpe Ratio
- Simulate 5,000 different portfolio allocations
- Identify maximum-Sharpe and minimum-volatility portfolios
- Compare historical portfolio performance

*Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- yfinance
- Google Colab

*Methodology : Historical adjusted market prices were collected for five NSE-listed
companies from different sectors.

Daily returns were calculated using:

R(t) = P(t) / P(t-1) - 1

Annualized return was estimated from average daily returns.

Annualized volatility was calculated using the standard deviation of daily
returns.

Covariance and correlation matrices were used to analyze relationships
between assets and diversification.

Portfolio return was calculated using weighted asset returns.

Portfolio risk was calculated using the covariance matrix.

Risk-adjusted performance was evaluated using the Sharpe Ratio.

Finally, 5,000 random portfolio allocations were simulated to compare
risk-return combinations and identify portfolios with maximum Sharpe Ratio
and minimum volatility.

The project includes :

- Normalized stock-price comparison
- Risk-return comparison
- Correlation matrix
- Equal-weight portfolio
- Maximum-Sharpe portfolio
- Minimum-volatility portfolio
- Portfolio simulation
- Historical portfolio growth comparison
