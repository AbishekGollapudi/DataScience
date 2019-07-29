# Sentiment Analysis on U.S. Airline Tweets

## Datasets

<https://www.kaggle.com/crowdflower/twitter-airline-sentiment> 

https://www.kaggle.com/rtatman/glove-global-vectors-for-word-representation

Data was preprocessed to remove neutral tweets and only focus on polarizing ones (positive and negative).

## Project Overview

This is an RNN implementation for sentiment analysis with a 2-layer bidirectional LSTM included to improve model performance. Because this is a relatively small dataset, any models trained are prone to overfitting. In order to reduce overfitting and improve the performance of word embeddings, I transferred Stanford's Glove to use pre-trained word embeddings as part of an embedding matrix inputted to my model's embedding layer.

## Results

The model performs very well with a 91-92% accuracy on both the validation set and the test set. However, training the model on a larger set of data will still allow it to better generalize and classify new tweets.
