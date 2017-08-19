# LSTM_Sentiment_Classification
Implementation of LSTM architecture in Keras to perform sentiment analysis on movie reviews from the Large Movie Review Dataset.

## Dataset
The Large Movie Review Dataset (often referred to as the IMDB dataset) contains 25,000 highly-polar movie reviews (good or bad) for training and the same amount again for testing. The problem is to determine whether a given movie review has a positive or negative sentiment.

Link to download dataset [here](http://ai.stanford.edu/~amaas/data/sentiment/)

The data was collected by **Stanford researchers** and was used in a 2011 paper where a split of 50-50 of the data was used for training and test. **An accuracy of 88.89% was achieved.**

## Models
1. A Simple LSTM Network
2. LSTM Network With Dropout
3. LSTM and Convolutional Neural Network with dropout

## Results
1. Simple LSTM - 85.72%
2. LSTM Network With Dropout - 85.67%
3. LSTM and Convolutional Neural Network with dropout - **88.41% !**

## Credits -
The following resources are extremely useful for a detailed understanding of this task or Deep Learning techniques:
1. [WildML blog](http://www.wildml.com/2015/12/implementing-a-cnn-for-text-classification-in-tensorflow/) by Denny Britz
2. [Machine Learning Mastery](http://machinelearningmastery.com/) blog by Dr.Jason Brownlee
3. Andrej Karpathy's blog on [RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
