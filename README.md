# Spam Email Classification Model

## Introduction

There are two objectives for this project:
  - Create and train a machine learning model that can predict if an email is spam or not.
  - Learn about text classifcation and functional models

Google's BERT transformer was used. BERT takes a string and produces a context-aware vector that I then processed in the functional neural network, ultimately leading to a prediction.

The model was developed and trained in a Colab notebook which is available [here](https://github.com/mLucas55/spam-email-classification/blob/main/code/spam-email-classification.ipynb).

## Selection of Data

The data set can be found online [here](https://drive.google.com/file/d/1ElqSIk-nJp8yKlz9ZGyVoKQ7e4OE1mpB/view?usp=sharing)

The data set has 83,488 total sample emails with a binary classificaiton colum
  - 0 = not spam
  - 1 = spam
  - 43910 spam
  - 39538 not spam

Data Preview:

![Data screenshot](./graphs/Data-Head.png)

Label Distrubtion:

![Bar screenshot](./graphs/Label-Balance.png)

The data set is a combination of two other spam email data sets. Along with combining data sets the creater also preprocessed all data by removing HTML elements, subjects, and actual email addresses.

However there seemed to be an artifact in the data as a result of the preprocessing: The string 'escapenumber' occured multiple times in essentially all emails. I used str.replace() to replace 'escapenumber' with an empty string. This caused a moderate rise in models accuracy of ~4%

## Methods

Tools:
  - TensorFlow: Machine learning library
  - Pandas: Data manipulation 
  - Seaborn + Matplotlib: Data visualization
  - Colab: Development notebook
  - GitHub: Version control
