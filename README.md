# House Price Prediction Using Linear Regression

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## Project Overview

This project focuses on predicting house prices using Machine Learning techniques. A Linear Regression model was developed by performing data preprocessing, exploratory data analysis (EDA), feature selection, and model evaluation.

The objective of this project is to build a reliable regression model that can accurately predict house prices based on various housing-related features.

---

## Dataset

The dataset contains multiple housing-related features such as:

- Property characteristics
- Area measurements
- Construction details
- Location-based information
- House condition and quality features

After preprocessing and feature selection, 54 relevant features were used for model development.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Project Workflow

### 1. Data Loading and Understanding
- Dataset inspection
- Data type analysis
- Missing value identification

### 2. Data Cleaning and Preprocessing
- Missing value treatment
- Duplicate value checking
- Data preparation

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis
- Correlation analysis
- Data visualization

### 4. Outlier Detection and Treatment
- Identification of extreme values
- Outlier handling using statistical methods

### 5. Feature Engineering
- Skewness analysis
- Feature transformation
- One-Hot Encoding of categorical variables

### 6. Feature Selection
- Correlation-based feature selection
- Selection of relevant predictors

### 7. Model Development
- Train-Test Split
- Linear Regression Model Training

### 8. Model Evaluation
- R² Score
- Adjusted R² Score
- Residual Analysis
- Actual vs Predicted Analysis

---

## Model Performance

| Metric | Score |
|----------|----------|
| R² Score | 89% |
| Adjusted R² Score | 87.45% |

---

## Model Validation

### Actual vs Predicted Analysis

An Actual vs Predicted scatter plot was generated to compare model predictions with actual house prices. Most observations follow a strong positive linear trend, indicating good predictive performance.

### Residual Analysis

Residual distribution was analyzed to evaluate prediction errors. The residuals are centered around zero and approximately follow a normal distribution, suggesting that the model captures the underlying relationship effectively without significant systematic bias.

---

## Key Learnings

- Importance of data preprocessing
- Impact of feature selection on model performance
- Understanding regression evaluation metrics
- Practical implementation of Linear Regression
- Residual analysis and model validation techniques

---

## Future Improvements

- Ridge Regression
- Lasso Regression
- Cross Validation
- Random Forest Regressor
- XGBoost Regressor
- Streamlit Deployment

---

## Author

**Jayesh Pardeshi**

AI & Data Science Student
