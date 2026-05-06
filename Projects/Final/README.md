# Final Project: Credit Card Fraud Detection

## Objective
The goal of this project is to detect fraudulent credit card transactions using machine learning models.

## Problem Type
This is a binary classification problem:
- 0 = Normal transaction
- 1 = Fraudulent transaction

## Dataset
The dataset used is the Kaggle Credit Card Fraud Detection dataset, which contains real transaction data. The dataset is highly imbalanced, with very few fraud cases compared to normal transactions.

## Approach
- Loaded and explored the dataset
- Handled class imbalance using undersampling
- Split data into training and testing sets
- Scaled features using StandardScaler
- Trained multiple machine learning models
- Compared model performance using evaluation metrics

## Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Results
The best-performing models were KNN and Random Forest, which showed strong performance in detecting fraud cases.

## Challenges
- Highly imbalanced dataset
- Trade-off between precision and recall
- Risk of false negatives in fraud detection

## What I Learned
- How to handle imbalanced datasets
- Importance of evaluation metrics beyond accuracy
- Real-world application of machine learning in financial fraud detection

## Conclusion
This project demonstrates how machine learning can be used to detect fraud effectively, although challenges such as class imbalance remain critical.
