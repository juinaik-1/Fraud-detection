# Fraud-detection

## Overview

This project aims to develop a machine learning model to predict fraudulent transactions for a financial company. The dataset contains transaction details over a 30-day simulation period, and the objective is to identify fraudulent activities based on transaction patterns.

## Dataset

The dataset used in this project contains 6,362,620 rows and 10 columns.
Dataset link: [kaggle](https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data)

## Getting Started

### Prerequisites
1) Python 3.7 or later
2) Jupyter Notebook
3) Required Python libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imblearn

### Data Preparation

The data preparation steps include:

  1) Loading the Dataset: Read the CSV file into a pandas DataFrame.
  2) Data Cleaning: Remove outliers and handle missing values.
  3) Feature Engineering: Create new features such as errorBalanceOrig and errorBalanceDest.
  4) One-Hot Encoding: Convert categorical features into numerical values using one-hot encoding.
  5) Splitting the Data: Split the data into training and testing sets.
  6) Feature Scaling: Standardize the feature values.

### Model Development

The model development steps include:

  1) Feature Selection: Use a Random Forest model to select the top 10 most important features.
  2) Model Training: Train a Random Forest classifier on the training data.
  3) Model Evaluation: Evaluate the model using metrics such as confusion matrix, classification report, ROC-AUC score, and visualize the ROC curve.

Model Evaluation:
    Accuracy: 99.99%
    ROC-AUC Score: 0.9965

## Conclusion

The Random Forest model achieved high accuracy (99.99%) and a ROC-AUC score of 0.9965, indicating excellent performance in detecting fraudulent transactions. Further steps can include testing the model on real-world data, improving feature engineering, and exploring other machine learning models.

## Future Work

  1) Validate the model on real-world datasets.
  2) Explore advanced feature engineering techniques.
  3) Experiment with other machine learning models.
  4) Implement the model in a production environment for real-time fraud detection.
