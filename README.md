# Sentiment-Analysis-of-Yelp-reviews
Algorithms used: Logistic Regression, K-Nearest Neighbors and Artificial Neural Network

## Introduction:
Sentiment analysis is part of the Natural Language Processing (NLP) techniques that consists in extracting emotions related to some raw texts. This is usually used on social media posts and customer reviews in order to automatically understand if some users are positive or negative and why. The goal of this study is to show how sentiment analysis can be performed using python. 

## Here are some of the main libraries we will use:
NLTK: the most famous python module for NLP techniques
Gensim: a topic-modelling and vector space modelling toolkit

Gensim module
Scikit-learn: the most used python machine learning library

Scikit-learn module
We will use here some hotel reviews data. Each observation consists in one customer review for one hotel. Each customer review is composed of a textual feedback of the customer’s experience at the hotel and an overall rating. The data can be found in my github folder.

## Goal
For each textual review, we want to predict if it corresponds to a good review (the customer is happy) or to a bad one (the customer is not satisfied).

## Conclusion
It is completely possible to use only raw text as input for making predictions. The most important thing is to be able to extract the relevant features from this raw source of data. This kind of data can often come as a good complementary source in data science projects in order to extract more learning features and increase the predictive power of the models.

After training the reviews with multiple models we realize that the ANN model provides an accuracy of 78% when fine tuned but tuning the model consumes a lot of time. In comparison to that, algorithms like Naive Bayes and Logistic run very fast. Naive Bayes gave an impressive accuracy (78.13%) while taking minimal time. Hence Naive Bayes is considered as the best model as per my analysis. If we would have more data then I think ANN could have achieved even more accuracy.
