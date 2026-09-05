# Superstore Sales & Profitability Analytics Dashboard — Excel

## 📊 Project Overview

An **Excel-only Business Analytics project** built using Superstore transactional data from **2011 to 2014**.

The project transforms transactional sales data into a structured analytical workbook and an interactive management dashboard to evaluate **sales performance, profitability, customer behavior, product performance, regional trends, discount impact, shipping performance, and business growth opportunities**.

The complete analysis is developed using **Microsoft Excel**, without SQL, Python, Power BI, or other external analytics tools.

---

## 🎯 Business Objective

The primary objective of this project is to analyze Superstore sales data and generate actionable business insights by identifying:

- Sales and profit trends over time
- High-performing and low-performing products
- Customer and segment performance
- Regional and market profitability
- Discount impact on profitability
- Shipping and delivery performance
- Seasonal sales patterns
- Business growth opportunities and profitability risks

---

## 📁 Dataset Overview

| Metric | Value |
|---|---:|
| Transaction Line Items | 51,290 |
| Unique Orders | 25,035 |
| Customers | 795 |
| Product Names | 3,788 |
| Product IDs / SKUs | 10,292 |
| Countries | 147 |
| Markets | 7 |
| Regions | 13 |
| Categories | 3 |
| Sub-Categories | 17 |
| Analysis Period | 2011–2014 |
| Total Sales | $12.64M |
| Total Profit | $1.47M |
| Overall Profit Margin | 11.6% |

---

## 🛠️ Tools & Excel Techniques

### Tools
- Microsoft Excel

### Excel Techniques Used
- Excel Tables
- Structured References
- SUMIFS
- COUNTIFS
- IF
- IFERROR
- UNIQUE
- FILTER
- PivotTables
- PivotCharts
- Slicers
- Timeline
- Conditional Formatting
- Data Validation
- KPI Analysis
- Trend Analysis
- Profitability Analysis
- What-If Analysis
- Goal Seek
- Interactive Dashboard

---

## 📌 Key Analysis Areas

### 📈 Sales Analysis

- Yearly sales performance
- Monthly sales trends
- Quarterly performance
- Sales by category
- Sales by market
- Sales by customer segment

### 💰 Profitability Analysis

- Total profit
- Profit margin
- Profit by category
- Profit by region
- Loss-making products
- Discount vs. profitability analysis

### 📦 Product Analysis

- Top 10 products by sales
- Top 10 products by profit
- Bottom 10 products by profit
- Product-level profitability comparison

### 👥 Customer Analysis

- Top 10 customers by sales
- Top 10 customers by profit
- Customer order activity
- Customer value comparison

### 🌍 Regional & Market Analysis

- Regional sales
- Regional profit
- Regional profit margins
- Market performance

### 🚚 Operational Analysis

- Shipping mode performance
- Delivery time analysis
- Order priority
- Shipping performance

### 🔮 Scenario Analysis

- Sales growth scenarios
- Profit margin scenarios
- Incremental profit analysis
- Goal Seek for target profitability

---

# 📈 Interactive Excel Dashboard

The final dashboard provides a management-focused view of the business using:

- KPI cards
- Year slicer
- Category slicer
- Segment slicer
- Region slicer
- Order Date timeline
- Sales trend analysis
- Monthly sales trend
- Category sales and profit comparison
- Regional profit analysis
- Customer segment analysis
- Market performance
- Discount profitability analysis
- Top 10 product analysis
- Key business insights

The dashboard is designed to allow users to **filter the analysis interactively** and quickly identify major performance trends and business risks.

---

## 🔍 Key Business Insights

- **Sales grew strongly from $2.26M in 2011 to $4.30M in 2014**, showing consistent business growth over the analysis period.

- **Technology is the strongest category in terms of both sales and profit**, making it the leading contributor to overall business performance.

- **Furniture has the weakest profit margin at approximately 7%**, despite generating more than $4.1M in sales.

