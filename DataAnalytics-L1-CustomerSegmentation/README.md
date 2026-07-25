# Customer Segmentation Analysis

## Project Overview

This project was completed as part of the Oasis Infobyte Data Analytics Internship (OIBSIP).

The objective of this project is to analyze customer data and segment customers into different groups using the K-Means Clustering algorithm. Customer segmentation helps businesses understand customer behavior and develop targeted marketing strategies.

---

## Objective

- Analyze customer demographic and spending data.
- Perform Exploratory Data Analysis (EDA).
- Apply the K-Means clustering algorithm.
- Identify distinct customer segments.
- Generate business insights for decision-making.

---

## Dataset

Dataset: Mall Customers Dataset

The dataset contains the following attributes:

- CustomerID
- Genre (Gender)
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

---

## Project Structure

```
DataAnalytics-L1-CustomerSegmentation/
│
├── dataset/
│   └── Mall_Customers.csv
│
├── image/
│   ├── age_distribution.png
│   ├── gender_distribution.png
│   ├── income_distribution.png
│   ├── spending_distribution.png
│   ├── correlation_heatmap.png
│   ├── elbow_method.png
│   └── customer_segmentation.png
│
├── notebook/
│   └── Customer_Segmentation.ipynb
│
├── README.md
└── requirements.txt
```

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview
- Statistical summary
- Missing value check
- Duplicate value check
- Age distribution
- Gender distribution
- Annual Income distribution
- Spending Score distribution
- Correlation analysis
- Pair plot visualization

---

## Customer Segmentation

The K-Means Clustering algorithm was applied using the following features:

- Annual Income (k$)
- Spending Score (1–100)

The Elbow Method was used to determine the optimal number of clusters.

---

## Results

The clustering process grouped customers into different segments based on their purchasing behavior and income levels.

The visualization clearly shows distinct customer groups and their cluster centroids.

---

## Business Insights

- High-income and high-spending customers represent premium customers.
- High-income but low-spending customers can be targeted with promotional campaigns.
- Low-income and high-spending customers demonstrate strong purchasing engagement.
- Low-income and low-spending customers are budget-conscious shoppers.
- Customer segmentation enables businesses to personalize marketing strategies and improve customer retention.

---

## Conclusion

Customer segmentation using K-Means Clustering provides valuable insights into customer behavior.

This project demonstrates how machine learning can help businesses identify customer groups, improve marketing strategies, optimize resource allocation, and enhance customer satisfaction.

---

##  Author

Siddarth Danu

Oasis Infobyte Data Analytics Internship (OIBSIP)

Level 1 – Task 2: Customer Segmentation Analysis