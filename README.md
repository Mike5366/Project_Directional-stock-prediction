# CSE573 Directional Stock Prediction using News and Historical

## Introduction
Predicting stock prices is a widely explored challenge within the field of machine learning, primarily because of its practical relevance. The ability to accurately forecast the future direction of a stock's price has the potential to significantly increase the financial gains of those who develop such predictive models. In this project, I investigate the Support Vector Machine(SVM) to tackle this problem. I incorporated historical stock price data and financial news articles into my analysis. My approach involves using BERT for sentiment analysis on news articles, followed by training models using SVM. Ultimately, I assess the performance through 12-fold cross-validation.

## Problem Statement
My objective is to employ features extracted from news articles and integrate the features with historical stock price data as input for a machine learning classifier. The ultimate aim is to forecast the future movement of stock prices, which is represented as a binary variable with values +1 or -1, corresponding to upward or downward directions, respectively. I will predict this direction based on the difference between the opening and closing prices of a single trading day.

## Data Set
Each following data is the combination of historical stock price data and the sentiment scores that are processed with financial news articles using BERT.
1. `Aapl_NewsPriceHistDirection.csv`: contains all individual news articles relating to Apple, sentiment, historical closing prices, and the direction label.

2. `Amzn_NewsPriceHistDirection.csv`: contains all individual news articles relating to Amazon, sentiment, historical closing prices, and the direction label.
