# Credit Card Fraud Analysis
This project involves analyzing a credit card fraud dataset and building machine learning models to detect fraudulent transactions. It includes steps such as data exploration, feature scaling, balancing the dataset, and training various classifiers. This project aims to address the issue of imbalanced datasets and provide insights into effective fraud detection.

## Project Overview
Credit card fraud detection is critical for financial systems. Fraudulent transactions are rare compared to legitimate ones, which creates an imbalance in the dataset. This project uses various techniques like scaling features and undersampling to balance the data and trains machine learning models to improve accuracy in fraud detection.

## Features:
### Data Preprocessing: Handling imbalanced data and scaling features.
### Data Visualization: Correlation heatmaps and class distribution visualizations.
### Model Training: Logistic Regression, K-Nearest Neighbors, Support Vector Machine, and Decision Tree Classifier models.
### Model Evaluation: Accuracy and F1-score evaluation for balanced and imbalanced datasets.

## Dataset
The dataset used for this project can be found here. It contains credit card transactions made by European cardholders in September 2013. The dataset includes 492 fraudulent transactions out of 284,807 total transactions, making it highly imbalanced.

## Dataset Features:
Time: Seconds elapsed between this transaction and the first transaction in the dataset.
Amount: Transaction amount.
V1 to V28: Principal components obtained using PCA.
Class: Target variable (0 for non-fraud, 1 for fraud).

## Summary of Results
Balanced Dataset: Undersampling was applied to balance the dataset, resulting in an equal distribution of fraudulent and non-fraudulent transactions.
Correlation Analysis: Several features (V2, V4, V11, V19) were positively correlated with fraudulent transactions, while others (V3, V7, V10, V12, V14, V17) were negatively correlated.
Model Accuracy: The Logistic Regression model achieved an accuracy of ~95% on the balanced dataset. Further improvements are possible by tuning model parameters or trying other advanced models.
