## Feature Selection and ML to predict stock price movement

To anticipate the stock market is impossible, by all means today. Stock market (or perhaps any other market where irrationality supercedes rationalitity) is the most whimsical, unpredictable field. Even the most advanced machine learning or deep learning techniques have failed to bring consistent sum to gold miners.

However, in a vain attempt to build a reliable, or at least a surviving mechanism that barely loses in the market, I have decided to derive several features, those of particular stock and those of commodities and indices that investors often refer to measure the sentiment of the market.

I will be using ML tools to build a binary classifier, which tells the investors to either buy or sell 5 days prior to the next opening day. After that, we will see in the back testing to find out if the model has any usage. 

We will be testing with random forest classifier. 

## What features are we using?

There are various, in fact hundreds of possible indicators. The following are examples of indicators we are going to use.

- % Price change from previous trading day
- Trade Volume
- Moving Averages 
- MACD
- Bollinger Bands
