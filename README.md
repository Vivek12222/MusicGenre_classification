# Overview:
This project focuses on predicting music genres using Principal Component Analysis (PCA) for dimensionality reduction and logistic regression for classification.

# Project Description:
The project involves developing a machine learning model to accurately classify music styles based on audio data. The primary techniques used are PCA for dimensionality reduction and logistic regression for building the classification model.

# Procedure
1. The Dataset was provided by **365 data science**. Initially the dataset is raw so data cleaning and data preprocessing methods was followed to convert raw data to clean data. 
2. Standardization techniques and PCA methods was applied to the data set to achieve dimensionality reduction which is one of the crucial step to reduce multicollinearity.
3. The given dataset was splitted into training and test data set using a scikit-learn module 
4. Logistic regression - One of the classification machine learning algorithm was applied on given training data and the model was trained on the training dataset. The Logistic regression class was imported from 
   sklearn and functions in Logistic Regression class was used to train the model on train data set
5. After training the model was used on test dataset to predict the values. 
6. The accuracy of given model is approximately 53.55%

# License:
This project is licensed under the Apache License 2.0.
