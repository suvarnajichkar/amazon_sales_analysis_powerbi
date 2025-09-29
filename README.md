# 📊 Amazon Sales Analysis – Power BI Dashboard


## 📌 Table of Contents
-<a href="#overview">Overview</a>
-<a href="#business_problem">Business Problem</a>
-<a href="#dataset">Dataset</a>
-<a href="project-structure">Project Structure</a>
-<a href="tools--technologies">Tools & Technologies</a>
-<a href="data-cleaning-preparation">Data Cleaning & Preparation</a>
-<a href="dashboard">Dashboard</a>
-<a href="final-recommendations">Final Recommendations</a>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2><a class="anchor" id="overview"></a>Overview</h2>

## 📌 Overview
This project presents an interactive **Power BI dashboard** built from Amazon sales data stored in Excel.  
The goal is to analyze **Year-to-Date (YTD)** sales performance, product category trends, and customer review patterns to support data-driven decision-making.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2><a class="anchor" id="business_problem"></a>Business Problem</h2>


## 💡 Business Problem
Amazon wants to monitor sales across products and time periods to answer:
- Which **product categories** generate the highest revenue?
- How do **monthly and weekly** sales fluctuate over the year?
- Does the **number of reviews** impact sales performance?
- Which quarters require **strategic focus** to increase revenue?

--------------------------------------------------------------------------------------------------------------------------------------------------------
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- **Source:** [ Data folder](Data/) – contains the **Amazon_Combined_Data.csv** Excel file  

--------------------------------------------------------------------------------------------------------------------------------------------------------------
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

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
|
└─ Scripts/ 
    └─ README.md
```
----------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>
- Excel 
- Power BI (Interactive Visualizations)
- GitHub

----------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2><a class="anchor" id="data-cleaning-preparation"></a>Data Cleaning & Preparation</h2>

- Removed duplicates and blank rows in Excel.
- Converted `Order Date` to **Date** data type.
- Built a **Date Table** for month/quarter analysis.
- Standardized column names and data types.
- Created relationships between the **Sales** and **Date** tables.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- **Power BI Dashboard** preview:  
  ![Dashboard Preview](Images/Amazone%20Sales%20Analysis.png)

- **Access Dashboard**  
  Click below to view the live Power BI report:

  [![View Dashboard](https://img.shields.io/badge/Power%20BI-View%20Dashboard-yellow?style=for-the-badge&logo=powerbi)](https://app.powerbi.com/view?r=eyJrIjoiYmE3MjhkNDUtMGMwMC00YmM0LWJhOGUtOTI1YWRhM2Y5ZmMxIiwidCI6IjJmMGEzYTlmLWZhOTUtNDM2Zi05YTk4LTZmODEwNjgwNmY0MCJ9)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Increase marketing for **Men Shoes** and **Camera** during peak holiday seasons.
- Encourage customers to provide reviews to boost credibility and sales.
- Monitor underperforming categories (e.g., Mobile Accessories) for product strategy changes.
