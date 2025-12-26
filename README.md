# FUTURE_ML_02

# Project Title: Telco Customer Churn Prediction and Power BI Analytics Dashboard

# Project Description:
This project combines machine learning-based churn prediction with a Power BI
business analytics dashboard to identify at-risk customers, analyze churn behavior,
and support data-driven retention strategies.

# Objectives:
- Predict customer churn using statistical and ensemble ML models
- Classify customers into High / Medium / Low churn-risk categories
- Visualize churn behavior across demographics, services, and contracts
- Provide interactive insights for business decision-making

# Technologies Used:
- Python, Pandas, NumPy
- Scikit-learn, Logistic Regression, Random Forest
- Matplotlib
- Power BI (DAX Measures, Visual Analytics)
- CSV-based output integration


# Machine Learning Pipeline (Python Workflow)

1. Load Telco Customer Churn dataset
2. Drop unnecessary columns (customerID)
3. Convert TotalCharges to numeric and handle missing values
4. Encode categorical features using Label Encoding
5. Split dataset into train and test sets
6. Train Logistic Regression model with class_weight="balanced"
7. Predict churn probability and generate classification metrics
8. Plot ROC and Precision-Recall curves
9. Perform permutation-based feature importance analysis
10. Train Random Forest model for performance benchmarking
11. Generate churn-risk segmentation file:
   - High Risk (prob > 0.7)
   - Medium Risk (prob > 0.4)
   - Low Risk (prob <= 0.4)
12. Export output file: customer_churn_risk.csv

# Model Evaluation Metrics:
- Accuracy
- Recall (priority for churn capture)
- ROC-AUC
- Confusion Matrix
- Classification Report

# Business Output (ML Layer):
- Customer-level churn probability scoring
- Risk segmentation labels
- Factors influencing churn behavior

# Key Observed Patterns:
- Month-to-month contracts show higher churn probability
- Short tenure customers churn more frequently
- Electronic payment users churn at higher rates
- Fiber optic customers churn more compared to DSL users

# Power BI Churn Analytics Dashboard (Business Layer)
# Dataset Source:
- Same processed dataset used in machine learning pipeline
- Integrated with exported churn probability outputs

# Power BI Workflow:
1. Import cleaned churn dataset into Power BI
2. Validate data types and categorical fields
3. Create churn metrics using DAX Measures
4. Build interactive visual dashboards for churn insights
5. Add slicers to enable multi-dimensional exploration

# Key Measures:
- Churn Count
- Total Customers
- Churn Rate (%)
- Segmented churn comparison across attributes

# Example Churn Rate Measure:
Churn Rate % = DIVIDE(COUNTROWS(Churned_Customers), COUNTROWS(All_Customers))

# Dashboard Visuals:
- Card Visual → Overall Churn Rate %
- Column Chart → Churn by Contract Type
- Column Chart → Churn by Payment Method
- Line Chart → Churn vs Customer Tenure
- Column Chart → Churn by Gender
- Column Chart → Churn by Internet Service Type
- Bar Chart → Overall Churn Distribution by Category
- Slicers → Contract, Payment Method, Gender, Internet Service

# Insights Delivered:
- Short-term contracts strongly correlate with churn risk
- Fiber optic customers show higher churn variance
- Longer tenure reduces churn probability
- Payment mode influences churn behavior

# Business Value:
- Enables proactive customer retention strategy
- Identifies high-risk customer segments
- Supports pricing and contract policy optimization
- Bridges ML predictions with real-world business analytics

# Future Enhancements:
- SMOTE for class imbalance improvement
- XGBoost and Gradient Boosted Trees comparison
- SHAP-based interpretability layer
- Deploy model with Streamlit or Flask
- Power BI integration with live model scoring API


  <img width="1566" height="315" alt="image" src="https://github.com/user-attachments/assets/aa16db73-eded-4781-b9d3-bf74b0c3880b" />
  <img width="764" height="491" alt="image" src="https://github.com/user-attachments/assets/05fadd43-2a15-4d2b-a415-f7c294b13bb4" />
  <img width="843" height="662" alt="image" src="https://github.com/user-attachments/assets/5f45689f-1417-4cc6-8f50-dac99acc1fd7" />
  <img width="843" height="664" alt="image" src="https://github.com/user-attachments/assets/4249fd17-6674-4f78-8ff4-13081dab41b1" />
  <img width="1120" height="705" alt="image" src="https://github.com/user-attachments/assets/a15f70f4-b359-4200-98ee-db93018ec676" />
  <img width="958" height="539" alt="image" src="https://github.com/user-attachments/assets/e6bfd783-0c77-4918-b8c6-ee743aa50bb7" />
  <img width="952" height="541" alt="image" src="https://github.com/user-attachments/assets/7df9cfe2-f1b9-41d1-89fd-f283688197f4" />
  <img width="960" height="536" alt="image" src="https://github.com/user-attachments/assets/2d56c68b-1b5e-4f92-b9e2-212125f424d5" />






