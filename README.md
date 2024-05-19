# SalesPrediction

# Sales Data Prediction

## Project Overview
This project seeks to enhance customer experience and loyalty by predicting the factors that influence customer arrivals and sales at stores. By understanding these factors, businesses can prevent customer turnover, optimize stock renewal, staff requirements, and overall improve the shopping experience. This analysis utilizes data mining techniques on the Walmart sales dataset to identify key variables impacting sales at different times of the month.

## Problem Setting
In the retail sector, customer retention is crucial as losing customers almost invariably leads to a revenue loss. This project addresses the uncertainty of customer retention by focusing on predicting the influential factors behind customer store visits and their purchase behaviors.

## Problem Definition
The challenge lies in predicting customer behavior without direct feedback, using historical sales data to unearth patterns and insights that could prevent customer loss and boost sales figures.

### Key Questions:
- What improvements can be made in customer service to enhance retention?
- How many sales representatives or employees are required at different times?
- Which inventory items need regular updates to ensure customer satisfaction?

## Data Source
The dataset is sourced from the publicly available [Walmart sales dataset on Kaggle](https://www.kaggle.com/datasets/varsharam/walmart-sales-dataset-of-45stores). It consists of 50,000 observations with attributes including sales data, customer price index, unemployment rates by store region, and holiday occurrences.

## Data Insights
- Replacement of missing values with the mean of respective variables.
- Detailed quarterly and annual sales overview.
- Analysis of holiday versus non-holiday sales impact.
- Examination of the correlation between sales and various data attributes like fuel prices and year.
- Seasonal sales trends and their outliers, especially in Q4.

## Model Exploration
Several predictive models are considered for this supervised classification task:
- Logistic Regression
- Decision Tree
- Support Vector Classifier (SVC)
- Random Forest
- K-Nearest Neighbors (KNN)
- Gradient Boosting
- XGBoost Classifier
- LightGBM Classifier
- Neural Networks using Keras

### Model Selection
The selection process involves evaluating models based on their performance on the original and oversampled datasets (using SMOTE for class balancing). The effectiveness of each model is assessed through confusion matrices and learning curves.

## Performance Evaluation
- **Linear Regression**: Used for predicting weekly sales with metrics like RMSE and MAE.
- **Logistic Regression**: Evaluated for classifying holiday sales with an AUC value of 0.52.
- **Random Forest Regressor**: Shows promising results for predicting weekly sales with high accuracy.

## Conclusion
The project concludes with recommendations for deploying logistic regression for holiday flag classification and Random Forest for predicting weekly sales, providing actionable insights for improving customer retention and sales performance.

