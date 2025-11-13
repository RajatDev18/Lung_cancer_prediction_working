# Lung Cancer Survival Prediction

Predicting patient survival using medical diagnosis data

## Overview

This project builds a machine learning model to predict the survival status of lung cancer patients based on medical, demographic, and lifestyle information. The system helps identify important factors influencing mortality and can support early diagnosis, treatment planning, and risk stratification.

## Objective

Analyze patient diagnosis data to understand key predictors of lung cancer survival.

Build and evaluate multiple machine learning models.

Identify the best model and important features using EDA and feature importance techniques.

Provide insights for healthcare research and early decision-making.

## Project Workflow
### 1. Data Preprocessing

Handling missing values

Encoding categorical variables

Date feature transformation

Outlier detection

Feature engineering (e.g., treatment duration)

### 2. Exploratory Data Analysis (EDA)

Smoking vs. survival rate

Age distribution patterns

Cancer stage influence

Comorbidity correlations (hypertension, asthma, cirrhosis)

### 3. Modeling

Machine learning algorithms used:

Logistic Regression

Random Forest

Gradient Boosting / XGBoost

Decision Trees

Evaluation metrics include:

Accuracy

Precision, Recall, F1-score

ROC–AUC

Confusion Matrix

### 4. Feature Importance

Identifying which features most strongly influence survival predictions.

### Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

## Results

Multiple models were trained and compared

Identified strongest predictors (e.g., cancer stage, smoking status, age)

Ensemble models provided the best performance

## Future Enhancements

Deploying the model using Streamlit or Flask

Adding SHAP explainability

Hyperparameter tuning

Predicting survival duration instead of binary outcome
