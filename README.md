# SecureSwipe
Credit card fraud detection using machine learning, with comparative model evaluation and research documentation.

# SecureSwipe: Credit Card Fraud Detection System

## Overview

SecureSwipe is a machine learning-based credit card fraud detection project developed during my machine learning internship. The project focuses on identifying fraudulent transactions by training and comparing multiple classification models.

## Objectives

- Analyze and preprocess credit card transaction data.
- Perform exploratory data analysis (EDA).
- Train and compare different machine learning models.
- Evaluate model performance using multiple metrics.
- Identify an effective model for fraud detection.

## Dataset

The project uses the European Credit Card Fraud Detection dataset from Kaggle.

- Total transactions: 284,807
- Fraudulent transactions: 492
- Features: V1–V28, Time, Amount
- Target: Class (0 = Legitimate, 1 = Fraudulent)

## Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting
- XGBoost

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Results

Random Forest achieved the following reported results in our study:

| Metric | Score |
|---|---|
| Accuracy | 99.92% |
| Precision | 96.5% |
| Recall | 91.8% |
| F1-Score | 94.1% |
| ROC-AUC | 0.996 |

These results are based on the experimental evaluation documented in the research paper.

## Repository Contents

- `notebooks/` – Machine learning project notebook
- `research-paper/` – Research paper PDF

## Future Work

- Real-time fraud detection
- Explainable AI (XAI)
- Improved class imbalance handling
- Validation using additional datasets

## Authors

Pratibha Gupta  
Nishu

Mathematics and Computing  
Indira Gandhi Delhi Technical University for Women
