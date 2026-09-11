# E-Commerce Sales Analytics Project

## Project Overview
An end-to-end data analytics project examining e-commerce transactions to reveal revenue drivers, demographic distributions, and product performance using Python, Power BI, Git, and GitHub.

## Problem Statement
E-commerce decision-makers require clear visualization of sales performance, customer demographics, and product category trends to optimize inventory management, target marketing budgets, and grow overall revenue.

## Dataset Description
- **Source:** E-Commerce Sales Records
- **Key Fields:** Order ID, Purchase Date, Purchase Time, Product Name, Category, Customer ID, Customer Age, Customer Gender, Price, Quantity, Total Sales.

## Tools Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn):** Exploratory Data Analysis (EDA) and data cleaning.
- **Power BI Desktop:** DAX calculations, interactive reporting, KPI card generation, and dashboard layout.
- **Git & GitHub:** Version control and documentation hosting.

## Data Cleaning & Transformation
- Handled missing values and verified data consistency across transactional records.
- Formatted `Purchase Date` into structured date hierarchies for time-series analysis.
- Evaluated total sales against unit price and quantity metrics to ensure calculation accuracy.

## Visualizations & Dashboard Layout
*(Upload `dashboard_screenshot.png` to your repo and link it here)*
- **3 KPI Cards:** Total Revenue ($302.79M), Total Units Sold (549K), Average Order Value ($3.03K).
- **Trend Visual:** Line Chart displaying Sales Trend over time.
- **Category Performance:** Horizontal Bar Chart comparing total revenue across Product Categories (Clothing, Books, Home & Kitchen, Toys, Electronics).
- **Demographics & Behavior:** Donut Chart showing revenue split by Gender (Male vs. Female) and Column Chart analyzing Age metrics against total expenditure.
- **Interactive Slicers:** Date selection slicer for custom dynamic filtering.

## Key Insights
1. **Strong Overall Revenue:** The platform achieved a total revenue of **$302.79M** across **549K total units sold**.
2. **High Average Spend:** The Average Order Value (AOV) stands strong at **$3.03K** per transaction.
3. **Gender Revenue Split:** Revenue distribution between Male (**50.2%**) and Female (**49.8%**) shoppers is nearly balanced.
4. **Category Distribution:** Clothing, Books, and Home & Kitchen lead in overall order volume and steady performance.
5. **Age Demographics:** Purchasing power is evenly spread across age demographics, providing opportunities for age-targeted promotions.

## Business Recommendations
1. **Bundle Low-Performing Categories:** Implement cross-category bundling (e.g., pairing Books or Toys with high-value Electronics) to elevate transaction sizes.
2. **Demographic Targeted Campaigns:** Leverage the balanced male-to-female split by launching gender-tailored seasonal promotional campaigns.

## Project Presentation
A PDF copy of the project presentation summarizing methodology, key findings, and recommendations is included in the root directory as `ecommerce_analytics_presentation.pdf`.

