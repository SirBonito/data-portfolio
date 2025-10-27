# Maji Ndogo Integrated Project 💧  
*An ALX Data Analytics Project by Boniface Kibet*

---

## 📖 Project Overview  
Access to clean and safe water remains one of the most pressing challenges for many developing regions. The **Maji Ndogo Integrated Project** explores patterns in water access and distribution, identifying areas that require targeted intervention.  

The project demonstrates end-to-end data analysis skills — from data preparation and cleaning, through querying and analysis, to visualization and insight communication (in progress).

---

## 🎯 Objectives  
- To analyze access to clean water across provinces in Maji Ndogo.  
- To identify which **source types** (rivers, wells, boreholes, etc.) serve the largest populations.  
- To determine the **most underserved regions** and possible factors affecting water distribution.  
- To demonstrate practical SQL and data analytics skills learned during the ALX Data Analytics program.

---

## 🧩 Dataset Description  
The dataset used in this project was provided as part of the ALX Data Analytics curriculum. It includes multiple related tables such as:

| Table Name | Description |
|-------------|--------------|
| `project_progress` | Contains information on water projects, their province, town, source type, and improvement details. |
| `water_source` | Contains details on water sources and number of people served. |
| `combined_analysis_table` | A merged table created during the data preparation stage. |

---

## 🛠️ Tools & Technologies  
- **SQL** – for querying, joins, and aggregations.  
- **Excel / Google Sheets** – for preliminary data inspection and cleaning.  
- **Power BI / Tableau (upcoming)** – for visual storytelling and dashboards.  
- **GitHub** – for version control and portfolio presentation.

---

## 🔍 Process & Methodology  

### 1. Data Preparation  
- Cleaned and formatted the raw data to handle missing and inconsistent values.  
- Merged datasets to form a comprehensive analysis table.  
- Validated data integrity by checking for duplicates and inconsistencies in province names and IDs.  

### 2. Data Analysis & Querying  
Sample SQL tasks performed include:
```sql
-- Identify provinces with the highest number of people served
SELECT province_name,
       SUM(number_of_people_served) AS total_people_served
FROM combined_analysis_table
GROUP BY province_name
ORDER BY total_people_served DESC;
