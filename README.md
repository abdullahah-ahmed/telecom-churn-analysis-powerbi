# 📉 Customer Churn Analysis Dashboard — Power BI

## 🗂️ Project Overview

An interactive **Customer Churn Analysis** solution built in Power BI for a telecom company. The project focuses on identifying churned customers, understanding churn drivers, and flagging at-risk customers — delivered through 2 targeted dashboards.

---

## 🎯 Business Questions Answered

- How many customers have churned and what is the overall churn rate?
- Which customer segments are most likely to churn?
- Does internet service type, contract type, or payment method affect churn?
- Which subscribed services correlate with higher churn?
- Who are the customers currently at risk?

---

## 🛠️ Work Done

### DAX Measures (20+ Measures)
All measures built to support churn analysis:

| Measure | Description |
|---|---|
| `churn rate` | % of churned customers out of total |
| `#customers churned` | Count of churned customers |
| `customers at risk` | Count of customers flagged as high risk |
| `ChurnYes_Percent` | Churn percentage per segment |
| `churn_code` | Churn classification identifier |
| `# teck tickets churned` | Tech support tickets raised by churned customers |
| `# admin tickets churned` | Admin tickets raised by churned customers |
| `avg monthly charge` | Average monthly charge for churned customers |
| `avg yearly charge` | Average yearly charge for churned customers |
| `avg_admin ticket churned` | Avg admin tickets per churned customer |
| `total charges churned` | Total revenue lost from churned customers |
| `monthly_charge_for_churned` | Monthly charges attributed to churned segment |
| `TOTAL_charge_for_remaining` | Total charges for retained customers |
| `not churned` | Count of retained customers |
| `partner_rate` | % of churned customers with a partner |
| `dependents_rate` | % of churned customers with dependents |
| `senior citizen C` | % of churned customers who are senior citizens |
| `subscription time` | Tenure grouping for churn analysis |
| `YEARLY CHARGES` | Total yearly charges |
| `Yearly charges churned` | Yearly charges for churned segment |

### Feature Engineering (Calculated Columns)
- `subscription time` — tenure bucketed into time bands (< 1yr, < 2yr… < 6yr)
- `churn_code` — churn flag encoding for segmentation
- `online security`, `online backup`, `phone service`, `tech support`, `streaming tv`, `streaming movies`, `device protection` — service adoption flags per customer

---

## 📊 Dashboard Pages

### 🟢 Page 1 — Customer Churn Dashboard
**Audience:** Marketing & Retention Teams

**KPIs:**
- Customers at Risk: **1,869**
- Tech Tickets (Churned): **2,173**
- Admin Tickets (Churned): **885**
- Total Charges Lost: **$2.86M**
- Monthly Charges (Churned): **$139.13K**

**Visuals:**
- 🍩 Churned customers by Gender (Female 49.76% / Male 50.24%)
- 📊 Churn by Subscription Time — **55.48%** of churned customers left within the first year
- 📋 Demographics: Senior Citizens (25%), Partner Rate (36%), Dependents (17%)
- 💳 Payment Method breakdown — Electronic check leads at **57.30%**
- 📄 Contract Type — Month-to-month contracts dominate at **88.55%** of churned
- 🌐 Internet Service — Fiber Optic users show **69.40%** churn concentration
- 📦 Subscribed Services adoption rates among churned customers

---

### 🟢 Page 2 — Customer Risk Analysis Dashboard
**Audience:** Customer Success & Operations Teams

**KPIs:**
- Total Customers: **7,032**
- Overall Churn Rate: **27%**
- Total Charges: **$16.06M**
- Admin Tickets: **3,621**
- Tech Tickets: **2,955**

**Visuals:**
- 📊 Churn Rate by Internet Service — Fiber Optic: **42%**, DSL: **19%**, No Internet: **7%**
- 🍕 Customer & Revenue distribution by Internet Service type
- 📊 Churn Rate by Contract Type — Month-to-month: **42.71%** vs Two-year: **2.85%**
- 📊 Churn Rate by Subscription Time — highest in year 1 at **47.68%**
- 📊 Churn Rate by Payment Method — Electronic check: **45.29%**
- 🔽 Interactive Slicers: Churn status, Internet Service type

---

## 💡 Key Insights

- **27% overall churn rate** — roughly 1 in 4 customers is leaving.
- **55% of churned customers** left within their first year — onboarding experience is critical.
- **Fiber Optic** users churn at **42%** despite being the highest revenue segment — a major red flag.
- **Month-to-month contracts** are the biggest churn driver at **42.71%** churn rate.
- **Electronic check** payment method correlates with the highest churn (**45.29%**).
- Customers **without Tech Support** show significantly higher churn rates.
- **1,869 customers** are currently identified as at-risk — immediate retention action needed.

---

## 🚀 Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | DAX, Calculated Columns, Report Design |
| **DAX** | 20+ measures for churn KPIs and segmentation |
| **Feature Engineering** | Tenure banding, service flags, churn encoding |

---

## 📁 Project Structure

```
📦 Customer-Churn-Analysis/
 ┣ 📊 Customer_Churn_Dashboard.pbix
 ┣ 📸 screenshots/
 ┃ ┣ churn_dashboard.png
 ┃ ┗ risk_analysis_dashboard.png
 ┗ 📄 README.md
```

---

## 👤 Author

**[Abdullah Ahmed]**
Data Analyst | Power BI Developer
[LinkedIn]([https://linkedin.com/in/yourprofile](https://www.linkedin.com/in/abdullah-ahmed-taha/))
