# E-Commerce Revenue Prediction — Linear Regression

Project Overview

This project analyzes purchase behavior in an online retail setting where customers first receive in-store styling sessions and later place their orders through either the mobile app or the website. The business objective is to determine which digital channel has a stronger influence on revenue so the company can prioritize product development, UX enhancements, and marketing investment.

Business Problem

The company needs clarity on:

Whether mobile app or website engagement contributes more to revenue.
Which engagement metrics are the strongest predictors of customer spend.
How classical regression modeling can support strategic decision-making for digital channel optimization.

Dataset

The dataset contains customer behavior and transaction features, including:
Time spent on the mobile app
Time spent on the website
Average session length
Length of membership

If the dataset cannot be shared publicly due to confidentiality, it has been excluded from this repository.

Approach

The project follows a structured workflow:

Data loading and inspection
Cleaning and handling missing values
Exploratory data analysis
Feature selection and engineering
Multiple linear regression modeling using scikit-learn
Model evaluation and interpretation
Business insights and conclusions

Model Development

A multiple linear regression model was implemented in Python.
Key steps included:

Train–test splitting
Fitting the regression model
Checking assumptions such as residual distribution and multicollinearity
Generating evaluation metrics (R², MAE, RMSE)

Evaluation Metrics

The model was assessed using:

R²: Measures the percentage of variance explained
MAE: Average magnitude of prediction error
RMSE: Penalizes larger errors more strongly

Residual and diagnostic plots were also generated to validate model assumptions.

Key Insights

Engagement on the mobile app showed a stronger positive relationship with revenue than website usage.
Improving the mobile experience may yield higher short-term ROI in terms of customer spending.
Classical regression still provides clear interpretability and reliable direction when combined with proper feature validation.

Tools & Technologies:

Python
Pandas
NumPy
Matplotlib
Seaborn
scikit-learn
statsmodels

Jupyter/Colab Notebook
