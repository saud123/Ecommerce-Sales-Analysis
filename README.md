# 📊 Ecommerce Sales Analysis Using Google Sheets


## ❓ 1.Problem Statement

Ecommerce businesses often struggle with scattered sales data and limited visibility into customer behavior, product performance, and seasonal trends. This leads to inefficient inventory planning, missed sales opportunities, and low customer retention.

This case study demonstrates how a data analyst used Google Sheets to analyze ecommerce sales data and extract actionable insights for decision-making in **Ecommerce Sector**

---


## 🔷 2. Objective
- Analyze ecommerce sales data to identify trends, patterns, and KPIs.
- Provide actionable insights to improve business performance.
- Showcase proficiency in Google Sheets for potential clients.

---

## 🔷 3. Dataset
**Source:**UCI Machine Learning Repository:  Online Retail Dataset (Oct 2010 – Dec 2011) 

**Columns Used:**
- InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

**Sample Entry:**
- InvoiceNo: 536365
- StockCode: 85123A
- Description: WHITE HANGING HEART T-LIGHT HOLDER
- Quantity: 6
- InvoiceDate: 01/12/2010
- UnitPrice: 2.55
- CustomerID: 17850
- Country: United Kingdom

---

## 🔷 4. Approach

### ✅ Step 1: Data Import & Cleaning
- Imported CSV into Google Sheets.
- Handled missing values.
- Formatted columns for consistency.
- Aggregated key columns for analysis.

### ✅ Step 2: Exploratory Data Analysis (EDA)
- Created new column for Total Sales Revenue : **Quantity × UnitPrice**
- Analyzed returns using negative quantities.
- Created Pivot Tables for:
  - Monthly sales trends
  - Top products by revenue
  - Top Returned prodcuts
  - Top Customers by revenue
  - Sales by country

### ✅ Step 3: KPIs & Metrics
Key metrics calculated:
- **Total Revenue**
- **Total Orders** 
- **Average Order Value** 
- **Customer Retention**
- **Return Rate (qty-based)**
- **Repeated Purchased**
- **R/L Ratio**

### ✅ Step 4: Insights & Recommendations
- Top 10 products contributed ~50% of total revenue.
- November–December had the highest sales (holiday season).
- UK and Germany accounted for ~70% of all sales.
- 8% Return Rate identified – opportunity to reduce.
- Customer segmentation can improve repeat purchases.

---

## 🔷 5. Google Sheets Template Includes:
- **Tabs**:
  - Online Retail ( Data & KPIs)
  - Pivot Tables and charts
  - Dashboard
  - Summary : Insights and recommendations.
- **Visuals**: Charts for trends, product performance, and geography.
- **Formulas**: Embedded for dynamic metrics.
---


## ✅ Solution Provided

This project solved the problem by:
- Centralizing raw sales data in **Google Sheets** for easy access and collaboration.
- Cleaning and organizing the dataset to remove inconsistencies and duplicates.
- Building interactive pivot tables, KPIs, and dashboards to:
  - Identify top-selling products
  - Detect high-return items
  - Analyze monthly sales trends
  - Understand customer behavior
- Delivering actionable insights to support smarter marketing and inventory decisions.








## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
