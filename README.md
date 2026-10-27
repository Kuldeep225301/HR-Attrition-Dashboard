
<img width="1277" height="736" alt="Screenshot 2026-10-27 081015" src="https://github.com/user-attachments/assets/dcaa8c85-ecbb-449e-84b6-97446ce21c93" />
# HR Analytics Dashboard | Workforce Attrition & Retention Analysis
## 📌 Project Overview
The objective of this HR Analytics Dashboard is to help HR leadership analyze employee attrition patterns across key variables such as department, age group, education background, salary slabs, and job satisfaction levels. This interactive dashboard equips stakeholders with data-driven insights to mitigate turnover and improve employee retention strategies.

---

## 🎯 Key Business Questions Addressed
- What is our current overall attrition rate and total employee turnover count?
- Which specific departments and job roles experience the highest employee churn?
- How does salary distribution affect employee retention?
- Is there a correlation between employee tenure, age group, and turnover?

---

## 📊 Key Performance Indicators (KPIs)
- **Total Employees:** 1,470 (1K+)
- **Attrition Count:** 229 Employees
- **Attrition Rate:** 16.21%
- **Average Employee Age:** 37 Years
- **Average Monthly Salary:** $6.52K
- **Average Tenure:** 7.04 Years

---

## 🔍 Key Insights & Root Cause Analysis
1. **Age Bracket Vulnerability:** The **26–35 age group** accounts for the highest attrition count (>100 employees), indicating early-to-mid career flight risk.
2. **Salary Sensitivity:** Attrition is heavily concentrated among employees earning **under $5K monthly**, demonstrating strong pay scale sensitivity.
3. **Departmental Impact:** The **Research & Development** department experienced the highest number of departures (127+), followed by **Sales** (90+).
4. **Role-Specific Turnover:** Laboratory Technicians, Research Scientists, and Sales Executives show higher attrition during their first **1–3 years** of tenure.

---

## 💡 Recommendations & Action Plan
- **Salary Band Adjustment:** Re-evaluate compensation structures for entry and junior-level roles earning under $5K, specifically within R&D and Sales.
- **Targeted Retention Programs:** Design clear 1-to-3-year career development pathways and structured mentorship for professionals aged 26–35.
- **Pulse Surveys:** Conduct targeted feedback loops for Laboratory Technicians and Sales Executives to resolve satisfaction bottlenecks early.

---

## 🛠️ Technical Stack & Tools Used
- **Business Intelligence Tool:** Power BI Desktop
- **Data Transformations:** Power Query (Data Cleansing, Profiling, Type Casting)
- **Data Modeling:** Star Schema / Relational Data Model
- **Calculations:** DAX (Data Analysis Expressions) for KPIs & Aggregations

---

## 📂 Repository Structure
```text
├── Data/
│   └── HR_Analytics_Dataset.csv      # Raw HR dataset
├── Dashboards/
│   └── HR_Analytics_Dashboard.pbix   # Power BI project file
├── Assets/
│   └── Dashboard_Preview.png         # Dashboard screenshot preview
└── README.md                         # Project documentation
