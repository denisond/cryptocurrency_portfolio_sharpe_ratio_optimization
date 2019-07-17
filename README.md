# Cryptocurrency portfolio Sharpe ratio optimization
This repository contains a Jupyter notebook with a cryptocurrency portfolio investment strategy, although it could be generalized to other securities. 
 
The structure of the program is as follows:
- use api to read-in crypto price data 
- define functions to generate mean daily returns and a covariance matrix for our coins
- define function to randomly weight proportions of each coin in our portfolio and calculate the portfolio's Sharpe ratio and variance over a specified period of time
- use Monte-Carlo method to find weighting of coins to maximize portfolio risk adjusted returns ([Sharpe ratio](https://en.wikipedia.org/wiki/Sharpe_ratio))
- plot all portfolios with stars on portfolios with highest Sharpe ratio and lowest volatility


