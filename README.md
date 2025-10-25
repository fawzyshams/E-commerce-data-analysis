# 📊 E-Commerce Sales Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=flat-square)

---

## 🔹 Overview

This project presents an **E-Commerce Sales Analysis Dashboard** created in Power BI.  
The dashboard provides comprehensive insights into sales performance, customer growth, payment trends, and product analytics.  
It combines **Star Schema modeling**, **DAX measures**, and **interactive visualizations** to help decision-makers track key business metrics.

---

## 🔹 Dashboard Highlights

- **Total Sales**: $3M (↑ 9.36%)
- **Total Orders**: 2K (↑ 9.64%)
- **Total Customers**: 909 (↑ 4.36%)
- **Average Order Value (AVO)**: $1.35K (↓ 0.26%)
- **Top Product**: Laptop - highest revenue generator
- **Dominant Category**: Electronics (88.71% of sales)
- **Payment Methods**: Balanced distribution across Bank Transfer, PayPal, and Credit Card

---

## 🔹 Key Insights

### 📈 Sales Performance
- **Product Leaders**: Laptops and Smartphones drive majority of revenue
- **Growth Trend**: Positive sales growth of 9.36% compared to previous period
- **Category Split**: Electronics dominate with 88.71%, Accessories at 11.29%

### 💳 Payment Analysis
- **Payment Distribution**:
  - Credit Card: 33.8%
  - PayPal: 33.12%
  - Bank Transfer: 33.08%
- **Payment Status**:
  - Failed: 34.45% (needs attention)
  - Completed: 33.11%
  - Pending: 32.44%

### 👥 Customer Insights
- **Customer Base**: 909 active customers with steady 4.36% growth
- **Order Volume**: 2K orders processed successfully
- **AVO Trend**: Slight decline of 0.26% indicates potential for upselling strategies

### 📦 Product Performance
- **Top Performers**: Laptop, Smartphone
- **Mid-Range**: Tablet, Smartwatch
- **Accessories**: Headphones showing consistent demand

---

## 🔹 Data Processing Workflow

### Step 1: Data Cleaning
- ✅ Removed duplicate records
- ✅ Handled missing values
- ✅ Standardized date formats
- ✅ Validated customer and product IDs
- ✅ Fixed inconsistent payment status entries

### Step 2: Star Schema Modeling
- **Fact Table**: Fact_Sales (transactional data)
- **Dimension Tables**:
  - Dim_Date (time hierarchy)
  - Dim_Customer (customer details)
  - Dim_Product (product information)
  - Dim_Geography (location data)
  - Dim_Payment (payment details)

### Step 3: DAX Measures
Created advanced calculations for KPIs, growth percentages, and trend analysis.

---

## 🔹 Files Included

- `ec_raw_data.xlsx` → Original raw dataset
- `cleaned_data.xlsx` → Cleaned and processed data
- `ecommerce_dashboard.pbix` → Power BI dashboard file
- `dashboard_screenshot.png` → Dashboard preview image
- `README.md` → Project documentation

---

## 🔹 Preview

Here is a snapshot of the dashboard:

![E-Commerce Dashboard](E commerce.png)

---

## 🔹 How to Use

1. **Download** and open `ecommerce_dashboard.pbix` in Power BI Desktop (latest version recommended).
2. **Explore** interactive filters, slicers, and drill-down capabilities.
3. **Refresh** data connection if needed by updating the data source path.
4. **Interact** with visualizations by clicking on charts to cross-filter other visuals.
5. **Use monthly filters** on the left sidebar to analyze specific time periods.

---

## 🔹 Technologies Used

- **Power BI Desktop** - Dashboard creation and visualization
- **Power Query** - Data transformation and ETL
- **DAX** - Advanced calculations and measures
- **Excel** - Raw data source
- **Star Schema** - Dimensional modeling approach

---
