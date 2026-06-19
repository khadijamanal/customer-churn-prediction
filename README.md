# customer-churn-prediction
Built an end-to-end machine learning pipeline for customer churn prediction using the Telco Customer Churn dataset. Implemented data preprocessing, feature scaling, categorical encoding, model training (Logistic Regression and Random Forest), hyperparameter tuning with GridSearchCV, and model export using Joblib.
# Customer Churn Prediction using Scikit-learn Pipeline

## Overview
This project implements an end-to-end machine learning pipeline to predict customer churn using the Telco Customer Churn dataset. The pipeline automates data preprocessing, feature transformation, model training, hyperparameter tuning, evaluation, and model export.

## Dataset
- Dataset: Telco Customer Churn Dataset
- File: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

## Features
- Data cleaning and preprocessing
- Handling missing values
- Feature scaling with StandardScaler
- Categorical encoding with OneHotEncoder
- Automated preprocessing using ColumnTransformer
- Logistic Regression model
- Random Forest Classifier model
- Hyperparameter tuning using GridSearchCV
- Model evaluation
- Pipeline export using Joblib

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Workflow
1. Load and clean the dataset.
2. Split features and target variable.
3. Apply preprocessing using Scikit-learn Pipeline.
4. Train machine learning models.
5. Perform hyperparameter tuning with GridSearchCV.
6. Evaluate model performance.
7. Save the best model pipeline.

## Output
The trained machine learning pipeline is exported as:

```text
churn_pipeline.pkl
```

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Place the dataset file in the project directory.
4. Run the Jupyter Notebook.

