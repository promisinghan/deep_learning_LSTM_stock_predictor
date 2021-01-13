> # Deep Learning 
# Unit 14 | LSTM Stock Predictor

## Background

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Cypro Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

In this assignment, you will use deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

You will need to:

1. Prepare the data for training and testing.

2. Build and train custom LSTM RNNs.

3. Evaluate the performance of each model.
<br>
<br>

>Let's do it!

![deep learning](https://images.pexels.com/photos/373543/pexels-photo-373543.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940 "Let's use deep learning to predict bitcoin closing price!")

*Photo by [Pixabay](https://www.pexels.com/@pixabay) from [Pexels](https://www.pexels.com/photo/abstract-art-blur-bright-373543/) / [Free License](https://www.pexels.com/license/)*
