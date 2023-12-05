# Spam Email Classification Model

## Introduction

The objective of this project is to create and train a machine learning model that can predict if an email is spam or not. I wanted to learn about computer text "recognition" through deep learning and further practice TensorFlow.

Computers understand numbers better than letters; that is why I used a Google's BERT transformer to effectively convert strings into numbers. BERT can take a string and produce a context-aware vector that is then processed in a functional neural network, ultimately leading to a prediction.

An existing transformer was used as the goal wasn't text classification in general, rather it was spam email classification. BERT provides a simple to implement and robust well suited for this task

## Selection of Data

The model was developed and trained in a Colab notebook which is available [here](https://github.com/mLucas55/spam-email-classification/blob/main/code/spam-email-classification.ipynb).

The data set has 83,488 total sample emails with a binary classificaiton colum
  - 0 = not spam
  - 1 = spam
  - 43910 spam
  - 39538 not spam
