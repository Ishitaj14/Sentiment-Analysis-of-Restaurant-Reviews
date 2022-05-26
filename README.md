# Sentiment-Analysis-of-Restaurant-Reviews
This is a Data Science Project based on using Natural Language processing with Restaurant reviews and analyzing the text data to finally perform sentiment analysis using Text classification

## Aim
The aim of this analysis is to build a prediction model to predict whether a review on the restaurant is positive or negative. To do so, I worked on Restaurant Review dataset , and loaded it into predicitve algorithms Multinomial Naive Bayes, Bernoulli Naive Bayes and Logistic Regression. Towards the end I tried to find the "best" model for predicting the review's sentiment.

Dataset: Restaurant_Reviews.tsv is a dataset from Kaggle datasets which consists of 1000 reviews on a restaurant.

### Steps performed
To build a model to predict if review is positive or negative, following steps are performed.

-Importing Dataset
-Reviews Analysis
-Preprocessing Dataset
-Vectorization
-Training and Classification
-Analysis Conclusion
-Saving the best model

## Files
1.Restaurant_Reviews.tsv (original data file)

2.Reviews Analysis.ipynb (textual analysis of the data)

3.Reviews Classifier.ipynb (notebook where model was trained and model, corpus saved with the help of pickle)

## Conclusion
The sentiment analyis was carried out through various methods. It was observed that Multinomial Naive Bayes is slightly better method compared to Bernoulli Naive Bayes and Logistic Regression, with 77.67% accuracy which means the model built for the prediction of sentiment of the restaurant review gives 77.67% right prediction.
The aim of the model is to correctly detect the sentiments of the textual reviews or feedback. The developed model can successfully detects the sentiments of the textual reviews or feedback. The model has been tested with few of the online reviews and was found that it detects the sentiments correctly. Thus, we can conclude that the motive was successful and this model can be used by restarants to understand their sentiments through their reviews and accordingly they can work on their shortcomings.





