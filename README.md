# Churnify 
### Smart Customer Churn Prediction System

Churnify is an end-to-end machine learning project that predicts whether a customer is likely to churn (leave the service) based on historical customer data. The system helps businesses identify high-risk customers and take proactive retention measures.

---

## Problem Statement
Customer churn directly impacts revenue and growth. The objective of Churnify is to analyze customer behavior and build a predictive model that accurately identifies customers who are likely to leave.

---

## Project Objectives
- Analyze customer data and identify churn patterns
- Perform Exploratory Data Analysis (EDA) for business insights
- Build and evaluate machine learning models
- Predict churn for new/unseen customers
- Create a reusable and production-ready ML pipeline

---

## Dataset Overview
- **Records:** 10,000 customers  
- **Features:** 12  
- **Target Variable:** `churn`  
  - `0` → Customer stays  
  - `1` → Customer churns  

### Key Features:
- Credit Score  
- Country  
- Gender  
- Age  
- Tenure  
- Account Balance  
- Number of Products  
- Credit Card Ownership  
- Active Member Status  
- Estimated Salary  

---

## Exploratory Data Analysis (EDA)
- Churn distribution analysis
- Active vs inactive members comparison
- Country-wise churn trends
- Correlation heatmap for numeric features

### Key Insight:
Inactive members and older customers show a higher tendency to churn.

---

## Machine Learning Workflow
1. Data Cleaning & Preprocessing  
2. Encoding categorical variables  
3. Feature selection  
4. Train-test split  
5. Model training and comparison  
6. Model evaluation using performance metrics  
7. Pipeline creation and model saving  

---

## Models Used
- Logistic Regression  
- Random Forest Classifier  

The best-performing model was selected based on **recall, precision, and overall performance** and saved as a pipeline.

---

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- Confusion Matrix  

> Recall was prioritized to reduce missed churn predictions.

---

## Predicting New Customers
Churnify allows prediction for new customer data by passing features into the trained pipeline, making it suitable for real-world deployment.

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Project Structure
Churnify/
│── Analysis.ipynb
│── customer_data.csv
│── best_churn_pipeline.pkl
│── README.md


---

## Results & Conclusion
Churnify successfully identifies customers at risk of churn and provides actionable insights for retention strategies. The project demonstrates a complete machine learning lifecycle from data analysis to prediction.

---

## Future Enhancements
- Deploy using Streamlit or Flask
- Add deep learning models
- Handle class imbalance with advanced techniques
- Integrate with real-time customer data

---

## Author
**Sai Harshitha**  
Machine Learning & Data Analytics Enthusiast

---

If you like this project, don’t forget to star the repository!
