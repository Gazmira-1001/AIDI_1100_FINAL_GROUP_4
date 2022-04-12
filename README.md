# AIDI_1100_FINAL_GROUP_4


## Group Members:

Brahushi Gazmira | Patel Khaleel | Jivnani Ravina | Parmar Niravkumar | Issac Dennis

## Course code: 
AIDI_1100 - Introduction to Artificial Intelligence 

## Submission Date:
12-04-2022


## Introduction

This project consists of 4 parts:

### `SECTION A. Scan/Parse/Scrape:` 
its implemented in the function get_news_data, it contains the instructions: 
1. the url is composed 
2. the get request is executed for the news url and 
3. parsing the request by using BeautifulSoap and the parser html5lib.


### `SECTION B. Track/Store/Search:` 
1. is implemented in the function get_news_data by localising the div class which contains the news information for the specified period of time. After accessing the information, the function stores it on the excel file 
2. is implemented the function get_stock_data, which is called inside get_news_data and has an array parameter from which are extracted all the tickers with the pattern NASDAQ:


### `SECTION C. Retrieve Data:` 
its consists of 
1. selecting randomly three stock symbols and 
2. get_ticker_info function which prints stock data(volume, price)


### `SECTION D. Visualize:`
Visualize consists of functions: 
1. plot_time_series, which plots dinamically 2 time series using plotly, one for Volume and another for Closing Price, the results on the graphs appear for different periode of time(monthly, for 6 months,Year to date (YTD) refers to the period of time beginning the first day of the current calendar year or fiscal year up to the current date, yearly and all.

### `SECTION E. Extra/Optional part:`

1. Candlestick function, which plots candlestick chart for each ticker in data for the same period as the 1st function. All charts have the feature stepmode="backward", which does the charts user-interactive to go back and forward

2. Recommend if Any of the stocks is worth purchasing or not based on slop of the close prices of the stock of last 6 month

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
