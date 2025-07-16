# HR_Attrition_EDA_Project
A business-focused EDA project to uncover drivers of employee attrition using IBM HR data
# 📊 HR Attrition Analysis — EDA Project (IBM Dataset)

## 🔍 Objective
This project explores the IBM HR Employee Attrition dataset to identify key factors influencing employee turnover. The goal is to provide **data-driven insights and business recommendations** to improve employee retention, mirroring real-world HR analytics tasks performed by data analysts in MNCs.

---

## 📦 Dataset
- **Source:** [Kaggle - IBM HR Analytics](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Rows:** 1470  
- **Columns:** 35 (Demographics, job details, satisfaction scores, compensation, etc.)

---

## 📈 Key Business Questions Explored

| Question                                                                 | Technique/Chart Used                     |
|--------------------------------------------------------------------------|------------------------------------------|
| Are younger employees more likely to leave?                             | Age histograms by Attrition              |
| Does working overtime increase attrition risk?                          | Countplot of Overtime × Attrition        |
| Do job roles or departments affect attrition?                           | Barplots and normalized attrition rates  |
| What impact does salary, satisfaction, or commute distance have?        | Boxplots and heatmaps                    |
| Can we create a flag to identify high-risk employees for exit?          | Rule-based feature engineering           |

---

## 🔬 Advanced Exploratory Features

✔️ **Satisfaction Index** = mean of 3 satisfaction columns  
✔️ **Years per Promotion** = TotalWorkingYears / CompaniesWorked  
✔️ **HighRiskFlag** = Employees with low income, high overtime, and low satisfaction  
✔️ **Attrition Rate by Role** and **Work-Life Balance conflict**

---

## 🧠 Key Findings

- 🔹 Employees aged **21–30** have the highest attrition rate.
- 🔹 **Overtime** and **low income (< ₹40K/month)** are major churn drivers.
- 🔹 Roles like **Sales Executive** & **Lab Technician** face high attrition.
- 🔹 Employees with **poor satisfaction scores** or **long commutes** are more likely to exit.
- 🔹 A custom **HighRiskFlag** can pre-flag over 70% of likely leavers.

---

## 📌 Business Recommendations

- 🧑‍🎓 Launch mentoring and L&D tracks for early-career employees.
- ⏱ Optimize workload and overtime in high-churn roles.
- 💬 Deploy real-time feedback surveys to track satisfaction monthly.
- 📊 Build dashboards to monitor attrition-linked KPIs.

---

## 🛠 Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Data Cleaning, EDA, Feature Engineering

---

## 📁 Project Structure
