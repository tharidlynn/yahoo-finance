# Scraping Yahoo finance
A python script which scrapes the [yahoo finance](https://finance.yahoo.com) and saves to PostgreSQL every 15 seconds.

The following data will be scraped:
* world-indices
* commodities
* currencies
* cryptocurrencies

## Getting started
1. `source .env` 
2. `python create_db.py`
3. `python main.py`