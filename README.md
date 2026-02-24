# fraud-detection-fintech
End-to-end credit card fraud detection model using Python
# Credit Card Fraud Detection Model
**Author:** Krishnaprasad Seshadri  
**Tools:** Python, Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn

## Project Summary
End-to-end fraud detection model built on 284,807 real credit card transactions. 
Addresses severe class imbalance (0.17% fraud) using SMOTE oversampling and 
evaluates performance using metrics appropriate for imbalanced datasets.

## Key Results
| Metric | Score |
|--------|-------|
| ROC AUC Score | 0.9644 |
| Fraud Recall | 83% |
| Fraud Precision | 83% |
| Dataset Size | 284,807 transactions |

## Key Techniques
- Exploratory Data Analysis and class imbalance visualisation
- SMOTE oversampling applied exclusively to training data
- Random Forest classifier with 100 estimators
- Evaluation using precision, recall, F1 and ROC AUC

## Dataset
[Credit Card Fraud Detection — Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Notebook
See `fraud_detection.ipynb` for the full annotated walkthrough.
