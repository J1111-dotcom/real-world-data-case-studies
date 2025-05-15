# Credit Card Fraud Detection

This project simulates a real-world scenario for a data analyst working with a financial services client.

A payment processor wants to proactively detect fraudulent credit card transactions in real time. They’ve provided historical data containing both legitimate and fraudulent transactions and asked for a predictive model that can help reduce fraud-related losses.


## Problem Statement

Detect and classify fraudulent transactions based on anonymized financial data to support real-time fraud prevention workflows.


## Objective

Build and evaluate classification models using imbalanced data techniques, focusing on metrics like recall, precision, and ROC AUC.  
The final model should minimize false negatives (missed frauds) without overwhelming the system with false positives.


## Key Steps

- Data inspection, cleaning, and preprocessing  
- Exploratory analysis with a focus on fraud-vs-legit distribution  
- Feature scaling and normalization  
- Model development using Decision Tree and SVM  
- Evaluation based on precision, recall, f1-score, and ROC AUC


## Results

- **Best Model:** Support Vector Machine (SVM)  
- **ROC AUC:** 0.9720  
- **Recall (Fraud):** 89%  
- **Precision (Fraud):** 38%

The SVM model offered the best balance between high fraud catch rate and minimal disruption to legitimate users.


## Data Visualization

For visual context, refer to the [images](finance/credit-card-fraud-detection/images) folder for key exploratory and evaluation outputs:

- Class distribution highlighting the extreme imbalance
- Feature correlation with fraud
- Final model performance metrics (SVM)


## Business Recommendations

- Deploy the model as a real-time fraud detection layer during transaction authorization
- Use the SVM model to reduce false positives while maintaining high fraud recall
- Route flagged transactions for manual review or temporary hold
- Retrain periodically with updated data to adapt to evolving fraud patterns


##  Folder Structure
```
credit-card-fraud/
│
├── data/ # CSV file hosted locally
├── credit_card_fraud.ipynb # Main project notebook
├── requirements.txt
└── README.md
```

---

## Portfolio

This project is part of a broader portfolio showcasing practical applications of data science across analytics, visualization, and machine learning.  
For more projects, visit [My GitHub Portfolio](https://github.com/dataworksbyj).

