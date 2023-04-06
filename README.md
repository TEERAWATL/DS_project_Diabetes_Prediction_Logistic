# Diabetes Prediction using Elastic Net Logistic Regression

Predict the presence of diabetes using Elastic Net Logistic Regression, a supervised machine learning algorithm.

## Description

This project predicts the presence of diabetes using the Elastic Net Logistic Regression model, a supervised machine learning algorithm that combines both L1 (Lasso) and L2 (Ridge) regularization. Elastic Net Logistic Regression is particularly useful when dealing with datasets that have correlated features or when you want to balance between L1 and L2 regularization.

Usage
Run the main script to execute the project:
Diabetes_prediction.ipynb

Dependencies
The project requires the following libraries:

Python 3.7
NumPy
pandas
scikit-learn
Matplotlib (optional, for data visualization)
seaborn (optional, for data visualization)
Install the dependencies using the following command:

pip install numpy pandas scikit-learn matplotlib seaborn

Dataset
The dataset used is the Diabetes Health Indicators Dataset, which consists of 253,680 survey responses from the cleaned BRFSS 2015 and a balanced dataset.

Dataset file: diabetes_binary_5050split_health_indicators_BRFSS2015.csv

Data Preprocessing
Load the dataset using pandas.
Clean and preprocess the data by handling missing values, scaling the data, and transforming categorical variables.
Split the dataset into training and testing sets using train_test_split from scikit-learn.
Model Training
Train an Elastic Net Logistic Regression model using scikit-learn.
Use the prepared training set for model training.
Model Evaluation
Evaluate the model's performance using the test set.
Calculate the mean squared error, accuracy score, and confusion matrix using scikit-learn.
Visualize the results using Matplotlib and seaborn.
