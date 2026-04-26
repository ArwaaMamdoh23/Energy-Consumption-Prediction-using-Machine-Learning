# Energy Consumption Prediction using Machine Learning

## Overview
This project builds a machine learning pipeline to predict electricity consumption  using multiple regression models.

It includes data preprocessing, feature engineering, model training, evaluation, and hyperparameter tuning.

---

## Dataset
The dataset contains energy consumption data with features such as:
- Power factors
- Reactive power
- CO2 emissions
- Time-based features (year, month, day)
- Load type and week status

---

## Workflow

### 1. Data Preprocessing
- Converted date into year, month, day  
- Handled missing values (mean & mode)  
- Removed duplicates  
- Detected and handled outliers using IQR  
- Encoded categorical features (Label Encoding & One-Hot Encoding)  

### 2. Models Used
- Linear Regression  
- Polynomial Regression  
- Ridge Regression  
- Lasso Regression  

### 3. Model Evaluation
- Mean Squared Error (MSE)  
- R² Score  
- K-Fold Cross Validation  
- Learning Curves  

### 4. Hyperparameter Tuning
- Tuned Lasso Regression using different alpha values  
- Selected best model based on validation performance  

---

## Key Highlights
- Implemented K-Fold Cross Validation for robust model evaluation  
- Compared multiple regression models including Linear, Polynomial, Ridge, and Lasso  
- Applied hyperparameter tuning to optimize model performance and reduce error  

---

## Author
Arwaa Mamdoh
