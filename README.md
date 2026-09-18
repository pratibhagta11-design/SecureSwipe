
# 🔐 SecureSwipe: Credit Card Fraud Detection System

### Machine Learning-Based Fraud Detection | Internship Project & Research Paper

SecureSwipe is a machine learning project developed during my internship to identify fraudulent credit card transactions. The project explores data preprocessing, exploratory data analysis, and comparative evaluation of multiple machine learning models.

The study focuses on handling imbalanced transaction data and evaluating model performance using relevant classification metrics.

---

## 📌 Project Overview

Credit card fraud detection is a challenging machine learning problem because fraudulent transactions represent a very small proportion of total transactions.

In this project, different machine learning models were trained and compared using the European Credit Card Fraud Detection dataset to study their performance in identifying fraudulent transactions.

## 🎯 Objectives

- Analyze and preprocess credit card transaction data.
- Perform Exploratory Data Analysis (EDA).
- Train multiple machine learning classification models.
- Compare model performance using different evaluation metrics.
- Identify the model with the strongest reported performance in this study.

## 📊 Dataset

**Dataset:** European Credit Card Fraud Detection

- Total Transactions: 284,807
- Fraudulent Transactions: 492
- Legitimate Transactions: 284,315
- Features: V1–V28, Time, Amount
- Target Variable: Class
  - `0` – Legitimate Transaction
  - `1` – Fraudulent Transaction

Most transaction features are anonymized using Principal Component Analysis (PCA).

Dataset Source:
[Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🤖 Machine Learning Models

The following models were implemented and compared:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)
5. K-Nearest Neighbors (KNN)
6. Gradient Boosting
7. XGBoost

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

Since the dataset is highly imbalanced, multiple evaluation metrics were considered instead of relying only on accuracy.

## 🏆 Reported Results

According to the research paper, Random Forest achieved the following results:

| Metric | Performance |
|---|---|
| Accuracy | 99.92% |
| Precision | 96.5% |
| Recall | 91.8% |
| F1-Score | 94.1% |
| ROC-AUC | 0.996 |

These figures represent the results reported in the accompanying research paper. They should not be interpreted as a guarantee of performance on new or real-world transaction data.

## 📂 Repository Structure

```text
SecureSwipe/
│
├── notebooks/
│   └── credit_card_fraud_detection.ipynb
│
├── research-paper/
│   └── SecureSwipe_Research_Paper.pdf
│
├── README.md
└── requirements.txt
```

## 🔍 Project Workflow

1. Dataset Loading
2. Data Understanding and Preprocessing
3. Exploratory Data Analysis
4. Feature Analysis
5. Model Training
6. Model Evaluation
7. Comparative Performance Analysis

## 📄 Research Paper

The research paper associated with this project is included in the `research-paper/` directory.

**Title:** SecureSwipe: Credit Card Fraud Detection System Using Machine Learning

**Authors:**
- Pratibha Gupta
- Nishu

## 🚀 Future Work

- Real-time fraud detection
- Explainable AI (XAI)
- Improved class imbalance handling
- Evaluation on additional datasets
- Investigation of evolving fraud patterns

## 👩‍💻 Authors

**Pratibha Gupta**  
Mathematics and Computing  
Indira Gandhi Delhi Technical University for Women

**Nishu**  
Mathematics and Computing  
Indira Gandhi Delhi Technical University for Women

---

⭐ This repository documents the machine learning internship project and its associated research work.
