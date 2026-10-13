# Customer Churn Analysis and Prediction

## Overview
This project analyzes customer churn using the Telco Customer Churn dataset. The goal is to understand customer behavior, identify factors associated with churn, and propose data-driven customer retention strategies.

## Objectives
- Clean and prepare customer data.
- Explore customer demographics, contracts, payment methods, and churn patterns.
- Segment customers using an RFM-style scoring approach.
- Train a Logistic Regression model to predict customer churn.
- Propose targeted customer retention strategies.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology
1. Data cleaning and preprocessing.
2. Exploratory data analysis and visualization.
3. Customer segmentation and churn analysis.
4. Model training and evaluation.
5. Business recommendations for customer retention.

## Results
The Logistic Regression baseline achieved an accuracy of 82.11% on the test set. Recall for customers who churned was 60%, with a precision of 68%.

These results provide a baseline for identifying customers at risk of leaving. Further improvements could focus on increasing churn recall and evaluating additional models.

## Business Recommendations
- Encourage customers to switch from monthly to longer-term contracts.
- Review pricing and retention offers for customers with high monthly charges.
- Investigate churn patterns among electronic-check users.
- Prioritize retention outreach for potentially high-value customers at risk.

## Dataset
Telco Customer Churn dataset. Add the original dataset source link here.

## How to Run
1. Clone this repository.
2. Install the dependencies listed in `requirements.txt`.
3. Open the notebook in Jupyter.
4. Run the notebook cells in order.