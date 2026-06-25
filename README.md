# 📊 HR Analytics Dashboard

An interactive **Power BI** dashboard designed to analyze workforce trends, evaluate employee retention, and uncover the core drivers behind organizational attrition. Processing a dataset of **1,470 employee records**, this project provides actionable, data-backed insights to optimize HR strategy and improve overall employee retention.

🔹 **Project Overview:** [Report.pdf](Report.pdf)  
🔹 **Dashboard View:** [HR Dashboard](HR%20Dashboard%20image.png)

---

## 🛠️ Tech Stack & Tools
* **Business Intelligence:** Power BI
* **Data Modeling & Analytics:** DAX (Data Analysis Expressions), Excel
* **Visualization Components:** KPI Cards, Donut Charts, Matrix Heatmaps, Clustered Bar/Column Chart.

---

## 📈 Key Performance Indicators (KPIs)
* **Total Headcount:** 1,470 employees
* **Attrition Count:** 237 employees
* **Overall Attrition Rate:** 16.12%
* **Active Workforce:** 1,233 employees
* **Average Workforce Age:** 37 years

---

## 🔍 Critical Insights & Risk Factors

### 1. The Overtime Impact (Strongest Predictor)
* Employees logging overtime exhibit a **30.53% attrition rate** compared to just 10.44% for non-overtime workers. 
* Overtime demands multiply an employee's likelihood to leave by nearly **3x**.
*
* ### 2. High-Risk Departments & Job Roles
* **Sales Department:** Suffers from the highest attrition rate at **20.63%** (effectively 1 in 5 employees).
* **Sales Representatives:** Stand out as the highest-risk role across the entire workforce with an alarming **39.76% attrition rate**.
* **Laboratory Technicians & HR Personnel:** Show elevated risks, both exceeding a **23% attrition rate**.

### 3. Demographics & Education Fields
* **Age Factors:** The **Under 25** demographic represents the highest risk of early departure, while the **25–34** bracket contributes the highest raw volume to attrition counts. Attrition visibly stabilizes after age 35.
* **Education Background:** Employees from **Human Resources (25.93%)** and **Technical Degree (24.24%)** backgrounds show the highest tendency to exit.

---

## 💡 Strategic Recommendations Engineered
* **Workload Balancing:** Re-evaluate corporate overtime policies and distribute workloads more equitably to counter the 3x attrition spike.
* **Sales Department Intervention:** Conduct compensation reviews and implement flexible work policies to stabilize the high-turnover Sales teams.
* **Early-Career Engagement:** Deploy targeted mentorship and robust onboarding programs for employees under 25 to reduce early-stage churn.
* **Proactive Retention:** Conduct targeted "stay interviews" for Laboratory Technicians and build internal career pathways leveraging stable, low-attrition managerial roles.

---

## 📂 Repository Structure
```text
├── Dataset/                      # Raw workforce records containing 1,470 rows
├── HR Analytics Dashboard.pbix   # Interactive Power BI dashboard file
├── Report.pdf                    # Executive summary and deep-dive analytical insights documentation
└── Screenshot 2026-06-25 201708.jpg # Dashboard preview image
