# 🌟 Elevate Labs – Data Analyst Internship Projects  

---

## 🚀 Overview  

This repository contains a collection of projects completed as part of the **Data Analyst Internship at Elevate Labs**, showcasing analytical, visualization, and predictive modeling skills using **Python**, **SQL**, and **Power BI**.  

Each project focuses on solving a real-world business problem through **data-driven insights**, **machine learning**, and **interactive dashboards**.  

---

# 📊 Project 1 – Customer Churn Analysis for Telecom Industry  

## 🔍 Overview  
This project predicts **customer churn** in the telecom sector using **Machine Learning** and **SQL** analytics.  
It helps identify customers at risk of leaving and recommends actionable strategies to improve customer retention.  

---

### 🎯 Objectives  
- Predict customers likely to churn using supervised ML.  
- Identify key churn-driving factors using **SHAP** and **ELI5**.  
- Segment customers into **Loyal**, **At Risk**, and **Dormant**.  
- Derive insights using **SQL analysis** for targeted retention actions.  

---

### 🗃️ Dataset  
- **Records:** 7,043 telecom customer entries  
- **Features:** Demographics, billing, services, tenure, and churn labels  
- **Synthetic Enhancements:**
  - `complaints` → Customer complaints (0–4)  
  - `call_duration` → Avg. monthly call duration (50–500 mins)  
  - `recharge_frequency` → Monthly recharge frequency (1–10)  

---

### 🧠 Tools & Technologies  

| Tool | Purpose |
|------|----------|
| Python | Data Processing & ML Modeling |
| Pandas, NumPy | Data Manipulation |
| Matplotlib, Seaborn | Visualization |
| Scikit-learn | Random Forest Classification |
| SMOTE | Handle Class Imbalance |
| SHAP, ELI5 | Model Explainability |
| SQL / DuckDB | Querying & Churn Segment Analysis |
| Power BI | Dashboard & Reporting |

---

### 🔧 Methodology  
1. Data cleaning, encoding, and preprocessing.  
2. Synthetic feature creation (complaints, call duration, recharge frequency).  
3. Model training with **Random Forest** (80/20 split, SMOTE applied).  
4. Model interpretation with **SHAP** and **ELI5**.  
5. Customer segmentation based on churn probability:  
   - 🟢 **Loyal:** P < 0.3  
   - 🟡 **At Risk:** 0.3–0.7  
   - 🔴 **Dormant:** P > 0.7  
6. SQL-based analysis to explore churned vs active users and behavioral metrics.  

---

### 📈 Key Insights  
- **Tenure**, **MonthlyCharges**, and **Complaints** are major churn indicators.  
- **Dormant** users exhibit low call durations and high churn probability.  
- **Loyal** customers maintain long tenure and minimal complaints.  
- SQL confirms that **frequent complaints** and **short call durations** signal churn risk.  

---

### ✅ Outcome  
Developed a **Customer Churn Prediction Framework** that accurately identifies customers at risk, enabling telecom companies to:  
- Detect churn early,  
- Launch proactive retention campaigns, and  
- Enhance Customer Lifetime Value (CLV).  

---

### 👤 Author  
**Name:** Rama Lokesh Reddy Penumallu  
**Internship:** Data Analyst Internship – Elevate Labs  
**Duration:** October 2025  
**Tools Used:** Python | SQL | SHAP | ELI5 | Power BI  

---

# 🛒 Project 2 – E-commerce Return Rate Reduction Analysis  

### 🔍 Overview  
This project analyzes e-commerce product returns to identify patterns and causes behind product returns.  
The insights help reduce return rates and improve **customer satisfaction**.

---

### 🎯 Objectives  
- Understand reasons for product returns.  
- Identify categories and locations with high return rates.  
- Recommend strategies to reduce return volume.  

---

### 🧠 Tools & Techniques  
| Tool | Purpose |
|------|----------|
| Power BI | Dashboard and Visualization |
| Excel | Data preprocessing |
| Python (optional) | Data cleaning & feature engineering |

---

### 📁 Dataset  
**Name:** `ecommerce_returns_synthetic_data.csv`  
**Fields:** order_id, order_date, product_category, customer_segment, customer_location, return_reason  
**Engineered Fields:**  
- `return_flag` → 1 = Returned, 0 = Not Returned  
- `order_month` → Month-Year derived from `order_date`

---

### 📊 Dashboard Highlights  
- KPI Cards: Total Orders, Total Returns, Return Rate (%)  
- Visuals:  
  - Bar chart – Returns by Category  
  - Pie chart – Return Reasons  
  - Line chart – Monthly Trends  
  - Map – Geographic Return Distribution  

---

### 🔍 Insights  
- High return rates in specific categories and regions.  
- Top return reasons: Defective Items, Wrong Product, Quality Issues.  
- Seasonal spikes in return volumes.  

---

### ✅ Recommendations  
- Focus on quality improvements in high-return categories.  
- Improve packaging & logistics.  
- Enhance product descriptions and size guides.  
- Adjust return policies for high-return regions.  

---

### 📦 Deliverables  
- 📊 `E-commerce_Return_Rate_Analysis.pbix`  
- 📄 `E-commerce_Return_Rate_Analysis_Report.docx`  
- 📁 Dataset: `ecommerce_returns_synthetic_data.csv`  
- 🖼 Dashboard Screenshot  

---

# 💼 Project 3 – HR Analytics: Employee Attrition Dashboard  

### 🧾 Overview  
This project analyzes **employee attrition** patterns to identify which roles, departments, or conditions (like overtime) are most prone to resignation. The result is an interactive **Power BI Dashboard** for HR decision-making.

---

### 📊 Objectives  
- Understand drivers of employee attrition.  
- Visualize attrition by job role, department, overtime, and experience.  
- Provide actionable recommendations for retention strategies.  

---

### 🧠 Tools Used  
| Tool | Purpose |
|------|----------|
| Power BI | Data cleaning, visualization, dashboard creation |
| Excel | Data preview and sanity check |

---

### 📁 Dataset  
**Source:** IBM HR Employee Attrition Dataset  
- **Records:** 1,470 employees  
- **Key Columns:** Attrition, Department, JobRole, OverTime, Gender, MonthlyIncome, YearsAtCompany  

---

### 📈 Insights  
- Sales Executives and R&D employees have the highest attrition.  
- Overtime workers are more likely to leave.  
- Most resignations occur between 5–10 years of service.  

---

### 📦 Deliverables  
- 📊 `HR_Attrition_Dashboard.pbix`  
- 📸 `HR_Attrition_Dashboard_Screenshot.png`  
- 📄 `HR_Employee_Attrition_Report.pdf`  

---

## 🧩 Final Takeaways  
- Strengthened analytical and data storytelling skills.  
- Applied ML, SQL, and BI tools for real-world business problems.  
- Delivered end-to-end data solutions — from preprocessing to insights visualization.  
- Gained hands-on experience in **data-driven decision-making**.  

---

## 🧾 Keywords  
`#DataAnalytics` `#MachineLearning` `#SQL` `#Python` `#PowerBI`  
`#DataVisualization` `#CustomerChurn` `#HRAnalytics` `#EcommerceAnalysis` `#ElevateLabs`  

---
