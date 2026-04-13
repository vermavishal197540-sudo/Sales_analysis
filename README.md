# 📊 Superstore Sales Analysis

## Overview
This project performs **Exploratory Data Analysis (EDA)** on the Superstore dataset to uncover sales trends, customer behavior, and regional performance.  
The analysis includes data cleaning, visualization, and insights into categories, sub-categories, regions, and customer segments.

---

## 🔧 Technologies Used
- **Python** (Data Analysis & Visualization)
- **Libraries:**
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `openpyxl` (for Excel file handling)

---

## 📂 Dataset
- File: `superstore_sales_cleaned.xlsx`
- Columns include: `Order_ID`, `Customer_ID`, `Sales`, `Category`, `Sub_Category`, `Region`, `City`, `Segment`, and `Order_Date`.

---

## 🛠️ Steps Performed
1. **Data Cleaning**
   - Removed null values
   - Converted `Sales` column to integer
   - Renamed `Order_Date` → `Delivered`

2. **Exploratory Data Analysis**
   - **Segment Analysis:** Consumer segment dominates sales.
   - **Regional Analysis:** West region contributes the highest revenue.
   - **City-Level Insights:** Top cities include New York, Los Angeles, and Seattle.
   - **Category/Sub-Category Analysis:** IT products and furniture (especially chairs) drive sales.
   - **Customer & Order Analysis:** Identified top customers and high-value orders.

3. **Visualizations**
   - Bar charts for segments, regions, categories, and sub-categories
   - Top 10 cities by sales
   - Top customers and orders

---

## 📈 Key Insights
- **Consumer-driven sales** form the backbone of revenue.
- **West region** is the strongest contributor.
- **Major cities** (NYC, LA, Seattle) dominate sales.
- **IT and furniture products** are in high demand.

---

## 🚀 Conclusion
Strategic focus on **consumer markets in the West region**, **major cities**, and **IT/furniture categories** can maximize growth and profitability.

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/superstore-sales-analysis.git
