# 📊 Customer Churn Analysis for Telecom Industry

---

## 🔍 Overview  
This project focuses on predicting **customer churn** in the telecom industry using **machine learning** and **SQL-driven analytics**.  
By leveraging customer demographics, billing behavior, and service usage patterns, we built a **predictive model** to identify customers most likely to churn and provide **data-driven retention strategies**.

---

## 🎯 Objectives  
- 📈 Predict customers likely to churn using supervised ML techniques.  
- 🔑 Identify key churn-driving features using **SHAP** and **ELI5**.  
- 👥 Segment customers into **Loyal**, **At Risk**, and **Dormant** groups.  
- 🧩 Derive actionable business insights using **SQL analysis**.  
- 💡 Provide retention-focused recommendations based on model findings.  

---

## 🗃️ Dataset  
- **Records:** 7,043 telecom customer entries  
- **Features:** Demographics, billing, services, tenure, and churn labels  
- **Enhanced Synthetic Features:**
  - `complaints` → Customer complaints (0–4)  
  - `call_duration` → Average monthly call duration (50–500 mins)  
  - `recharge_frequency` → Monthly recharge frequency (1–10)  

---

## 🧠 Technologies Used  

| Tool / Library | Purpose |
|----------------|----------|
| **Python** | Data processing & ML modeling |
| **Pandas, NumPy** | Data manipulation |
| **Matplotlib, Seaborn** | Visualization |
| **Scikit-learn (Random Forest)** | Churn prediction |
| **SMOTE** | Handling class imbalance |
| **SHAP & ELI5** | Model explainability |
| **DuckDB / SQL** | Querying & segment-level analysis |
| **Google Colab / Jupyter Notebook** | Development & visualization |

---

## 🔧 Methodology  

1. **Data Preprocessing**  
   - Cleaned missing values and formatted numeric fields.  
   - Encoded categorical variables.  

2. **Feature Engineering**  
   - Created synthetic and domain-specific metrics (complaints, call duration, recharge frequency).  

3. **Model Training**  
   - Used **Random Forest Classifier** with **80/20 stratified split**.  
   - Handled imbalance using **SMOTE**.  

4. **Model Explainability**  
   - Used **SHAP** for feature impact visualization.  
   - Verified feature importance using **ELI5 permutation importance**.  

5. **Customer Segmentation (Churn Probability Based)**  
   - 🟢 **Loyal:** Probability < 0.3  
   - 🟡 **At Risk:** 0.3 – 0.7  
   - 🔴 **Dormant:** Probability > 0.7  

6. **SQL Analytics**  
   - Aggregated churned vs active users by `region`, `contract`, and `complaints`.  
   - Analyzed recharge patterns and call durations for each segment.  

---

## 📈 Outputs  

- ✅ **Classification Metrics** (Accuracy, Precision, Recall, F1-score)  
- 📊 **SHAP Summary Plot** – Visualizes top churn factors  
- 🔍 **ELI5 Feature Importance Table** – Explains model behavior  
- 🧩 **Segment-Level Dashboards** – Visual churn breakdown  
- 📝 **Reports & Presentations** – Final analysis and recommendations  

---

## 💡 Key Insights  

- **Tenure**, **MonthlyCharges**, and **Complaints** are the top churn indicators.  
- **Dormant** users show low call engagement and higher churn probability.  
- **Loyal** customers maintain longer tenure and fewer complaints.  
- **SQL analysis** validated that **high complaint volume** and **short call durations** are key red flags.  

---



## ✅ Outcome  

The developed **Customer Churn Prediction Framework** effectively identifies customers at risk of leaving.  
By combining **machine learning** and **SQL-based behavioral analysis**, it empowers telecom companies to:
- Detect churn early,  
- Implement proactive retention campaigns, and  
- Enhance overall customer lifetime value (CLV).  

---

## 👤 Author  
**Name:** Rama Lokesh Reddy Penumallu 
**Internship:** Data Analyst Internship – Elevate Labs  
**Duration:** October 2025  
**Tools Used:** Python | SQL | SHAP | ELI5 | Power BI  

---

## 🧩 Keywords  
`#CustomerChurn` `#DataAnalytics` `#MachineLearning` `#Python` `#SQL`  
`#Telecom` `#CustomerSegmentation` `#DataScience` `#ElevateLabs` `#Internship`

---
