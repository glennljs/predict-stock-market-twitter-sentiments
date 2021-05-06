# Predicting Stock Market Trends with Twitter Sentiment Analysis using Machine Learning Models

## Abtract

In this project, I attempt utilize sentiment analysis (emotions and sentiments) of a set of Twitter Users to predict Stock Market Data, represented by the S&P500 Index.

## Hypothesis

Through my analysis, I tested 3 different hypothesis and models,

1. Direct influence of Twitter Sentiments on Stock Market Prices.
2. Influence of Twitter Sentiments on upward/downward change of Stock Market Prices.
3. Influence of Twitter Sentiments on *Volatility* of Stock Market Prices.

## Method

A collection of Tweets were scraped using Tweepy API, using python notebook *scrape*. 

The tweets were processed to create emotional and sentiment scores for each tweet.

The data was then modeled against the S&P500 Index Closing prices on a daily basis to test each hypothesis.

## Results

From the analysis, I found that the sentiments were unable to directly predict the stock market prices. However, they were able to predict upward/downward changes of prices with a 57% accuracy and volatility with a 59% accuracy.

However, when fitted together with the existing VIX model, we were able to predict volatility of stock market prices with a 70% accuracy using our sentiment analysis model.

## Requirements

Python 3 is required for this project. The modules required for python 3 are listed in the requirements.txt file.