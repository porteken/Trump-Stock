# Trump-Stock
Rpubs Notebook: https://rpubs.com/porteken/Trump-Stock

This project attempts to predict the performance of SPY (SPDR S&P 500 Trust ETF) based on Trump's tweets.  I used Python to process trump tweet's into a cosine similarity score using Spacy and Bert transformer, and used R for the ARIMA time series model.   Below are some assumptions and parameters I had for this project.
1. If there was multiple tweets on one day, then I chose the tweet that had the most favorites.
2. Gaps in the model (weekends for stock price and days with no tweet for tweet score), were filled with the most recent model
3. The model used data from 1/9/18 to 4/30/20.
4. The model had a 95/5 train/test split to allow the model to train on the stock market drop in early 2020.

