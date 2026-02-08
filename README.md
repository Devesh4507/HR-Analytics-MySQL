# HR-Analytics-MySQL
End-to-end HR Analytics project using MySQL with business insights


## 📌 Project Overview
This is an end-to-end **HR Analytics project** focused on understanding workforce
structure, employee tenure patterns, and attrition behavior using **MySQL**.

The project simulates sample HR dataset and answers executive-level questions
to support **data-driven workforce planning and retention strategies**.

---

## 🎯 Business Objectives
- Understand overall workforce distribution
- Analyze employee tenure and workforce maturity
- Identify departments with the highest attrition risk
- Evaluate whether employee engagement predicts attrition
- Provide actionable insights for HR decision-makers

---

## 🛠 Tools & Technologies
- **Database:** Kaggle  
- **SQL Concepts:**  
  - Filtering & Aggregation (`WHERE`, `COUNT`, `AVG`, `GROUP BY`)
  - Date & Tenure Analysis (`DATEDIFF`, `TIMESTAMPDIFF`)
  - Conditional Logic (`CASE WHEN`)
  - Joins
  - Window Functions (`SUM() OVER()`)

---

## 📂 Dataset Overview
- Total active employees: **2,458**
- Schema: `panda`
- Tables used:
  - `employee_data`
  - `employee_engagement_survey_data`
  - `recruitment_data`
  - `training_and_development_data`

Employees are distributed across multiple departments, job roles, divisions,
and **three pay zones**.

---

## 🔍 Key Analysis Performed

### 1️⃣ Workforce Distribution
- Analyzed employee count by department, job title, division, and pay zone.
- Confirmed **2,458 active employees** across the organization.

---

### 2️⃣ Employee Tenure Analysis
- **Average tenure (overall): ~5 years**
- Highest average tenure:
  - **Executive Office: 5.5 years** (stable leadership roles)
- Lowest average tenure:
  - **Software Engineering: 4.6 years** (possible growth-driven churn)

---

### 3️⃣ Tenure Bucket Distribution
| Tenure Range | Percentage |
|--------------|-----------|
| Below 1 year | **0%** |
| 1–3 years | ~10% |
| 3–5 years | **41%** |
| 5+ years | **49%** |

➡ Indicates a **highly experienced workforce** but **limited recent hiring**.

---

### 4️⃣ Attrition Rate by Department
Top departments at risk:
- **Executive Office:** **79.2%**
- **Admin Office:** **60.0%**
- **Software Engineering:** **55.7%**

➡ Attrition patterns vary significantly by department, suggesting that
**retention strategies should be department-specific**, not organization-wide.

---

### 5️⃣ Engagement vs Attrition
- Attrition rate (Disengaged): **51.09%**
- Attrition rate (Engaged): **51.11%**

➡ Engagement score alone is **not a strong predictor** of attrition in this organization.

---

## 📊 Key Business Insights
- Nearly **half the workforce (49%)** has more than 5 years of tenure
- Absence of employees with <1 year tenure suggests **limited recent hiring**
- Executive, Admin, and Software Engineering teams require **targeted retention strategies**
- Factors beyond engagement (growth, compensation, role clarity) likely drive exits


---

## 🚀 Conclusion
This project aimed at:
- Translating business problems into SQL-based analysis.
- Applying SQL techniques to real datasets
- Derive actionable insights for HR leadership.
- Present analytical findings in a structured, executive-ready format.
