# 📊 Global Superstore – Power BI Dashboard

## 📝 Project Overview

This repository contains the Power BI solution for the **Global Superstore Command Center**, a graded assignment for the **Certificate Program in Data Analytics (CPDA)**. The project focuses on building an interactive dashboard that provides actionable insights into sales performance, profitability, discount strategies, customer behavior, and operational efficiency across global markets.

---

## 🎯 Business Objectives

1. **Revenue Growth**  
   Identify under-penetrated regions and product lines with high growth potential.

2. **Margin Improvement**  
   Analyze the impact of discounting on profitability and recommend optimal discount thresholds.

3. **Operational Efficiency**  
   Benchmark delivery performance to balance shipping cost vs. customer satisfaction.

4. **Customer Profiling**  
   Discover high-value customer segments among Consumer, Corporate, and Home Office.

---

## 🔍 Key Research Questions

- Which regions and product sub-categories are over/under-performing?
- What discount level maximizes volume without eroding margins?
- Is expedited shipping cost-effective in terms of repeat business or pricing power?
- Which cities experience high return rates or late shipments?
- How do seasonal trends help with inventory and promotion planning?

---

## 🧩 Data Model

- **Fact Table:** Sales Orders  
- **Dimension Tables:** Calendar, Product, Customer, Employee, Territories, Returns  

✅ Built using a **Star Schema** with relationships established via surrogate keys.

---

## 📈 Power BI Visualizations

| Page | Visual Type | Description |
|------|-------------|-------------|
| **Dashboard** | KPI Cards, Trend Lines, Heatmap | Overview of Sales & Profit by Region |
| **Category Analysis** | Drill-down Bar Chart | Category → Sub-category comparison |
| **Discount Impact** | Scatter Plot | Discount % vs. Profit Margin % |
| **Logistics** | Box & Whisker Plot | Lead Time by Region and Ship Mode |
| **Map View** | Filled Map | Profit Margin % by Country/City |
| **Segment Comparison** | Small Multiples or Tables | Consumer vs. Corporate vs. Home Office |

---

## 🧮 DAX Measures Used

- `Total Sales`
- `Total Profit`
- `Profit Margin (%)`
- `Average Discount`
- `Discount to Profit Correlation`
- `YoY Sales and Profit Growth`
- `Average Order Lead Time`

---

## ✅ Success Criteria

- All visuals are fully interactive and filter-sync enabled
- Report performance optimized to load in <5 seconds
- Provides at least **three non-obvious, data-driven insights**

---

## 📂 Project Files

| File Name | Description |
|-----------|-------------|
| `Calender.xlsx` | Calendar dimension for time-based filtering |
| `Customer Details.xlsx` | Customer dimension including segments |
| `Employee.xlsx` | Sales rep and manager info |
| `Product Details.xlsx` | Product hierarchy (Category, Sub-Category) |
| `Returns.xlsx` | Product returns for performance analysis |
| `Sales.xlsx` | Core transaction-level sales data |
| `Territories.xlsx` | Geography and region information |
| `Problem_Statement_v1.pdf` | Official assignment brief and requirements |
| `Firstname_Lastname_CPDA_Bx.pbix` | Power BI dashboard (replace with your name & batch) |

---

## 🧠 Insights & Recommendations

Here’s a sample of insights discovered through this dashboard:
- APAC region shows strong sales growth but low profit margins — optimize discounts.
- Office Supplies in EMEA have high return rates — consider reviewing quality/expectations.
- Home Office customers show highest average profit per order — tailor retention offers.

---

## 🧑‍🎓 Author

**Rohit Prakash**  
Pursuing Data Analytics Certification  
*Transitioning from Retail to Data Analytics*

![image](https://github.com/user-attachments/assets/cfe6888b-96d1-486b-837f-7842d22a56ff)
