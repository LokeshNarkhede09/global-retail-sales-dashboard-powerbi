# Global Retail Sales Dashboard | Power BI

## 📌 Project Overview

The **Global Retail Sales Dashboard** is a business intelligence project developed using Microsoft Power BI to analyze retail sales, profitability, product performance, and regional trends.

The project uses the Global Superstore dataset, which contains sales transactions for Furniture, Office Supplies, and Technology products across different regions and markets.

The objective is to transform raw sales data into meaningful insights that support data-driven business decisions.

## 🎯 Business Problem

The retail business faces the following challenges:

- Profitability varies across regions.
- Discounts may reduce profit margins.
- Returned orders can affect revenue and performance.
- Sales targets differ across regions.

## 🎯 Project Objectives

- Analyze total sales, profit, and quantity sold.
- Evaluate sales and profitability by region and market.
- Identify top-performing products and customer segments.
- Understand the impact of discounts on profitability.
- Analyze returned orders and shipping costs.
- Develop an interactive dashboard to monitor key business metrics.

## 📂 Dataset Description

**Raw Dataset:** `GlobalSuperstore-Raw-Dataset.xlsx`

The project brief identifies three tables:

### 1. Orders Table
Contains sales transaction details.

Key columns:
- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Market
- Region
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit
- Shipping Cost
- Order Priority

### 2. Returns Table
Contains returned-order information.

Key columns:
- Order ID
- Returned
- Market

### 3. People Table
Contains regional sales manager information.

Key columns:
- Person
- Region

## 🛠️ Tools and Technologies

- **Microsoft Power BI** — Dashboard development and data visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — Calculated measures and KPI analysis
- **Microsoft Excel** — Raw dataset and source data preparation

## 🧹 Data Cleaning and Transformation

The project brief specifies the following data preparation tasks:

- Standardizing order dates and shipping dates.
- Converting Sales and Profit into numeric data types where required.
- Handling missing values.
- Checking and removing duplicate orders where appropriate.
- Creating calculated columns, such as Profit Margin and Returned Flag, if required.

## 📊 Key Performance Indicators (KPIs)

The project requirements include the following KPIs:

- **Total Sales** — Overall sales generated.
- **Total Profit** — Total profit earned.
- **Total Quantity** — Total units sold.
- **Profit Margin %** — Profit as a percentage of sales.
- **Return Rate %** — Percentage of orders returned.
- **Average Shipping Cost** — Average shipping cost per transaction.
- **Top 10 Products by Sales** — Products ranked by sales performance.

## 📈 Dashboard Visualizations

The project brief proposes the following visualizations:

- **KPI Cards:** Total Sales, Total Profit, Profit Margin %, and Return Rate %.
- **Line Chart:** Monthly Sales Trend.
- **Bar Chart:** Sales by Region.
- **Donut/Pie Chart:** Customer Segment Contribution.
- **Bar Chart:** Top 10 Products by Sales.
- **KPI/Gauge:** Sales vs. Target, where valid target data is available.

## 🔍 Interactive Features

The project requirements include:

- Slicers for Year, Region, Segment, and Category.
- Drill-through analysis from Region to Product to Customer.
- Conditional formatting to highlight negative profits.

## 💡 Business Questions

This project aims to investigate the following questions:

1. Which regions have the highest and lowest profits?
2. Are discounts associated with lower profitability?
3. Which customer segments are the most profitable?
4. How many orders are returned in each region?
5. Which products generate the highest sales?
6. Which shipping modes are most cost-effective?
7. How does performance vary across regional sales managers?

## 🚀 How to Use This Project

1. Download or clone this repository.
2. Install Microsoft Power BI Desktop.
3. Open `Global-Retail-Sales-Dashboard.pbix`.
4. If prompted, update the source path to `GlobalSuperstore-Raw-Dataset.xlsx`.
5. Refresh the dataset if necessary.
6. Explore the available charts, KPIs, and filters.

## 📁 Repository Structure

```text
global-retail-sales-dashboard-powerbi/
│
├── GlobalSuperstore-Raw-Dataset.xlsx
├── Global-Retail-Sales-Dashboard.pbix
└── README.md
```

## 📊 Key Findings and Recommendations

- **Total Sales:** 12,642,501.91
- **Total Profit:** 1,467,457.29
- **Total Quantity Sold:** 178,312 units
- **Profit Margin:** 11.61%
- **Total Unique Orders:** 25,035
- **Returned Orders:** 1,172
- **Return Rate:** 4.68%
- **Average Shipping Cost per Row:** 26.38
- **Top Performing Region by Profit:** Central — 311,403.98 profit.
- **Top-Selling Product:** Apple Smart Phone, Full Size — 86,935.78 in sales.
- **Most Profitable Category:** Technology — 663,778.73 profit.
- **Lowest Average Shipping Cost:** Standard Class — 19.97 per transaction row.

### Recommendations

1. Investigate why the Southeast Asia region generated only 17,852.33 in profit despite 884,423.20 in sales.
2. Analyze discount levels and their relationship with profitability before changing discount policies.
3. Examine returned orders to identify opportunities to reduce returns.
4. Evaluate Technology products for opportunities to improve sales and profitability.
5. Compare shipping costs and delivery performance when selecting shipping methods.


## 🏁 Conclusion

This project demonstrates the use of Power BI, Power Query, DAX, and Excel for retail sales analysis and business intelligence reporting.

It provides a foundation for understanding sales trends, profitability, product performance, and regional operations through data visualization.

## 👨‍💻 Author

**Lokesh Narkhede**

- GitHub: https://github.com/LokeshNarkhede09
- LinkedIn: www.linkedin.com/in/lokeshnarkhede
