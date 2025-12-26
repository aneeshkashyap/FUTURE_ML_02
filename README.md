# FUTURE_ML_02

Project Title: Telco Customer Churn Prediction

Description:
This project focuses on predicting customer churn using machine learning techniques.
The workflow includes data preprocessing, feature encoding, model training, model evaluation,
risk segmentation, and feature importance analysis.

Objectives:
- Predict whether a customer will churn based on historical data
- Classify customers into High, Medium, and Low churn-risk categories
- Identify key drivers influencing churn
- Compare Logistic Regression and Random Forest performance

Technologies Used:
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Permutation Importance (Explainability)

Project Workflow:
1. Load dataset and remove unwanted columns
2. Convert TotalCharges to numeric and handle missing values
3. Encode categorical features using Label Encoding
4. Split dataset into training and testing sets
5. Train Logistic Regression model with class balancing
6. Predict churn probability for customers
7. Generate churn-risk segmentation file (High / Medium / Low risk)
8. Evaluate model using Accuracy, Recall, ROC-AUC
9. Plot ROC and Precision-Recall curves
10. Perform Feature Importance analysis using Permutation Importance
11. Train Random Forest for model comparison

Business Output:
- Exported file: customer_churn_risk.csv
- Contains churn probability and risk category for each customer

Key Insights (observed trends):
- Month-to-month contracts show higher churn probability
- Electronic payment users churn more frequently
- Longer customer tenure reduces churn risk
- Fiber optic users have higher churn compared to DSL users

Future Enhancements:
- Apply SMOTE for class imbalance handling
- Add XGBoost model comparison
- Implement SHAP for deeper interpretability
- Deploy the model using Streamlit dashboard
