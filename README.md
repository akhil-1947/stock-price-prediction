# Stock-price-prediction

## Introduction
Predicting stock market prices has been a topic of interest among both analysts and researchers for a long time. Stock prices are hard to predict because of their high volatile nature which depends on diverse political and economic factors, change of leadership, investor sentiment, and many other factors. Predicting stock prices based on either historical data or textual information alone has proven to be insufficient.

## Why Sentiment Analysis
Market sentiment is a qualitative measure of the attitude and mood of investors to financial markets in general, and specific sectors or assets in particular. Positive and negative sentiment drive price action, and also create trading and investment opportunities for active traders and long-term investors.
Existing studies in sentiment analysis have found that there is a strong correlation between the movement of stock prices and the publication of news articles. Several sentiment analysis studies have been attempted at various levels using algorithms such as Support Vector Machines, Naive Bayes Regression, and deep learning. The accuracy of deep learning algorithms depends upon the amount of training data provided.

## Score Metric
I am using RMSE to compare the performance of various models.

## Data Collection
I am using the Nifty 50 Index for the stock price data and Stock News from a popular twitter handle of NDTV Profit.

## Modelling
As we know that time series model needs to be trained every time in production with the new data points for accurate prediction so we will be using only those models which have low time complexity in training i.e. which trains faster with new data. <break>
<ol>
  <li> ARIMA
   <li> SARIMAX
     <li> Facebook Prophet
       <li> LSTM taking news polarity into account
</ol>
  

## Papers Referred
  <ol>
<li>Stock Price Prediction Using News Sentiment Analysis: http://davidanastasiu.net/pdf/papers/2019-MohanMSVA-BDS-stock.pdf <break>
<li>Sentiment Analysis of Twitter Data for Predicting Stock Market Movements: http://arxiv.org/pdf/1610.09225v1.pdf
  </ol>
