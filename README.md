# 🏦 Bank Customer Churn Analysis Dashboard  
**Tools:** Power BI | Excel | DAX | Power Query  

This project analyzes customer churn for a retail bank using **Excel** and **Power BI** to uncover the key factors influencing customer attrition.  
The goal is to help stakeholders identify churn drivers and implement data-driven retention strategies.  

---

## 📊 Overview  
Customer churn represents the percentage of customers who stop using a bank’s services.  
Understanding churn helps financial institutions improve customer satisfaction, loyalty, and profitability.  

This project provides a detailed analysis of **10,000+ customer records**, exploring demographic, behavioral, and financial factors contributing to churn.  
It integrates **Excel-based data preprocessing** with **Power BI dashboards** for interactive insights.  

---

## 🎯 Objectives  
- Analyze customer churn trends across demographics and regions.  
- Identify patterns linked to churn, such as credit score, satisfaction, and activity levels.  
- Create a data validation process using Excel before visualization in Power BI.  
- Build an interactive Power BI dashboard to support strategic decision-making.  

---

## 🔍 Key Insights  
1. **Churn Overview:**  
   - Overall churn rate: **20.38%**  
   - Total active customers: **5151**  
   - Total churned customers: **2038**  

2. **Demographic Insights:**  
   - **Females** have a higher churn percentage than males.  
   - **Germany** records the highest churn rate among all countries analyzed.  

3. **Behavioral Factors:**  
   - Customers with **1 or 2 products** are more likely to churn.  
   - Low satisfaction and inactive memberships are key churn indicators.  

4. **Financial Indicators:**  
   - Low **credit scores** and **non-zero balances** correlate strongly with churn.  

5. **Retention Opportunity:**  
   - Data-driven retention strategies could potentially reduce churn by **~8%**.  

---

## ⚙️ Tools & Techniques  
| Tool | Purpose |
|------|----------|
| **Excel** | Initial data cleaning, summary statistics, KPI validation |
| **Power Query** | Data transformation and modeling before visualization |
| **DAX (Power BI)** | Calculated columns and KPIs such as Churn Rate and Active % |
| **Power BI** | Interactive dashboards and visual storytelling |

---

## 📘 Excel Contribution  
Excel was used for **data preprocessing and metric validation** before visualization in Power BI:  
- Removed duplicates, standardized formats, and handled missing data.  
- Calculated churn metrics and demographic summaries using formulas and pivot tables.  
- Validated key KPIs like churn percentage and active/inactive customer counts.  
- Created a simple **Excel dashboard** for churn summaries (Country-wise and Gender-wise).  

---

## 📊 Power BI Dashboard Highlights  
### Key Metrics  
- **Total Customers:** 10,000  
- **Churned Customers:** 2038  
- **Churn Rate:** 20.38%  
- **Churn by Geography, Gender, Age, Product, and Credit Score** visualized through interactive charts.  

### Key Visuals  
- Donut Chart → Overall churn percentage  
- Bar Charts → Churn by Geography, Product, and Gender  
- Line Chart → Churn by Age Group and Tenure  
- KPI Cards → Total Customers, Active vs Churned, Average Credit Score  

---

## 🧠 Insights Summary  
- Germany and female customers show the highest churn tendency.  
- Low satisfaction and fewer products correlate with higher churn risk.  
- Customers with low credit scores and medium balances are most likely to leave.  
- Targeted retention efforts could improve customer retention by up to **8%**.  

---

## 🗂️ Dataset  
The dataset was sourced from [Kaggle](https://www.kaggle.com) and contains over **10,000 customer records** with attributes such as:  
- **Demographics:** Gender, Age, Geography  
- **Banking Data:** Credit Score, Balance, Products Held, Tenure  
- **Behavioral Factors:** Satisfaction Score, Activity Status  
- **Target Variable:** Churn (Yes/No)  

---

## 🧰 Project Structure  
Bank_Customer_Churn_Analysis/
│
├── Data/
│ ├── bank_churn_raw.csv
│ ├── bank_churn_cleaned.xlsx
│
├── Excel_Analysis/
│ ├── Churn_Summary.xlsx
│ ├── Validation_Sheet.xlsx
│
├── PowerBI_Dashboard/
│ ├── Bank_Customer_Churn.pbix
│
├── Screenshots/
│ ├── Excel_Summary.png
│ ├── PowerBI_Dashboard.png
│
└── README.md


---

## 🖼️ Dashboard Snapshots  

### Power BI Dashboard  
<img width="1160" height="484" alt="Screenshot (328)" src="https://github.com/user-attachments/assets/b5460d8b-976b-46b1-b12f-db50c0e83b62" />  

<img width="1166" height="489" alt="Screenshot (329)" src="https://github.com/user-attachments/assets/43835f49-fb1f-4a97-8f2e-4262f25a5c41" />  

<img width="1167" height="487" alt="Screenshot (330)" src="https://github.com/user-attachments/assets/ea931ebe-3404-4368-a999-c8ba8c75b726" />  

### Excel Dashboard

---

## 🏁 Conclusion  
By combining **Excel’s analytical power** with **Power BI’s visualization capabilities**, this project delivers end-to-end insights into customer churn behavior.  
It showcases the importance of **data validation, visualization, and actionable storytelling** in driving customer retention strategies.  

---
