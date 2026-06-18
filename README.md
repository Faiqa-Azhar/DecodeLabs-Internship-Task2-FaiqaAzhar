# Fraud Detection Using Machine Learning 🚨

## Project Description

This project focuses on building a **Fraud Detection Classification Pipeline** using supervised machine learning techniques. The goal is to identify fraudulent transactions from a highly imbalanced dataset by applying data preprocessing, imbalance handling, model training, and evaluation techniques.

The project uses **SMOTE (Synthetic Minority Over-sampling Technique)** to balance fraud and non-fraud transactions and implements classification models such as **Logistic Regression** and **Random Forest**.

The models are evaluated using strict performance metrics including **Precision, Recall, and ROC-AUC** instead of accuracy because fraud detection datasets are usually highly imbalanced.




# Objectives

- Build a machine learning model to detect fraudulent transactions
- Handle imbalanced classification data
- Apply SMOTE for minority class balancing
- Train multiple classification algorithms
- Compare model performance using evaluation metrics
- Generate predictions for new transactions


# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Imbalanced-Learn
- Matplotlib (Visualization)



# Machine Learning Models

## 1. Logistic Regression

Used as a baseline classification algorithm for predicting fraud probability.

## 2. Random Forest Classifier

An ensemble learning algorithm used for better fraud detection performance.



# Data Preprocessing Steps

The following preprocessing techniques were applied:

- Dataset structure analysis
- Missing value detection and handling
- Feature and target separation
- Data scaling
- Label verification
- Class imbalance analysis
- SMOTE oversampling



# Handling Class Imbalance

Fraud detection datasets usually contain fewer fraud transactions compared to normal transactions.

To solve this problem:

**SMOTE (Synthetic Minority Oversampling Technique)** was applied to generate synthetic fraud samples and balance both classes.




# Model Evaluation Metrics

Accuracy was not used because it can give misleading results on imbalanced datasets.

The models were evaluated using:

### Precision
Measures how many predicted fraud transactions are actually fraud.

### Recall
Measures how many actual fraud transactions were successfully detected.

### ROC-AUC
Measures the model's ability to separate fraud and non-fraud classes.



# Results

The trained models were evaluated and compared using:

- Precision Score
- Recall Score
- ROC-AUC Score

The best performing model was selected after hyperparameter tuning.



# Author
Faiqa Azhar

