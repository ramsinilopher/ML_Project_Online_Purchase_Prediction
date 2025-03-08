# ML_Project_Online_Purchase_Prediction

Online Shopper Intention Prediction

Overview

This project aims to predict whether an online shopper will make a purchase based on various behavioral and session-based features. The dataset consists of user interactions with an e-commerce website, including page visits, product-related attributes, and technical details.

Dataset

Source: UCI Machine Learning Repository

Features:

# 1. Administrative & Informational page visits

# 2. Product-related page visits

# 3. Page durations

# 4. Bounce rate & Exit rate

# 5. Special days & Weekend indicators

# 6. Traffic type & Visitor type

# 7. Region & Operating System

# 8. Revenue (Target variable: Yes/No for purchase intention)

## Project Workflow

# Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Outlier detection & handling (Winsorization applied)
* Handling skewness(Yeo-Johnson Transformation)
* Feature scaling & normalization



# Exploratory Data Analysis (EDA)

* Data visualization using Seaborn & Matplotlib

* Histogram & Boxplot analysis

* Feature correlation analysis

# Feature Engineering

* Selecting important features using correlation & statistical tests

# Model Training & Evaluation

# Algorithms Used:

# 1. Logistic Regression

# 2.   Decision Tree

# 3. Random Forest

# 4. Support Vector Machine (SVM)

# 5. Gradient Boosting

# 6. XGBoost



# Model evaluation metrics:

Accuracy, Precision, Recall, F1-score


# Hyperparameter Tuning

GridSearchCV for optimization

Model Deployment

Saving the trained model using joblib


Results

Best-performing model: [XGBoost]

Accuracy achieved: [89.10]%

Key insights from the data:

This project demonstrates how to build a predictive model for online shopper behavior using machine learning techniques. The insights gained from this analysis can help e-commerce businesses enhance their marketing strategies and improve user engagement.
