
# 📊 HR Analytics Dashboard – Power BI Portfolio Project

## 🚀 Project Overview

The **HR Analytics Dashboard** is an interactive Power BI project designed to analyze employee data and uncover key workforce insights related to attrition, demographics, salary distribution, and job satisfaction.

This dashboard enables HR teams and business leaders to make **data-driven decisions** to reduce employee turnover and improve organizational performance.

---

## 📸 Dashboard Preview

<p align="center">
  <img src="bi.png" width="1000">
</p>

---

## 🎯 Business Problem

Employee attrition significantly impacts productivity and increases hiring costs.  

This project aims to:

- Identify departments with high attrition  
- Analyze salary and experience trends  
- Study demographic patterns influencing turnover  
- Understand job satisfaction levels  
- Provide actionable HR insights  

---

## 📊 Key KPIs

- 👥 **Total Employees:** 1413  
- 🚪 **Attrition Count:** 229  
- 📉 **Attrition Rate:** 16.21%  
- 🎂 **Average Age:** 37  
- 💰 **Average Salary:** 6.5K  
- 🕒 **Average Years at Company:** 7.0  

---

## 📈 Dashboard Insights

### 🔹 Attrition by Age
- Highest attrition observed in the **26–35 age group**
- Early-career employees show higher exit rates

### 🔹 Attrition by Salary Band
- Maximum attrition in salary band **Up to 5K**
- Attrition reduces as salary increases

### 🔹 Department & Job Role Insights
- Sales and Laboratory roles show higher turnover
- Research-based roles show moderate attrition

### 🔹 Education Impact
- Life Sciences background shows higher attrition
- Technical degree holders show stable retention patterns

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|------|----------|
| Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | KPI Calculations |
| CSV Dataset | Data Source |
| PBIX | Report Model |

---

## 🧮 Sample DAX Measures

```DAX
Attrition Count = 
CALCULATE(
    COUNT(Employee[EmployeeID]),
    Employee[Attrition] = "Yes"
)

Attrition Rate = 
DIVIDE(
    [Attrition Count],
    COUNT(Employee[EmployeeID])
)

Average Salary = 
AVERAGE(Employee[MonthlyIncome])
```

---

## 🗄 Data Preparation

- Cleaned missing values using Power Query  
- Created calculated columns for age groups and salary bands  
- Built relationships in the data model  
- Designed interactive slicers for filtering  

---

## 🎛 Interactive Features

- Department filter  
- Gender filter  
- Education filter  
- Dynamic KPI updates  
- Drill-down visualizations  

---

## 📌 Business Value

This dashboard helps organizations:

- Reduce employee turnover  
- Improve workforce planning  
- Optimize compensation strategies  
- Identify high-risk attrition groups  
- Support data-driven HR decisions  

---

## 🔮 Future Enhancements

- Predictive attrition modeling using Machine Learning  
- Power BI Service deployment  
- Row-Level Security (RLS)  
- Executive summary page for leadership  

---

## 📂 Project Files

- `HR_analytics_dashboard.pbix` – Power BI Report  
- `HR_Analytics.csv` – Dataset  
- `HR_Analytics_Dashboard.png` – Dashboard Preview  
- `README.md` – Documentation  

---

## 👨‍💻 Author

**Adithiya K**  
B.Tech – Computer Science  
Lovely Professional University  

---

⭐ If you found this project useful, feel free to star the repository!
