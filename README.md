# Customer Churn Prediction for DTH Services

## Overview
This project focuses on predicting customer churn for a Direct-To-Home (DTH) service provider, faced with high competition and customer retention costs. By leveraging machine learning models, the project aims to identify potential churners and suggest targeted offers to retain them effectively.

## Table of Contents
- [Project Background](#project-background)
- [Data Overview](#data-overview)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Building](#model-building)
- [Model Performance](#model-performance)
- [Business Insights and Recommendations](#business-insights-and-recommendations)
- [Contributors](#contributors)
- [License](#license)

## Project Background
The DTH industry's churn rate stands at 14-16%, with the company experiencing a churn rate of 16.84%. This project was undertaken to reduce churn by predicting potential churners using data-driven insights and implementing targeted retention strategies.

### Objectives
- Develop a churn prediction model that can accurately predict potential churners.
- Provide clear and actionable retention strategies to reduce customer churn.
- Enhance the company's revenue by improving customer retention rates.

## Data Overview
The dataset includes data from 11,260 unique customer accounts with 19 attributes, such as account tenure, service scores, and payment methods. Data preprocessing involved handling missing values, removing duplicates, and feature engineering to ensure data quality for model training.

## Exploratory Data Analysis (EDA)
We conducted a comprehensive EDA to understand the factors contributing to churn. Key findings include:
- High churn rates among new customers.
- Significant impact of customer service interactions on churn likelihood.
- Variations in churn rates across different payment methods and customer demographics.

## Model Building
We employed various machine learning models including Logistic Regression, XGBoost, and Random Forest. The XGBoost model was tuned to optimize for precision and recall, proving to be the most effective in predicting churn.

### Model Comparison
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 85% | 80% | 78% | 79% |
| Random Forest | 88% | 83% | 85% | 84% |
| **XGBoost** | **92%** | **90%** | **91%** | **90.5%** |

## Model Performance
The final model achieved a recall of 91%, helping us to accurately identify potential churners. The model's performance insights are crucial for implementing effective customer retention strategies.

## Business Insights and Recommendations
- **Enhance Customer Onboarding:** Improving the initial customer experience to reduce early churn.
- **Optimize Customer Service:** Tailoring customer service efforts based on individual service scores and feedback.
- **Customized Retention Offers:** Using predictive insights to offer customized retention plans that address specific customer needs.

