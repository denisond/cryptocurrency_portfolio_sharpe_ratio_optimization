# Cryptocurrency portfolio Sharpe ratio optimization
This repository contains a Jupyter notebook with an investment strategy for a portfolio of cryptocurrencies, although it could be generalized to other securities. 
 
The structure of the program is as follows:

  --use an api to read-in crypto price data 
  
  --defines functions to generate mean daily returns and a covariance matrix for our coins
  
  --define a function that randomly weights the proportion of each coin in our portfolio and calculates the portfolios Sharpe ratio and variance over a specified period of time.
  
  --use Monte-Carlo method to find optimal weights to maximize Sharpe ratio

