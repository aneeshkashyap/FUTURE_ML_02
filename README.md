# FUTURE_ML_02

# Project Title: Telco Customer Churn Prediction

# Description:
This project focuses on predicting customer churn using machine learning techniques.
The workflow includes data preprocessing, feature encoding, model training, model evaluation,
risk segmentation, and feature importance analysis.

# Objectives:
- Predict whether a customer will churn based on historical data
- Classify customers into High, Medium, and Low churn-risk categories
- Identify key drivers influencing churn
- Compare Logistic Regression and Random Forest performance

# Technologies Used:
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Permutation Importance (Explainability)

# Project Workflow:
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

# Business Output:
- Exported file: customer_churn_risk.csv
- Contains churn probability and risk category for each customer

# Key Insights (observed trends):
- Month-to-month contracts show higher churn probability
- Electronic payment users churn more frequently
- Longer customer tenure reduces churn risk
- Fiber optic users have higher churn compared to DSL users

# Future Enhancements:
- Apply SMOTE for class imbalance handling
- Add XGBoost model comparison
- Implement SHAP for deeper interpretability
- Deploy the model using Streamlit dashboard

  <img width="1566" height="315" alt="image" src="https://github.com/user-attachments/assets/aa16db73-eded-4781-b9d3-bf74b0c3880b" />
  <img width="764" height="491" alt="image" src="https://github.com/user-attachments/assets/05fadd43-2a15-4d2b-a415-f7c294b13bb4" />
  <img width="843" height="662" alt="image" src="https://github.com/user-attachments/assets/5f45689f-1417-4cc6-8f50-dac99acc1fd7" />
  <img width="843" height="664" alt="image" src="https://github.com/user-attachments/assets/4249fd17-6674-4f78-8ff4-13081dab41b1" />
  <img width="1120" height="705" alt="image" src="https://github.com/user-attachments/assets/a15f70f4-b359-4200-98ee-db93018ec676" />
  <img width="958" height="539" alt="image" src="https://github.com/user-attachments/assets/e6bfd783-0c77-4918-b8c6-ee743aa50bb7" />
  <img width="952" height="541" alt="image" src="https://github.com/user-attachments/assets/7df9cfe2-f1b9-41d1-89fd-f283688197f4" />
  <img width="960" height="536" alt="image" src="https://github.com/user-attachments/assets/2d56c68b-1b5e-4f92-b9e2-212125f424d5" />






