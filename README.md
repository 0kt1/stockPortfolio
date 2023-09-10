
# Stock Market App

This is a stock market app that allows users to search for stocks and view their current price, change, and chart. The app also displays the latest prices of the Dow Jones Industrial Average (DJIA), S&P 500 (GSPC), and Nasdaq Composite (IXIC).

## Getting Started

To run the app, you will need to have Node.js and npm installed on your computer. Once you have these installed, you can clone the repository and install the dependencies by running the following commands:



## Features

The app has the following features:

* Search for stocks by symbol
* View the current price, change, and chart of a stock
* View the latest prices of the DJIA, S&P 500, and Nasdaq Composite
* Update stock prices every 10 seconds

## Code Explanation

The app is built using the following technologies:

* HTML
* CSS
* JavaScript
* jQuery
* TradingView

The HTML code defines the structure of the app. The CSS code styles the app. The JavaScript code handles the interactivity of the app. The jQuery library is used to make AJAX requests. The TradingView library is used to display the stock charts.

The main JavaScript file is `main.js`. This file contains the following functions:

* `getStockInfo()`: This function gets the current price, change, and chart of a stock.
* `getIndices()`: This function gets the latest prices of the DJIA, S&P 500, and Nasdaq Composite.
* `getStockChart()`: This function displays the stock chart.

The `getStockInfo()` function uses the IEX Cloud API to get the current price, change, and chart of a stock. The `getIndices()` function uses the Alpha Vantage API to get the latest prices of the DJIA, S&P 500, and Nasdaq Composite. The `getStockChart()` function uses the TradingView library to display the stock chart.



