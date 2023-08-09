# Repository Information
Language: Python
Creator: Daniel Grammer
Date Created: Jan, 2023
Last Edit: 08/07/2023

# Code Overview
The scraper in this repository currently has the ability to scrape historical price data (Open, High, Low, Close, Adj Close, Volume) for around 7,500 stocks listed on the NYSE and the NASDAQ Stock Exchange. It also has the ability to scrape investor sentiment data (bearish, bullish, and neutral), inflation % (USA, monthly), historical data for the DOW, NASDAQ, and S&P500 index funds, and whether or not a company released earnings on a given day (this capability is prone to error, due to the fact that companies can release earnings on days/times that the market is not open. The earnings reports could be off by 1-2 days). The scraper compiles all of this data for each stock into a JSON format, and then saves it on your computer. Each function is described in the code with comments.
