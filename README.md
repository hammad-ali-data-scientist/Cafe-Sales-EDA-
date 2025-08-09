# ☕ Cafe Sales Data Cleaning & Analysis

This repository contains a complete **Data Cleaning and Exploratory Data Analysis (EDA)** workflow for a café's sales dataset.  
The primary objective is to transform inconsistent, error-prone raw sales records into a clean, structured format and extract business insights to support decision-making.


## 📌 Business Context
Cafes generate large amounts of transactional data daily, which can be riddled with:
- Missing values
- Typographical errors
- Inconsistent formats  
Cleaning and analyzing this data enables:
- Better inventory management
- Optimized pricing strategies
- Identification of high-demand products

---

## 🎯 Project Objectives
1. **Data Cleaning** – Standardize, validate, and preprocess sales data.
2. **Data Transformation** – Convert data types, handle nulls, and fix incorrect entries.
3. **Exploratory Analysis** – Identify sales trends, customer preferences, and payment patterns.
4. **Data Export** – Produce a high-quality cleaned dataset ready for further analysis or dashboard integration.


## 🛠 Methodology
- **Load Raw Data** (`dirty_cafe_sales.csv`)
- **Data Cleaning Process:**
  - Replace invalid entries (`ERROR`, `UNKNOWN`) with `NaN`
  - Convert numeric and date columns to the correct data types
  - Fill missing values:
    - **Median** for numeric fields
    - **Mode** for categorical fields
    - Calculated values for dependent fields (e.g., `Total Spent = Quantity × Price Per Unit`)
- **Exploratory Data Analysis:**
  - Identify top-selling items
  - Analyze daily revenue trends
  - Evaluate payment method preferences
- **Export Results** to `cleaned_cafe_sales.csv`


## 📊 Key Insights
- **Top Products**: Certain menu items dominate sales, indicating strong customer preference.
- **Revenue Patterns**: Seasonal or day-specific sales fluctuations are visible.
- **Payment Trends**: A clear majority payment method could influence POS system upgrades.


## 📈 Visualizations
- **Top 10 Best-Selling Items** 
- **Daily Sales Trend** 
- **Payment Method Distribution** 


## 📦 Technologies Used
- **Python** (Data Processing & Visualization)
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Matplotlib & Seaborn** – Data visualization
- **Google Colab** – Execution environment


## 👨‍💻 Author
**Hammad Ali**
