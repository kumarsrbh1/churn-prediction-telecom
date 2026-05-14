# 📊 Customer Churn Prediction – Telecom

## 🎯 Project Overview
Build a machine learning model to predict customer churn and identify high-risk customers in a telecom company.


---

## 📊 Business Problem

- Telecom company loses ~25% customers annually  
- Customer acquisition cost is 5× higher than retention  
- Goal: Predict churn early to improve retention  

---

## 🗂️ Dataset

📥 **Download Dataset:**  
👉 https://www.kaggle.com/datasets/blastchar/telco-customer-churn  

- 7,043 customers  
- 21 features  

---

## ⚙️ Project Workflow

- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Building (XGBoost)  
- Model Evaluation  

---

# 📷 Model Output

---

## 🔹 Customer Churn Distribution

![Churn Distribution](images/churn.png)

---

## 🔹 Feature Importance (Top Drivers of Churn)

![Feature Importance](images/feature_importance.png)

---

## 🤖 Model Used

- ✅ XGBoost Classifier  
- Handles non-linear relationships  
- Works well with structured/tabular data  

---

## 📊 Model Performance


- Accuracy: **80.5%**

### Classification Report:

| Class | Precision | Recall | F1 Score |
|------|----------|--------|----------|
| 0 (Non-churn) | 0.84 | 0.90 | 0.87 |
| 1 (Churn)     | 0.66 | 0.54 | 0.59 |


---

## 🔍 Key Insights

- Customers with **month-to-month contracts** churn more  
- Customers with **high monthly charges** are high risk  
- **New customers (low tenure)** are most likely to churn  
- Customers without **security services** tend to leave  

---

## 💡 Business Recommendations

- Offer retention plans to high-risk customers  
- Encourage long-term contracts  
- Improve onboarding for new customers  
- Bundle value-added services  

---

## 📂 Project Structure

``
