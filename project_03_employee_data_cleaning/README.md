# Project 03: Employee Data Cleaning & Insights

##  Overview
This project focuses on **cleaning and analyzing the HR Employee Attrition dataset**.  
The dataset contains demographic, job-related, and attrition information about employees.

###  Objectives
- Clean the dataset (handle missing values, duplicates, inconsistent data).
- Perform basic exploratory data analysis (EDA).
- Extract meaningful insights about employee attrition.
- Prepare the dataset for future machine learning tasks.

---

##  Data Cleaning Process
1. Checked for **missing values** → none found.
2. Removed **duplicate records** (if any).
3. Standardized **column names** (replaced spaces with underscores).
4. Verified and adjusted **data types**.
5. Separated **categorical** and **numerical** features for later analysis.

---

## Exploratory Data Analysis (EDA)

### 1. Attrition Distribution
- Most employees have **no attrition**.
- Dataset is imbalanced, which is important for future ML modeling.

### 2. Age Distribution
- Majority of employees are aged **30–40 years**.
- Fewer employees are very young (<25) or older (>55).

### 3. Department vs Attrition
- **Sales department** shows a relatively higher attrition rate compared to R&D and HR.

---

##  Key Insights
- Employee attrition is relatively low overall, but certain departments (like Sales) experience more turnover.  
- Age plays a role, with mid-career employees being the largest group in the company.  
- This cleaned dataset is now ready for **advanced analysis and predictive modeling**.

---

##  Next Steps
- Perform correlation and statistical analysis.
- Train ML models to **predict employee attrition**.
- Explore feature importance to understand drivers of attrition.

