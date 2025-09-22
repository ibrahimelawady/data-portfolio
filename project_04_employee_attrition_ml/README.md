# 👩‍💼 Employee Attrition Prediction (ML)

##   Overview
This project explores and predicts **employee attrition** using the famous HR Employee Attrition dataset.  
We applied data cleaning, exploratory analysis, and machine learning models to understand the key drivers of attrition and evaluate predictive performance.  

---

##   Steps Performed
1. **Data Loading & Cleaning**
   - Removed missing values.
   - Encoded categorical features with `LabelEncoder`.
   - Standardized numerical features with `StandardScaler`.

2. **Exploratory Data Analysis (EDA)**
   - Distribution of attrition across departments.
   - Impact of features like age, monthly income, and job role.
   - Correlation analysis.

3. **Modeling**
   - Trained and evaluated:
     - Logistic Regression  
     - Random Forest Classifier
   - Compared performance using:
     - Accuracy, Precision, Recall, F1-score
     - Confusion Matrix
     - ROC-AUC score

4. **Feature Importance**
   - Identified top 15 features influencing attrition using Random Forest.

5. **Visualizations**
   - ROC curves comparing Logistic Regression and Random Forest.  
   - Feature importance barplot.  

---

##  Results & Insights
- **Random Forest** outperformed Logistic Regression:
  - Higher recall → better at identifying employees who will leave.
  - Higher ROC-AUC → better discrimination ability overall.
- **Top drivers of attrition** included:
  - Monthly Income  
  - OverTime  
  - Job Role  
  - Total Working Years  
  - Age  
- Employees with **lower income, high overtime, and fewer working years** were more likely to leave.

---

##  Key Findings
- Attrition is not random — it strongly correlates with salary, workload, and job type.  
- Random Forest is more suitable for this dataset than Logistic Regression.  
- HR teams can use these insights to **improve retention strategies**.

---



  **Outputs Saved in Drive**
- `employee_data_cleaned.csv`  
- Feature Importance Plot → `images/feature_importances.png`  
- ROC Curve → `images/roc_curve.png`  

