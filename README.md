# Customer Churn Prediction in the Telecommunications Industry Using Machine Learning

## Overview

This project focuses on predicting customer churn in the telecommunications industry using machine learning techniques. The project covers data cleaning, preprocessing, exploratory data analysis, statistical analysis, feature engineering, model development, evaluation, and business recommendations.

This project was completed as part of the IDRA Summer Training Program in Data Science and AI.

## Objective

The main objective of this project is to identify factors associated with customer churn and develop a machine learning model to predict customers who are likely to churn.

## Dataset

The project uses the Telco Customer Churn dataset provided as part of the IDRA Summer Training Program.

- **Records:** 7,043
- **Variables:** 20
- **Target Variable:** Churn

The dataset is not included in this repository. The IDRA-provided `Telco-Customer-Churn.csv` file is required to run the notebook.

## Project Workflow

1. Data Loading and Understanding
2. Data Cleaning
3. Data Preprocessing
4. Exploratory Data Analysis
5. Statistical Analysis
6. Feature Engineering
7. Data Preparation
8. Machine Learning Model Development
9. Model Evaluation and Comparison
10. Final Model Selection
11. Business Insights and Recommendations

## Machine Learning Models

Five classification models were developed and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## Final Model

Support Vector Machine (SVM) was selected as the final model using **F1-score as the primary model selection criterion**.

### SVM Performance

| Metric | Score |
|---|---:|
| Accuracy | 74.59% |
| Precision | 51.41% |
| Recall | 78.07% |
| F1-Score | 62.00% |
| ROC-AUC | 82.49% |

## Key Findings

The analysis identified higher observed churn rates among:

- Month-to-month contract customers
- Customers with shorter tenure
- Fiber optic internet service customers
- Electronic check payment users
- Customers with higher monthly charges

These findings represent statistical associations and should not be interpreted as proof of causal relationships.

## Business Recommendations

- Strengthen onboarding and early-stage customer retention.
- Encourage customers to adopt longer-term contracts.
- Investigate pricing, service quality, and support for fiber optic customers.
- Promote convenient payment methods.
- Use predictive modelling to prioritize customers for retention initiatives.
- Collect additional customer information to improve future churn prediction.

## Repository Structure

```text
customer-churn-prediction/
│
├── Customer_Churn_Prediction_Capstone.ipynb
├── IDRA_Capstone_Project_Report.docx
├── IDRA_Capstone_Project_Report.pdf
├── README.md
└── LICENSE
