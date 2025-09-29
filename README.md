# 📊 Amazon Sales Analysis – Power BI Dashboard


## 📌 Table of Contents
- [Overview](#overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Tools & Technologies](#tools--technologies)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Dashboard](#dashboard)
- [Final Recommendations](#final-recommendations)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------



## 📌 Overview
This project presents an interactive **Power BI dashboard** built from Amazon sales data stored in Excel.  
The goal is to analyze **Year-to-Date (YTD)** sales performance, product category trends, and customer review patterns to support data-driven decision-making.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------




## 💡 Business Problem
Amazon wants to monitor sales across products and time periods to answer:
- Which **product categories** generate the highest revenue?
- How do **monthly and weekly** sales fluctuate over the year?
- Does the **number of reviews** impact sales performance?
- Which quarters require **strategic focus** to increase revenue?

--------------------------------------------------------------------------------------------------------------------------------------------------------

## Dataset
- **Source:** [ Data folder](Data/) – contains the **Amazon_Combined_Data.csv** Excel file  

--------------------------------------------------------------------------------------------------------------------------------------------------------------
## Project Structure

```
Amazon-Analysis/
|                
├─ Data/
│   └─Amazon_Combined_Data.csv  
│
├─ Dashboard/
│   └─Amazone Sales Analysis.pbix
│
├─ Images/
│   └─ Amazone Sales Analysis.png
│   └─ Amazone.png
├─ README.md
```
----------------------------------------------------------------------------------------------------------------------------------------------------------------
## Tools & Technologies
- Excel 
- Power BI (Interactive Visualizations)
- GitHub

----------------------------------------------------------------------------------------------------------------------------------------------------------------
## Data Cleaning & Preparation

- Removed duplicates and blank rows in Excel.
- Converted `Order Date` to **Date** data type.
- Built a **Date Table** for month/quarter analysis.
- Standardized column names and data types.
- Created relationships between the **Sales** and **Date** tables.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Dashboard

- **Power BI Dashboard** preview:  
  ![Dashboard Preview](Images/Amazone%20Sales%20Analysis.png)

- **Access Dashboard**  
  Click below to view the live Power BI report:

  [![View Dashboard](https://img.shields.io/badge/Power%20BI-View%20Dashboard-yellow?style=for-the-badge&logo=powerbi)](https://app.powerbi.com/view?r=eyJrIjoiYmE3MjhkNDUtMGMwMC00YmM0LWJhOGUtOTI1YWRhM2Y5ZmMxIiwidCI6IjJmMGEzYTlmLWZhOTUtNDM2Zi05YTk4LTZmODEwNjgwNmY0MCJ9)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Final Recommendations

- Increase marketing for **Men Shoes** and **Camera** during peak holiday seasons.
- Encourage customers to provide reviews to boost credibility and sales.
- Monitor underperforming categories (e.g., Mobile Accessories) for product strategy changes.
