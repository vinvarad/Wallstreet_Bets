# Stock Prediction using subreddit r/Wallstreetbet.
- Fetch top 600 "Hot" threads from subreddit r/wallstreetbets via Reddit API.
- Identify only NASDAQ ticker symbols from top threads (ignoring all other details)
- Perform Sentiment Analysis for the final ticker symbols using VADER & IBM Watson.
- Aggregate the sentiment score for each ticker symbol and pull closing price using Quandl & Alpaca API's.
- Train and run Tensorflow Deep learning analysis to compare sentiment scores with next day performance and predictions for next day's trading.

