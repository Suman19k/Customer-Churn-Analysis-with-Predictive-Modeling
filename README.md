# 📊 Customer Churn Analysis & Prediction

## 📌 Overview
This project focuses on analyzing customer churn data and building a predictive model to identify customers likely to leave a service. The goal is to uncover key business insights and support data-driven decision-making for customer retention.

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn

---

## 📂 Dataset
- Telco Customer Churn Dataset (~7,000+ records)
- Features include customer demographics, services, billing details, and churn status

---

## 🔍 Key Steps Performed

### 1. Data Cleaning
- Removed irrelevant columns (customerID)
- Handled missing values in `TotalCharges`
- Converted data types and filtered invalid records

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn distribution across different features
- Studied impact of:
  - Contract type
  - Payment method
  - Monthly charges
  - Tenure

### 3. Feature Engineering
- Encoded categorical variables using Label Encoding
- Prepared dataset for machine learning models

### 4. Model Building
- Built a Logistic Regression model for churn prediction
- Evaluated performance using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

## 📈 Key Insights
- Customers with **month-to-month contracts** have the highest churn rate  
- Higher **monthly charges** increase churn probability  
- Customers with **longer tenure** are less likely to churn  
- Lack of **tech support and online security** leads to higher churn  

---

## 💡 Business Recommendations
- Promote **long-term contracts** to reduce churn  
- Offer **discounts or retention plans** to high-paying customers  
- Improve **customer support services**  

---

## 📊 Model Performance
- Logistic Regression Accuracy: **~79%**
- Balanced performance across precision and recall

---

## 🚀 Conclusion
This project demonstrates how data analysis and machine learning can be used together to extract meaningful insights and support business decisions aimed at reducing customer churn.

---

## 📎 Future Improvements
- Try advanced models (Random Forest, XGBoost)
- Perform feature selection for better accuracy
- Deploy model using Streamlit or Flask

---

## 👤 Author
**Suman Raj**
