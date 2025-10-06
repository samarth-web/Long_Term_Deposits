Predicting Term Deposit Subscription using XGBoost
Overview

This project uses XGBoost to predict whether a banking customer will subscribe to a long-term deposit based on marketing campaign data.
The work demonstrates how data analytics can guide customer targeting and improve marketing efficiency.

Objective

Build a classification model to predict client subscription (yes/no).

Identify the most influential features.

Provide business insights to improve marketing strategy.

Dataset

Source: Kaggle – Banking Dataset Classification

Rows: ~32,000

Features: 20

Target: y (subscription outcome)

Tools

Python, pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost
Environment: Google Colab / Jupyter Notebook

Method

Cleaned and encoded categorical data.

Trained an XGBoost classifier with tuned parameters.

Evaluated performance using accuracy, precision, recall, and confusion matrix.

Analyzed feature importance to extract insights.

Key Results

Most important features: pdays, duration, contact, month, default.

Recent and longer client interactions strongly increase subscription likelihood.

Contact method and timing significantly influence campaign success.

Demographics had limited predictive power.

Business Insight

Target recently contacted customers, prioritize meaningful call interactions, and schedule campaigns in high-performing months to improve deposit conversion.
