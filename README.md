# Clothing-Reviews-Sentiment-Analysis
In this project we work with Womens-ecommerce-clothing-reviews data, and do sentiment analysis on the customers' reviews to predict if the product has been recommended or not. 
We first do EDA, and then preprocess the data by preprocessing the reviews (text) using nltk, oversampling the data (as the classes are unbalanced), and vectorization of the reviews (text).
We finally implement different ML (Linear Regression, SVM, Random Forest) and DL models (LSTM, GRU, Bidirectional LSTM) in Scikit-learn and Keras respectively, 
and comapre their performance on the test data through the use of different classification metrics (accuracy, precision, recall, F1-score) to see which model gives us the best performance. We found our random forest classifier achieves the best performance of 97% F1-score on the test data. 

