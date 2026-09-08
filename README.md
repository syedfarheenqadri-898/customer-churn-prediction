# Customer Churn Prediction in the Telecommunications Industry Using Machine Learning

## Overview

This project focuses on predicting customer churn in the telecommunications industry using machine learning techniques. The project includes data cleaning, preprocessing, exploratory data analysis, statistical analysis, feature engineering, model development, evaluation, and business recommendations.

The project was completed as part of the IDRA Summer Training Program in Data Science and AI.

## Objective

The main objective of this project is to identify factors associated with customer churn and develop a machine learning model that can predict customers who are likely to churn.

## Dataset

The project uses the Telco Customer Churn dataset provided as part of the IDRA Summer Training Program.

- Records: 7,043
- Variables: 20
- Target variable: Churn

The dataset file is not included in this repository. Place the IDRA-provided `Telco-Customer-Churn.csv` file in the project directory before running the notebook.

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

The following classification models were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## Final Model

Support Vector Machine (SVM) was selected as the final model based on the highest F1-score, which was used as the primary model selection criterion.

### SVM Performance

| Metric | Score |
|---|---:|
| Accuracy | 74.59% |
| Precision | 51.41% |
| Recall | 78.07% |
| F1-Score | 62.00% |
| ROC-AUC | 82.49% |

## Key Findings

The analysis identified several customer groups with higher observed churn rates:

- Month-to-month contract customers
- Customers with shorter tenure
- Fiber optic internet service customers
- Electronic check payment users
- Customers with higher monthly charges

The analysis shows associations between these factors and churn; it does not establish causal relationships.

## Business Recommendations

- Strengthen onboarding and early-stage customer retention.
- Encourage customers to move toward longer-term contracts.
- Investigate pricing, service quality, and support for fiber optic customers.
- Promote convenient payment methods.
- Use predictive modelling to prioritize customers for retention initiatives.

## Limitations
- The dataset does not contain some potentially useful factors such as customer satisfaction and service quality information.
- Model evaluation was based on a single train-test split.
- Hyperparameter optimization was not performed.
- Preprocessing was performed before the train-test split, resulting in minor data leakage.
- Further validation and optimization would be required before real-world deployment.

