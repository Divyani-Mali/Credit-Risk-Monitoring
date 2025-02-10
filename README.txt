Credit Risk Monitoring Using Machine Learning
📌 Project Overview
Credit risk assessment is crucial for banks to determine the likelihood of a customer defaulting on a loan. This project leverages machine learning to classify bank customers into different credit risk levels based on their financial behavior and transaction history.

⚠️ Problem Statement
Banks and financial institutions often struggle to identify high-risk customers who may default on loans. Traditional methods are:

Time-consuming ⏳
Less accurate in predicting future risks 📉
Inefficient in handling large-scale data 📊
To solve this, we developed a machine learning-based credit risk classification system to automate and improve risk assessment.

✅ Proposed Solution
Our solution classifies customers into four credit risk categories using banking transaction data and financial indicators:

🟢 p1 (Low Risk) → Safe customers with a good financial history
🟡 p2 (Moderate Risk) → Customers with minor financial instability
🟠 p3 (High Risk) → Customers with a significant risk of default
🔴 p4 (Very High Risk) → Customers highly likely to default
How It Works?
Data Preprocessing: Cleaning and handling missing values
Feature Engineering: Selecting key financial indicators
Model Training: Using Random Forest, XGBoost, and Decision Tree Classifiers
Evaluation & Optimization: Improving accuracy, precision, recall, and F1-score
🔍 Key Insights
Customers with irregular payments, low income, or high loan amounts were more likely to be in p3 or p4 categories.
Transaction frequency and stability were key indicators of creditworthiness.
Feature selection techniques (ANOVA, Chi-square tests) improved model performance.
Random Forest & XGBoost provided the best accuracy in predicting credit risk.


