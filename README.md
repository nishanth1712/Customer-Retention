
# Customer Retention Analytics

## Overview
This project aims to predict customer churn for a telecom company using machine learning techniques. It explores customer demographics, account information, and usage patterns to identify key factors influencing churn.

## Features
- Data preprocessing: Handling missing values, encoding categorical variables, scaling numerical features.
- Exploratory Data Analysis (EDA): Visualization of churn patterns and key metrics.
- Model Training: Logistic Regression and Random Forest classifiers.
- Model Evaluation: Accuracy scores, confusion matrices, and feature importance visualization.

## Dataset
The dataset is sourced from the Kaggle [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn).

## How to Run
1. Clone this repository.
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python script:
   ```bash
   python customer_retention_analysis.py
   ```

## Results
- Logistic Regression Accuracy: ~80%
- Random Forest Accuracy: ~78%

## Visualizations
- Confusion matrices for both models.
- Feature importance plot for the Random Forest model.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn
