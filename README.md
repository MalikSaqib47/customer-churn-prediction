Customer Churn Prediction

This repository contains a Python-based machine learning project to predict customer churn using the Telco Customer Churn dataset, showcasing my skills in data analysis and modeling.

Overview

Problem: Predict whether a customer will churn based on features like tenure, monthly charges, and service subscriptions.
Dataset: Telco-Customer-Churn.csv (publicly available from Kaggle/IBM, ~7,000 records).
Technologies: Python, pandas, seaborn, matplotlib, scikit-learn.
Models: Logistic Regression, Decision Tree, Random Forest.
Evaluation: Accuracy, classification reports, ROC curves.

How to Run

Clone the repo: git clone https://github.com/MalikSaqib47/customer-churn-prediction.git
Install dependencies: pip install -r requirements.txt
Open the notebook: jupyter notebook customer_churn_pred.ipynb

Results

Performed exploratory data analysis (EDA) to identify churn patterns (e.g., higher churn with shorter tenure and higher monthly charges).
Compared three models, with Logistic Regression achieving the highest accuracy (85%) and AUC (0.85).
Visualizations: Churn distribution, tenure vs. churn boxplot, ROC curves, top 10 feature importance from Random Forest.

Files

customer_churn_pred.ipynb: Jupyter Notebook with full analysis, modeling, and visualizations.
Telco-Customer-Churn.csv: Dataset with customer details.
requirements.txt: List of Python dependencies for reproducibility.

License
MIT License