- **Tables is a major loss-making sub-category despite generating significant sales**, indicating the need for deeper product-level investigation.

- **Higher discount levels are associated with negative profitability**, highlighting discount management as an important profitability lever.

- **Q4 is the strongest sales period**, indicating clear seasonality that can support inventory and promotional planning.

---

## 💡 Business Recommendations

- Review high-discount transactions where profitability becomes negative.
- Investigate loss-making products, particularly within the Tables sub-category.
- Evaluate pricing, discounting, shipping costs, and product mix for weak-margin products.
- Prioritize high-margin products and profitable customer segments.
- Monitor regional profitability separately from revenue performance.
- Use seasonal demand patterns to improve inventory and promotional planning.

---

# 📷 Dashboard Preview

![Superstore Dashboard](images/dashboard.png)

---

# 📚 Workbook Preview

The workbook is organized into multiple analytical worksheets, each serving a specific stage of the analysis.

## 1. Executive Dashboard

The main interactive dashboard provides a consolidated view of sales, profitability, customer performance, regional performance, discount impact, product performance, and business trends.

![Superstore Dashboard](images/dashboard.png)

---

## 2. Data Preparation

The **Data** worksheet contains the transactional dataset along with calculated analytical fields used throughout the project.

![Data Worksheet](images/data.png)

---

## 3. KPI Calculations

The **KPI_Calculations** worksheet contains core business metrics including total sales, total profit, profit margin, unique orders, customers, average order value, delivery performance, and loss-making line items.

![KPI Calculations](images/kpi-calculations.png)

---

## 4. Pivot Table Analysis

The **Pivot_Tables** worksheet contains summary analyses covering yearly, monthly, quarterly, category, sub-category, regional, market, customer segment, shipping, and discount performance.

![Pivot Tables](images/pivot-tables.png)

---

## 5. Product Analysis

The **Product_Analysis** worksheet evaluates product performance through sales, profit, profit margin, top-performing products, and loss-making products.

![Product Analysis](images/product-analysis.png)

---

## 6. Customer Analysis

The **Customer_Analysis** worksheet compares customers by sales, profit, and order activity to identify high-value customers and profitability differences.

![Customer Analysis](images/customer-analysis.png)

---

## 7. Regional Analysis

The **Regional_Analysis** worksheet compares regional sales, profit, and profit margins to identify geographical performance differences.

![Regional Analysis](images/regional-analysis.png)

---

## 8. Trend & Seasonality Analysis

The **Trend_Analysis** worksheet evaluates yearly growth, monthly sales trends, and seasonal sales patterns across the 2011–2014 analysis period.

![Trend Analysis](images/trend-analysis.png)

---

## 9. What-If Analysis

The **What_If_Analysis** worksheet evaluates how different sales growth and profit margin assumptions can affect scenario revenue, profit, and incremental profit.

It also demonstrates Excel's **Goal Seek** capability for target-profit analysis.

![What-If Analysis](images/what-if-analysis.png)

---

## 10. Project Report

The **Report** worksheet summarizes the dataset, major business findings, analytical observations, and recommendations derived from the project.

![Project Report](images/report.png)

---

# 📂 Project Files

- [`Superstore_Sales_Profitability_Dashboard.xlsx`](./Superstore_Sales_Profitability_Dashboard.xlsx) — Complete Excel analytics workbook
- [`README.md`](./README.md) — Project documentation
- `images/` — Dashboard and worksheet preview screenshots

---

## 📁 Repository Structure

```text
superstore-sales-profitability-excel/
│
├── README.md
├── Superstore_Sales_Profitability_Dashboard.xlsx
│
└── images/
    ├── dashboard.png
    ├── data.png
    ├── kpi-calculations.png
    ├── pivot-tables.png
    ├── product-analysis.png
    ├── customer-analysis.png
    ├── regional-analysis.png
    ├── trend-analysis.png
    ├── what-if-analysis.png
    └── report.png
