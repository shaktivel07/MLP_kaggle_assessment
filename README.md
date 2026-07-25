#  Flight Ticket Price Prediction


> An end-to-end machine learning workflow for predicting airline ticket prices using regression models, developed as part of the **Machine Learning Practice (MLP)** course in the **IIT Madras BS Degree in Data Science and Applications**.

---

## Overview

This repository contains my submission for the **Machine Learning Practice (MLP)** course, a **4-credit** course in the IIT Madras BS Degree program.

Building upon the concepts learned in:

- Machine Learning Foundations (MLF)
- Machine Learning Techniques (MLT)

this assessment focuses on solving a real-world regression problem while following a structured and reproducible machine learning pipeline.

Rather than emphasizing only predictive performance, the assessment demonstrates the complete workflow expected in practical machine learning projects—from data understanding to model evaluation and final deployment-ready predictions.

---

## Problem Statement

Develop a machine learning model capable of predicting airline ticket prices based on flight-related attributes such as airline, source, destination, departure and arrival timings, travel duration, number of stops, travel class, and booking information.

---

# Workflow

The notebook is organized into sixteen well-defined stages:

1. Setup & Data Loading
2. Dataset Understanding
3. Descriptive Statistics
4. Missing Value Analysis
5. Duplicate Detection
6. Outlier Analysis
7. Exploratory Data Analysis (EDA)
8. Feature Engineering
9. Data Preprocessing
10. Model Building
11. Hyperparameter Tuning
12. Model Comparison
13. Final Model Training
14. Kaggle Submission Generation
15. Feature Importance Analysis
16. Conclusion

---

# Features Implemented

## Data Analysis

- Dataset exploration
- Data type inspection
- Statistical summaries
- Missing value analysis
- Duplicate detection
- IQR-based outlier detection
- Outlier retention justification

---

## Exploratory Data Analysis

Visualizations include:

- Target distribution
- Price by travel class
- Price by airline
- Correlation heatmap
- Booking days vs. ticket price
- Flight stop distribution

Each visualization is accompanied by detailed observations and business insights.

---

## Feature Engineering

Feature engineering includes:

- Removal of unnecessary columns
- Creation of model-ready features
- Consistent preprocessing for both training and testing datasets

---

## Data Preprocessing

Implemented using Scikit-learn Pipelines.

Components include:

- Missing value imputation
- One-Hot Encoding
- Feature Scaling
- ColumnTransformer
- End-to-end preprocessing pipeline
- Polynomial feature preprocessing for linear models

---

# Machine Learning Models

The notebook trains and evaluates **nine regression models**, including:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net
- Decision Tree Regressor
- Random Forest Regressor
- Extra Trees Regressor
- Gradient Boosting Regressor
- HistGradientBoosting Regressor

All models are evaluated using **5-fold Cross Validation**.

Performance metrics include:

- R² Score
- Root Mean Squared Error (RMSE)

---

# Hyperparameter Optimization

Hyperparameter tuning is performed using:

- GridSearchCV
- RandomizedSearchCV

The tuned models are compared against baseline models to identify the best-performing estimator.

---

# Final Model

The best-performing model is:

- Retrained using the complete training dataset
- Used to generate predictions on unseen test data
- Exported as a Kaggle-compatible submission file

---

# Model Explainability

To better understand model behavior, the notebook includes:

- Feature Importance Analysis
- Permutation Importance

These techniques help identify the most influential variables affecting ticket prices.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Repository Structure

```
Flight-Ticket-Price-Prediction/
│
├── notebook.ipynb
├── README.md
```

---

# Learning Outcomes

This assessment provided hands-on experience in:

- Building complete machine learning pipelines
- Exploratory Data Analysis
- Feature Engineering
- Data Preprocessing
- Cross Validation
- Regression Algorithms
- Hyperparameter Optimization
- Model Comparison
- Explainable Machine Learning
- Generating competition-ready predictions

---

# Academic Information

**Program**
> IIT Madras BS Degree in Data Science and Applications

**Course**
> Machine Learning Practice (MLP)



---

# Disclaimer

This repository represents my individual submission for an academic assessment conducted as part of the IIT Madras BS Degree in Data Science and Applications. It is shared for educational and portfolio purposes only.

---

## Author

**Shakthivel T K**
- BS Degree in Data Science and Applications, IIT Madras

GitHub: https://github.com/shaktivel07
