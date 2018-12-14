# StockPredictor
Final Project for CS 4701, Practicum in Artificial Intelligence.
By Alexander Li, Rohan Patel, Ryan Tine, Nicole Kwok, and Anthony Yang

This project experimented with predicting stock movement based on new articles from Reuters. We first used a Python crawler to pull news and stock data from each of the FAANG (Facebook, Amazon, Apple, Netflix, Google) stocks. Then, we developed a machine learning pipeline to extract useful features from the text data through a combination of bag-of-words and sentiment analysis. This data was used to train, validate, and test the effectiveness of different models. We compare Random Forest, Naive Bayes, Neural Networks, and SVMs in this project.

Ultimately we found Random Forest to have about 10% validation and testing error for predicitng the movement of Apple stock 1 week after an article is published. This is based off 5 years of data. The default script will train, test, and plot results for Apple stock prediction.
