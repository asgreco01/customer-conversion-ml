# Customer Conversion Prediction

## Project Goal
The goal of this project is to predict whether a customer will convert (make a purchase) based on marketing campaign data. This helps businesses optimize targeting and improve ROI.

## Dataset
The dataset contains information about customers, including:

- Demographics (age, income, etc.)
- Marketing interactions (email clicks, website visits)
- Previous purchases

Target variable:
- `conversion` (1 = converted, 0 = not converted)

## Machine Learning Workflow

1. Data Loading
2. Train/Test Split
3. Preprocessing (scaling, encoding with ColumnTransformer)
4. Pipeline Construction
5. Feature Selection (SelectKBest)
6. Hyperparameter Tuning (GridSearchCV)
7. Model Evaluation

## Models Used

- Logistic Regression
- Random Forest Classifier

We started with Logistic Regression as an interpretable baseline and then compared it with Random Forest to evaluate whether a more flexible model could improve predictive performance.

## Scenario
This project simulates a real-world marketing analytics case in which an e-commerce company wants to predict which customers are most likely to convert after interacting with a campaign. The workflow includes preprocessing, feature selection, model tuning, and business-oriented interpretation of results.

## Results
Logistic Regression Accuracy: 71.1%
Random Forest Accuracy: 67.0%
Best Model: Logistic Regression
ROC-AUC Score: 75.9

The Logistic Regression model improved performance by capturing non-linear relationships in customer behavior.

## Key Insights
Customers with higher engagement (clicks, visits) are more likely to convert
Previous purchase behavior is a strong predictor of conversion
Certain demographic segments show higher conversion probability

These insights can help marketing teams focus campaigns on high-value customers.

## Business Impact

This model can help companies:

Improve targeting of marketing campaigns
Reduce wasted advertising spend
Increase overall conversion rates and ROI

Note: The dataset is not included in this repository. Any marketing conversion dataset with similar features can be used to reproduce the results.
