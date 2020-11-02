# Trump-Stock
Rpubs Notebook: https://rpubs.com/porteken/Trump-Stock

ThThe goal of this project was to see if Trump tweet's have an impact on the SPY using time series modeling and NLP with data from the beginning of 2018 to August 2020. I used Python to process trump tweet's into a cosine similarity score using Spacy and Bert transformer, and used R for the ARIMA time series model. Below are some assumptions and parameters I had for this project. 
1. If there was multiple tweets on one day, then I chose the tweet that had the most favorites. 
2. Gaps in the model (weekends for stock price and days with no tweet for tweet score), were filled with the most recent model 
3. The model used data from 10/1/18 to 8/27/20. 
4. The model had a 95/5 train/test split to allow the model to train on the stock market drop in early 2020.

