# Custom Screener project.

#### Goal:
    Create a screener, that finds all the tickers on the major US stock exchanges (NASDAQ, NYSE) where EPS is higher than P/E.

#### Programming language:
    Python. Mostly, all code is written within Jupyter Notebook environment.

#### APIs:
    Finnhub (currently, the main source of ticker data), yfinance (depricated, was used to understand logic, is not fitted for large amount of searchin (since more than 7000 stocks, currently, exist on major exchanges))

#### Frameworks:
    Pandas

#### Project structure:
    ./Scripts/Alternative_method.ipynb      - in this file lies the script, that can find data with finnhub

## All dependencies can be recreated with requirements.txt file with pip/venv


#### To do in the future:
    1) Provde alternatives to the Finnhub (Polygon???), in case it becomes unavailable/unreliable
    2) Mabe add options to add aditional criterias, such as P/B < 1