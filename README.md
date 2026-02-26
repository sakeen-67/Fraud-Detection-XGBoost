# Credit Card Fraud Detection using XGBoost

## Overview
This project builds a fraud detection system using XGBoost on a highly imbalanced real-world credit card transaction dataset (284,807 transactions, 0.17% fraud cases).

## Approach
- Stratified train-test split
- SMOTE for class imbalance handling
- Logistic Regression as baseline
- XGBoost as primary model
- ROC-AUC and Precision-Recall evaluation
- Decision threshold optimization

## Final Performance (Optimized Threshold)
- Fraud Recall: 85%
- Fraud Precision: 58%
- ROC-AUC: 0.97
- Average Precision: 0.80

## Key Insight
Threshold tuning significantly improved fraud precision while maintaining high recall, demonstrating practical deployment-level thinking for imbalanced classification.

## Dataset
Credit Card Fraud Detection Dataset (Kaggle)

## Technologies
Python, Pandas, Scikit-learn, XGBoost, SMOTE
