## Project Overview

This project was completed as part of the Oasis Infobyte Data Analytics Internship (Level 2 – Task 3).

The objective of this project is to build a Machine Learning model that can detect fraudulent credit card transactions. Since fraudulent transactions represent only a tiny fraction of all transactions, this project focuses on analysing the dataset, understanding class imbalance, and developing a classification model to distinguish fraudulent transactions from legitimate ones.

 ## Objective
Analyse the credit card transaction dataset.
Perform Exploratory Data Analysis (EDA).
Clean and preprocess the data.
Train a Machine Learning model to detect fraud.
Evaluate the model using standard classification metrics.
Provide business insights based on the results.
 ## Dataset

Dataset: Credit Card Fraud Detection Dataset

Due to GitHub's 100 MB file size limit, the dataset is not included in this repository.

You can download it from Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

 ## Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

 ## Project Structure
DataAnalytics-L2-FraudDetection/
│
├── dataset/
│
├── image/
│   ├── class_distribution.png
│   ├── transaction_amount_distribution.png
│   ├── time_distribution.png
│   ├── correlation_heatmap.png
│   ├── amount_by_class.png
│   └── confusion_matrix.png
│
├── notebook/
│   └── Fraud_Detection.ipynb
│
├── README.md
└── requirements.txt

 Exploratory Data Analysis

## The following analyses were performed:

Dataset overview
Missing value detection
Duplicate value removal
Class distribution analysis
Transaction amount distribution
Transaction time distribution
Correlation heatmap
Amount comparison between fraud and legitimate transactions
 ## Data Preprocessing

The following preprocessing steps were completed:

Removed duplicate records
Selected input features and target variable
Split data into training and testing sets
Standardised features using StandardScaler
 ## Machine Learning Model

 Algorithm Used

Logistic Regression

The dataset was divided into:

Training Data: 80%
Testing Data: 20%
##  Model Evaluation

The model was evaluated using:

Accuracy Score
Precision
Recall
F1-Score
Classification Report
Confusion Matrix
 ## Key Findings
The dataset is highly imbalanced, with fraudulent transactions making up only a very small percentage of all transactions.
Most transactions involve relatively small amounts.
Feature scaling improved the stability and convergence of the Logistic Regression model.
The confusion matrix and classification metrics helped evaluate the model's ability to identify fraudulent transactions.

## Dataset

The dataset used for this project is the **Credit Card Fraud Detection Dataset**.

Due to GitHub's 100 MB file size limit, the dataset is not included in this repository.

You can download it from:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud