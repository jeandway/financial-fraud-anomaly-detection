# Anomaly Detection in Financial Transactions
This project applies machine learning and anomaly detection techniques to credit-card fraud detection using a highly imbalanced financial transaction dataset.
The goal is to compare supervised classification, unsupervised anomaly detection, and clustering-based anomaly scoring to identify fraudulent transactions.

## Project Overview
Credit-card fraud detection is a classic anomaly detection problem because fraudulent transactions are rare compared to legitimate transactions. In this project, 
I compared multiple machine learning models and evaluated them using metrics that are better suited for imbalanced data, such as precision, recall, F1-score, ROC-AUC, and PR-AUC.

## Dataset
Dataset: European Credit Card Fraud Detection Dataset  
Source: Kaggle / ULB Machine Learning Group

The dataset contains:

- 284,807 transactions
- 492 fraud cases
- Fraud rate around 0.172%
- 30 features including Time, Amount, V1-V28, and Class

The dataset file is not included in this repository because of size and licensing. It can be downloaded from Kaggle.

## Models Compared
- Logistic Regression
- k-Nearest Neighbors
- Gaussian Naive Bayes
- Decision Tree
- Random Forest
- Random Forest with SMOTE
- XGBoost
- Isolation Forest
- Local Outlier Factor
- One-Class SVM
- K-Means distance-based anomaly scoring

## Best Result
XGBoost achieved the strongest overall performance:

- PR-AUC: 0.8832
- Precision: 89.3%
- Recall: 84.7%
- F1-score: 0.8691

## Key Techniques
- Imbalanced classification
- Fraud detection
- Anomaly detection
- SMOTE oversampling
- Cost-sensitive threshold tuning
- Precision-recall analysis
- SHAP model interpretation
- Data visualization

## Tools Used
- Python
- pandas
- NumPy
- scikit-learn
- XGBoost
- imbalanced-learn
- SHAP
- matplotlib
- seaborn
- Jupyter Notebook

## Project Report

The full project report is available in the `report/` folder.
