# Crytocurrency Data Science Project

![](https://i.imgur.com/vq7g2xQ.png)

## Contributors:
* Andy Vu Hoang
* Zachary Valery

## Abstract
In this project, we sought to analyze cryptocurrencies in the context of a data science project. The first step was gathering data on what we arbitrarily identified as the top 25 cryptocurrencies.   We then conducted data analysis on those cryptocurrency data sets by creating graphics which included all of the currencies we were lookin at and a correlation analysis.  We also conducted a time series analysis on the data.  Then we implimented a model in accordance with the the analysis which was condiucted

## Technologies
* Git: for team collaboration
* Python
   * Numpy: creating and manipulating multi-dimensional arrays and matrices
   * Pandas: data gathering, manipulation, and analysis
   * Matplotlib: data visualization
   * Scikit-learn: machine learning
   * Pickle for data gathering

## Data Gathering
To get data for bitcoin prices in particular, we used Kraken, Coinbase, Itbit, Bitstamp, and poloniex's API data and merged it into one data frame to get really complete data. Then for the other 24 cryptocurrencies, we used only poloniex's data because it was sufficient.  We then did some cleaning to the data to get it into a form which we could put it into one big graph.

## Data Analysis
Our main analysis of the data for this project was an extensive correlation analysis of the various cryptocurrencies used.  Not only did we analyze the correlation between the currencies but we analyzed the correlation between the average daily price of each cryptocurrency with the average price of the previous day in order to see if the price of one currency the day before has and influence on the price of another one the next day.  We found that they were not significantly correlated.  We also identified that Bitcoin and Litecoin were two of the most correlated cryptocurrencies and three currencies which were tightly correlated are Siacoin, Digibite, and 0x.

## Monte Carlo Simulation
In order to predict the future price trends for specific cryptocurrencies and understand the cryptocurrency market better, we decided to use a common tool for prediction of stock prices and quantifying risk: Monte Carlo simulations. These simulations assume that daily returns are a random variable which is normal distributed and centered around a mean of 0. From running them, the volatility of cryptocurrency can be made obviously clear, as the range for which the prices can be within just 30 days is significantly large.
   
