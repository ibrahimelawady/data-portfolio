# Project 05 — Retail Sales Analysis

## 📌 Overview
This project focuses on analyzing a **retail sales dataset** to uncover trends, product performance, and profitability patterns.  
The analysis highlights which products drive the most sales, seasonality effects, and provides recommendations for inventory and marketing strategies.

---

## 📂 Dataset
**File:** `Sales_Data.csv`  
**Location used in this project (Google Drive):**  
`/content/drive/MyDrive/DATA_SCIENCE_PROJECTS/Sales_Data.csv`

### Columns:
- **month_number** → Month index (1–12)  
- **facecream, facewash, toothpaste, bathingsoap, shampoo, moisturizer** → Units sold per product per month  
- **total_units** → Total units sold in the month  
- **total_profit** → Total profit generated in the month  

✅ Dataset has **12 rows × 9 columns** with **no missing values**.

---

## 🛠️ Project Structure
project_05_sales_analysis/
├── project_05_sales_analysis.ipynb # Colab/Jupyter notebook (analysis + charts)
├── Sales_Data.csv # raw dataset
├── README.md # project documentation
└── images/ # saved charts (optional)
├── monthly_sales_trend.png
├── units_vs_profit.png
└── product_contribution.png


---

## 🔎 Steps Performed
1. **Import libraries** → pandas, numpy, matplotlib, seaborn.  
2. **Load dataset** from Google Drive.  
3. **Explore dataset** → shape, datatypes, descriptive stats, missing values check.  
4. **EDA (Exploratory Data Analysis)** → product-level and month-level analysis.  
5. **Visualizations** → line charts, scatter plot, pie chart.  
6. **Insights & recommendations** → based on product performance and profitability.

---

## 📊 Key Visualizations
- **Monthly Sales Trend per Product** → Line chart showing monthly units sold for each product.  
- **Total Units vs. Total Profit** → Scatter plot showing relationship between units and profit.  
- **Product Contribution** → Pie chart showing sales share of each product category.  

*(You can save plots into `/images/` and embed them here.)*

---

## 💡 Insights & Recommendations
- **Toothpaste** → Highest sales volume, consistent demand → main revenue driver.  
- **Bathing Soap** → Strong and stable performance, second-largest contributor.  
- **Facewash & Moisturizer** → Lower sales → consider targeted promotions/bundling.  
- **Seasonality** → Sales peak in Q4 → prepare stock & marketing campaigns accordingly.  
- **Profitability** → Profit follows units sold closely → indicates stable margins across products.  

📌 **Business Actions:**  
- Boost inventory and marketing budget for *Toothpaste* & *Bathing Soap*.  
- Promote *Facewash* and *Moisturizer* with discounts or bundles.  
- Plan logistics to avoid stockouts in peak season (months 10–12).  

---

## 🚀 How to Run (Google Colab)
1. Mount Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
