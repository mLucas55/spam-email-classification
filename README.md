# Spam Email Classification Model

* Given an email, this model can predict with ~80% accuracy if it is spam.

* This neural network uses Google's BERT transformer to convert emails to vectors which are then fed into a TensorFlow functional model.

* Trained on this data set: https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset/data

* The data set already preprocessed the emails, but there were still some abnormalities that were fixed in this notebook such as removing invalid substrings.

* The data set had a slight imbalance so down sampling was used.
  
* This is my first functional model which was created to continue learning about machine learning.


!! Work in progress !!

## Introduction

The objective of this project is to create and train a machine learning model that can predict if an email is spam or not. I wanted to learn about computer text "recognition" through deep learning and further practice TensorFlow.

Computers understand numbers better than letters; that is why I used a Google's BERT transformer to effectively convert strings into numbers. BERT can take a string and produce a context-aware vector that is then processed in a functional neural network, ultimately leading to a prediction.

An existing transformer was used as the goal wasn't text classification in general, rather it was spam email classification. BERT provides a simple to implement and robust well suited for this task

## Selection of Data

The model was developed and trained in a Colab notebook which is available [here](https://github.com/mLucas55/spam-email-classification/blob/main/code/spam-email-classification.ipynb).
