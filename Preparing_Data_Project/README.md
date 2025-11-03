# Preparing Data for Analysis: Access to Safe and Affordable Drinking Water  
*ALX Data Analytics – Data Preparation Module Project*  
*By Boniface Kibet*

---

## 🌍 Project Overview  
This project focused on understanding **global inequalities in access to safe and affordable drinking water**, emphasizing how data preparation shapes the accuracy and depth of analysis.  
Before any querying or visualization, the goal was to clean, standardize, and transform raw data into a reliable foundation for later exploration.

---

## 🎯 Objectives  
- Assess disparities in access to clean water between different **countries and regions**.  
- Identify missing, inconsistent, or unreliable data that could distort analysis.  
- Practice professional **data preparation techniques**—cleaning, transformation, and validation—using real-world water access data.

---

## 🧩 Dataset Description  
The dataset included information on water access, population, and service levels across various countries and income groups.  
Key columns included:
- **Country / Region**
- **Population served**
- **Service level (%)**
- **Year**
- **Water source type**
- **Income group classification**

The raw data contained inconsistencies such as:
- Different spellings for the same country names  
- Missing or duplicate entries  
- Unaligned service-level formats (percentages vs decimals)

---

## 🛠️ Tools & Techniques  
- **Excel / Google Sheets:** For data cleaning, formatting, and standardization.  
- **SQL (basic):** For initial filtering and exploration.  
- **Data Validation:** Ensuring unique IDs, checking for null values, and applying consistent naming conventions.  

---

## 🔍 Process  

### 1. Data Cleaning  
- Removed duplicates and irrelevant rows.  
- Standardized country and region names using lookup tables.  
- Handled missing data using mean substitution and logical inference (e.g., using neighboring country averages).  
- Converted service level values into a consistent percentage format.  

### 2. Data Transformation  
- Split composite columns (e.g., “Country–Region”) into separate fields.  
- Created calculated columns such as “Population without access.”  
- Filtered out outliers to prevent distortion of results.  

### 3. Validation  
- Cross-checked totals and averages with public reference datasets (e.g., WHO/UNICEF JMP).  
- Ensured data types aligned correctly (text, numeric, percentage).  

---

## 💡 Key Findings (Before Visualization)
- **High inequality:** Low-income regions consistently showed service levels below 50%.  
- **Regional contrast:** Urban regions often had 2–3× higher access rates than rural ones.  
- **Data gaps:** Some countries lacked recent reporting, emphasizing the need for better data infrastructure.

---

## 🧠 Learnings & Reflections  
This project reinforced one of the biggest truths in analytics: *clean data is powerful data.*  
Through this exercise, I learned:
- Preparation takes time but saves countless errors later.  
- Context matters—knowing what a number *means* is as important as its accuracy.  
- Collaboration and peer review are essential in catching unseen inconsistencies.

---

## 🚀 Next Steps  
The cleaned and validated dataset from this project formed the basis for the **Maji Ndogo Integrated Project**, where I applied querying, analysis, and soon, visualization techniques to extract deeper insights.

---

## 👤 Author  
**Boniface Kibet**  
Data Analyst (in training) | ALX Africa  
[LinkedIn](www.linkedin.com/in/bonifacekibet) | [Email](mailto:bonifacekibet50@gmail.com)
