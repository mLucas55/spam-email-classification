# Spam Email Classification Model
!! Work in progress !!

* Given an email, this model can predict with ~80% accuracy if it is spam.

* This neural network uses Google's BERT transformer to convert emails to vectors which are then fed into a TensorFlow functional model.

* Trained on this data set: https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset/data

* The dat set already preprocessed the emails, but there were still some abnormalities that were fixed in this notebook such as removing invalid substrings.

* The data set had a slight imbalance so down sampling was used.
  
* This is my first functional model which was created to continue learning about machine learning.
