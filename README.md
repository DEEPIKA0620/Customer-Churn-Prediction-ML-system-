# Customer Churn Prediction

## Project Overview

Customer churn is one of the major challenges faced by businesses. Losing existing customers directly impacts revenue and growth. This project uses Machine Learning techniques to predict whether a customer is likely to leave the company based on customer demographics, service usage, and billing information.

## Problem Statement

Businesses often struggle to identify customers who are likely to discontinue their services. The objective of this project is to build a machine learning model that predicts customer churn and helps organizations take proactive retention measures.

## Dataset

* Dataset: Telco Customer Churn Dataset
* Total Records: 7043
* Features: Customer demographics, account information, service details, billing information, and churn status.
* Target Variable: Churn (Yes/No)

## Tools and Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Data Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Encoding
6. Model Training
7. Model Evaluation
8. Business Insights Generation

## Machine Learning Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

## Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 81.62%   | 67.38%    | 59.25% | 63.05%   |
| Decision Tree       | 71.47%   | 46.19%    | 47.18% | 46.68%   |
| Random Forest       | 79.99%   | 66.79%    | 48.53% | 56.21%   |

## Key Insights

* Customers with month-to-month contracts are more likely to churn.
* Higher monthly charges are associated with increased churn risk.
* Customers with shorter tenure tend to leave more frequently.
* Contract type plays a significant role in customer retention.

## Conclusion

Among the evaluated models, Logistic Regression achieved the best overall performance. The developed churn prediction system can help businesses identify high-risk customers and improve customer retention strategies.

