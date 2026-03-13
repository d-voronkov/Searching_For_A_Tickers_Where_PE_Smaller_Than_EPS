# Custom Screener project.

## Goal:

Create a screener, that finds all the tickers on the major US stock exchanges (NASDAQ, NYSE) where EPS is higher than P/E.

## Programming language:

Python. 
Mostly, all code is written within Jupyter Notebook environment.

## APIs:
**Finnhub** (currently, the main source of ticker data), yfinance (depricated, was used to understand logic, is not fitted for large amount of searchin (since more than 7000 stocks, currently, exist on major exchanges)), **ExchangeRate API**

## Frameworks:
Pandas

## Before starting the project:
1) Get the .csv with all the possible tickers on US stock exchanges. (The easiest way - download it from NASDAQ official page)
2) Rename it to "All_Stocks.csv"
3) Put it in the ./Data folder

## Project structure:
./Scripts/Alternative_method.ipynb      - in this file lies the script, that can find data with finnhub

## All dependencies can be recreated with requirements.txt file with pip/venv           -> Will  be added later


## To do in the future:
1) Provde alternatives to the Finnhub (Polygon???), in case it becomes unavailable/unreliable
2) Mabe add options to add aditional criterias, such as P/B < 1
