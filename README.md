# Customer-churn-prediction


## Overview
This project is focused on predicting customer churn using a neural network-based machine learning model. Customer churn is a critical business metric, and predicting it can help businesses take proactive measures to retain their customers.
In this project, we:
- Load and explore the dataset.
- Preprocess the data by handling missing values and encoding categorical variables.
- Build a neural network model using TensorFlow and Keras.
- Train and evaluate the model's performance for churn prediction.

## Dataset
We use the 'churn.csv' dataset for this project. It contains information about customers, their demographics, and various features that may influence their decision to churn.
Link to dataset:https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Data Preprocessing
- We start by dropping unwanted features.
- Handle missing values.
- Convert data types to the appropriate format.
- Encode categorical variables into numeric form.
- Scale numerical features using Min-Max scaling.

## Neural Network Model
We create a neural network model using TensorFlow and Keras. The model architecture consists of several dense layers with ReLU activation functions, culminating in a sigmoid output layer for binary classification (churn or no churn).

## Model Training
The model is trained on the preprocessed data using the Adam optimizer and binary cross-entropy loss. We monitor accuracy during training.

## Required libraries
NumPy, pandas, Matplotlib, TensorFlow
