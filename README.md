# Bollinger Band Trading Algorithm

## Web Scraping

To test the algorithm on the daily timeframe, gold (XAU-USD) price and volume data are first web-scraped from Yahoo! Finance. The Selenium library is used to web scrape the data, followed by compiling it into a data frame with the Pandas library. The data is then saved in CSV format.

## Bollinger Bands

Settings for Bollinger Bands are based on the 50-day MA at 2 standard deviations. The data for this is then added to the data frame for use in the algorithm.

## Trading Algorithm

TBD
