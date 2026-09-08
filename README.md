# Exploratory-Data-Analysis-EDA-and-Data-Visualization on “anonymized loan applications USA_ETL”
An Exploratory Data Analysis (EDA) and Data Visualization project on 5,000 anonymized US bank customer records to identify key drivers behind personal loan acceptance for targeted marketing strategies.

# Description 
This is Bank Customer Dataset for Personal Loan Prediction. This dataset contains demographic, financial, and behavioral data of 5,000 bank customers collected during a marketing campaign aimed at offering personal loans.

The primary objective was to predict whether a customer accepted the personal loan offer (personal_loan), making this a supervised binary classification problem.



# Key Features & Workflow

Dataset: 5,000 rows, 14 demographic and financial features (Source: Mendeley Data, Abbas, 2025).

Data Preprocessing & Cleaning: Loaded CSV/Excel sources, evaluated missing values, removed duplicates, and validated categorical distributions.

Statistical Analysis: Analyzed central tendencies and feature distributions; verified zero severe outliers using IQR methods across categorical and binary features.

Exploratory Visualizations: Built univariate, bivariate, and multivariate visualizations (histograms, KDE plots, boxplots, pair plots, and custom visual charts).

# Core Data Insights

Strongest Loan Predictor: Income shows the highest positive correlation with Personal Loan acceptance (r=0.50), followed by average credit card spending (CCAvg, r=0.37) and holding a Certificate of Deposit (CD Account, r=0.32).

Spending Patterns: Income strongly correlates with credit card spending (CCAvg, r=0.65), confirming higher earners spend significantly more on credit.

Cross-Selling Potential: Customers with a CD Account demonstrate a moderate correlation (r=0.32) with holding a Securities Account.

Demographics: Near-perfect collinearity exists between Age and Experience (r≈0.99).
