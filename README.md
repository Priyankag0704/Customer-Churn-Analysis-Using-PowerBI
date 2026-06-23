# 📊 Customer Churn Analysis Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?style=for-the-badge&logo=powerbi)
![DAX](https://img.shields.io/badge/Language-DAX-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Data%20Cleaning-Power%20Query-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

---

# 📌 Project Overview

This **Customer Churn Analysis Dashboard** was built in **Power BI** to analyze customer attrition patterns and identify the key factors influencing churn. The dashboard provides business insights into customer retention, contract types, tenure, monthly charges, and risk segmentation, enabling organizations to make data-driven decisions to reduce customer loss and improve customer lifetime value.

---

# 🎯 Business Problem

Customer churn directly impacts revenue and profitability. Businesses need to understand:

- Why customers are leaving.
- Which customer segments are at higher risk.
- How contract type and tenure influence retention.
- What factors contribute to customer loyalty.

This dashboard transforms raw customer data into actionable insights for strategic decision-making.

---

# 🛠 Tools & Technologies Used

| Tool | Purpose |
|--------|---------|
| **Power BI** | Dashboard Development |
| **Power Query** | Data Cleaning & Transformation |
| **DAX** | KPI Calculations and Measures |
| **Data Modeling** | Relationship Management |
| **Excel/CSV Dataset** | Data Source |

---

# 📈 Dashboard KPIs

### ✅ Total Customers
**7,043**

### ✅ Churn Rate
**26.54%**

### ✅ Total Churned Customers
**1,869**

### ✅ Retained Customers
**5,174**

---

# 📊 Dashboard Features

## 1️⃣ Customer Retention Overview
- Overall customer retention vs churn distribution.
- Interactive donut chart for quick performance evaluation.

### Key Insight
- **73.46% customers are retained.**
- **26.54% customers have churned.**

---

## 2️⃣ Churned Customers by Contract Type

Analyzes customer churn across different subscription contracts.

### Findings

✔ Month-to-Month customers contribute the highest churn.

✔ One-Year and Two-Year contracts have significantly lower churn rates.

### Business Recommendation

Encourage customers to move from month-to-month plans to long-term contracts to improve retention.

---

## 3️⃣ Churn Rate by Tenure Band

Customer churn segmented by customer lifespan.

| Tenure Band | Churn Rate |
|-------------|------------|
| 0–6 Months | 52.94% |
| 6–12 Months | 35.89% |
| 12+ Months | 17.13% |

### Key Insight

Customers are most likely to churn during their first six months.

### Recommendation

Implement onboarding programs and loyalty campaigns to improve early customer engagement.

---

## 4️⃣ Monthly Charges Analysis

Compares average monthly charges between retained and churned customers.

### Observation

- Churned customers exhibit higher monthly charges.
- Pricing strategy and service value significantly affect retention.

---

## 5️⃣ Online Security & Backup Analysis

Examines monthly charges based on:

- Online Security
- Backup Services

### Key Finding

Customers without security and backup services tend to contribute more to churn.

---

## 6️⃣ Risk Segmentation

Customers are categorized into:

- Normal Risk
- High Risk

### Business Benefit

Helps organizations:

- Identify customers likely to leave.
- Take proactive retention measures.
- Improve customer satisfaction.

---

# 📌 Key Business Insights

### 🔹 26.54% overall customer churn rate.

### 🔹 Month-to-Month contract customers account for the majority of churn.

### 🔹 Customers with shorter tenure (0–6 months) are at the highest risk.

### 🔹 Higher monthly charges are associated with increased churn probability.

### 🔹 Customers lacking online security and backup services show higher attrition rates.

### 🔹 Long-term contracts significantly improve customer retention.

---

# 📷 Dashboard Preview

<p align="center">
<img width="1000" alt="Customer Churn Dashboard" src="https://github.com/Priyankag0704/Customer-Churn-Analysis-Using-PowerBI/blob/main/Snapshot%20of%20Customer%20Churn%20Analysis.png">
</p>

---

# 💡 Recommendations

✔ Introduce loyalty and retention programs for new customers.

✔ Promote annual and long-term subscription plans.

✔ Provide value-added services like online security and backup.

✔ Develop targeted marketing campaigns for high-risk customers.

✔ Monitor customer behavior to proactively reduce churn.
---

# 🚀 Skills Demonstrated

### Data Analysis
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)

### Power BI
- KPI Cards
- Interactive Dashboard Design
- Treemap
- DAX Measures
- Data Modeling
- Drill-through Analysis

### Business Analytics
- Customer Segmentation
- Retention Analysis
- Churn Prediction Insights
- Performance Monitoring

---

# 📚 DAX Measures Used

```DAX
Total Customers = COUNT(Customer[CustomerID])

Churned Customers =
CALCULATE(
    COUNT(Customer[CustomerID]),
    Customer[Churn]="Yes"
)

Churn Rate % =
DIVIDE(
    [Churned Customers],
    [Total Customers]
) * 100

Retained Customers =
CALCULATE(
    COUNT(Customer[CustomerID]),
    Customer[Churn]="No"
)

Average Monthly Charges =
AVERAGE(Customer[MonthlyCharges])
```

---

# 📌 Business Impact

This dashboard enables organizations to:

- Reduce customer churn.
- Improve customer retention strategies.
- Increase customer lifetime value.
- Identify high-risk customer segments.
- Support data-driven business decisions.

---
