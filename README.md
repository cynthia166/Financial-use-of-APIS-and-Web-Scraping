# Financial-use-of-APIS-and-Web-Scraping

I worked with the Api IEXAPI, it had a lot of  relevant and interesting information about de actions, for example the dividends of one year, low, high and close
price in the last 30 days. It is thoroughly recomendable and all you need is to sign up and obtain a Token.

## Information  consulting 

I decided to work with the 10 most requested actions in  the Structured Notes (Autocallable and Plain Vanilla Warrant) from Bancomer and Scotiabank. All of the action are from USA and the currency is in dollars.
They were the following:

-NFLX
-AAPL
-TSLA
-BMRN
-MRNA
-UBER
-AMZN-MM
-CNC
-NVDA
-FDX

For each action I consulted the information using the same API the only thing that changed was the TICKER of the requested equity. I consider that for this project the most relevant price was the Close.

## Descriptive Statistics

Finally I had a table with 10 accion considering  the last 30 working  days, and obtained the descriptive statistics that were the following:

-Mean 
-Min
-Max
-Var
-Kurtosis
-Skew
-Median
-Std

## Graphic Representation

Time Series of the action were presented and we would appreciate the trend of the action. Also the histogram so we could see the frequency of the price and a horizon of a month.

## ISIN 

I Web-scraped Wikipedia to obtain the International Securities Identification Number (ISIN) which is used to  uniquely identify the security.
The final product of this project is a merged data frame with the principal descriptive statistics and their ISIN.


