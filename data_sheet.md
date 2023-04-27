# Datasheet 



## Motivation

The S&P 500 is the world's most famous financial benchmark. This stock market index tracks the performance of the 500 largest companies traded on the stock exchanges in the United States. The S&P 500 is widely regarded as an indicator of the overall health of the US stock market and is often used as a benchmark for stock investments.

 
## Composition

The dataset contains historical stock price data for the companies that make up the S&P 500 index, spanning from 2018 to 2023. The instances in the dataset are:
- 'open' - Opening price
- 'high' - Highest price reached during the day
- 'low' - Lowest price reached during the day
- 'close' - Closing price
- 'adjclose' - Closing price adjusted for actions such as dividends and stock splits, which affect the price of a stock over time.
- 'volume' - Quantity of stocks traded during the day
- 'ticker' - Unique code that identifies the stock.

## Collection process

The data was obtained through the Yahoo Finance API using the open-source library yahoo_fin. (https://algotrading101.com/learn/yahoo-finance-api-guide/)
The data is related to the period from 01/01/2018 to 10/04/2023.

 
## Uses

Analysis of the historical stock prices of the companies that make up the S&P 500. Use the dataset to build predictive models for stock prices. Analyze which stocks had the highest gains during the period.

## Distribution

The data is public and can be obtained from various sources.  

## Maintenance

The Yahoo Finance API provides the data, but it's currently no longer a fully official API, which means that sometimes it may not provide all the desired information.

