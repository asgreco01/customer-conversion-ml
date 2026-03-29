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
- Decision Tree Classifier
- Random Forest Classifier
