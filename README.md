# Consumer Sales Dashboard | Power BI

### Dashboard Link
[View Interactive Power BI Dashboard](https://app.powerbi.com/links/A2q8Kna7sP?ctid=61363c43-8420-43ca-8f82-801627e16cdf&pbi_source=linkShare)

## Problem Statement

This dashboard helps the organization understand its sales performance, product profitability, customer purchasing patterns, and discount strategies. It provides insights into sales trends, top- and bottom-performing products, total orders, and geographical sales distribution.

The dashboard enables the business to identify high-performing products, evaluate profitability, compare sales performance across different periods, and understand how discounts affect business outcomes. Interactive filters allow users to analyze sales data by product, date, customer ID, and promotion category.

The primary objective is to transform raw sales data into meaningful business insights that support better decision-making, improve profitability, and identify opportunities for business growth.

## Steps Followed

- **Step 1:** Loaded the sales dataset into Power BI Desktop.

- **Step 2:** Opened Power Query Editor to inspect the dataset and understand its structure.

- **Step 3:** Performed data profiling using Column Quality, Column Distribution, and Column Profile to identify data quality issues.

- **Step 4:** Cleaned and transformed the data using Power Query, where required, to prepare it for analysis.

- **Step 5:** Reviewed the available tables and identified the fields required for sales, profit, quantity, discount, order, product, customer, date, and city analysis.

- **Step 6:** Combined data from multiple tables where necessary using Power Query Merge and established relationships between tables in the data model, depending on the dataset structure.

- **Step 7:** Created the required data model to support accurate calculations and interactive reporting.

- **Step 8:** Created DAX measures for total sales, total profit, quantity sold, total orders, and average discount, based on the available columns.

- **Step 9:** Developed visualizations to identify the Top 5 and Bottom 5 products by sales, profit, and quantity sold.

- **Step 10:** Created sales trend visualizations to analyze performance over daily, monthly, quarterly, and yearly periods.

- **Step 11:** Analyzed the relationship between sales and profit to understand business performance and profitability.

- **Step 12:** Implemented period comparison analysis to compare sales and profit between two user-selected periods.

- **Step 13:** Created discount analysis visuals to calculate and compare the average discount offered across different discount categories.

- **Step 14:** Created KPI cards to display the total number of orders and other key business metrics.

- **Step 15:** Developed order-level analysis to display sales, profit, and discount for selected orders.

- **Step 16:** Created city-wise sales visualizations to understand geographical sales performance.

- **Step 17:** Added interactive slicers for Product, Date, Customer ID, and Promotion Category to enable dynamic analysis.

- **Step 18:** Applied formatting, visual interactions, titles, and a consistent theme to improve dashboard readability and usability.

- **Step 19:** Published the completed report to Power BI Service to make the dashboard accessible online.

## DAX Measures

The following are example DAX measures for the project. Update the table and column names according to your actual dataset.

### 1. Total Sales

```dax
Total Sales =
SUM(Sales[Sales])
```

### 2. Total Profit

```dax
Total Profit =
SUM(Sales[Profit])
```

### 3. Total Quantity Sold

```dax
Total Quantity Sold =
SUM(Sales[Quantity])
```

### 4. Total Orders

```dax
Total Orders =
DISTINCTCOUNT(Sales[Order ID])
```

### 5. Average Discount

```dax
Average Discount =
AVERAGE(Sales[Discount])
```

*Note: These examples assume a table named `Sales` with the corresponding columns. If your dataset uses different names or stores discounts differently, adjust the formulas accordingly.*

## Dashboard Requirements

### 1. Product Performance Analysis

- Identify the Top 5 products by sales, profit, and quantity sold.
- Identify the Bottom 5 products by sales, profit, and quantity sold.
- Compare product performance to identify opportunities for improvement.

### 2. Sales Trend Analysis

- Analyze sales trends at daily, monthly, quarterly, and yearly levels.
- Identify changes in sales performance over time.
- Understand periods of growth or decline.

### 3. Sales and Profit Analysis

- Analyze the relationship between sales and profit.
- Compare sales and profit between two selected periods.
- Evaluate overall business performance and profitability.

### 4. Discount Analysis

- Calculate the average discount offered in each discount category.
- Compare discount patterns across categories.
- Understand the potential impact of discount strategies on profitability.

### 5. Order Analysis

- Calculate the total number of orders.
- Display sales, profit, and discount for individual selected orders.
- Enable users to filter order-level results interactively.

### 6. City-wise Sales Analysis

- Analyze sales across different cities.
- Identify cities with higher sales contributions.
- Support geographical performance comparisons.

## Interactive Filters

The dashboard includes slicers for:

- Product
- Date
- Customer ID
- Promotion Category

These filters allow users to explore the data from different business perspectives and analyze specific products, customers, periods, and promotional categories.

## Insights and Business Recommendations

The dashboard is designed to help identify the following insights from the sales data:

1. **Top and Bottom Products:** Identify the products generating the highest and lowest sales, profits, and quantities sold.

2. **Sales Trends:** Understand how sales change over time and identify periods of strong or weak performance.

3. **Profitability:** Examine the relationship between sales and profit to evaluate business performance.

4. **Discount Strategy:** Compare average discounts across categories and investigate whether discounting supports profitable sales.

5. **Order Performance:** Review order-level sales, profit, and discounts to understand individual transactions.

6. **Geographical Performance:** Identify cities with strong sales and areas that may require additional business attention.

Actual numerical findings should be added after reviewing the dashboard and validating the underlying data.

## Tools and Technologies Used

- Microsoft Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Power BI Service
- Data Visualization
- Business Intelligence

## Skills Demonstrated

- Data Cleaning and Transformation
- Data Modeling and Relationships
- DAX Calculations
- Sales and Profitability Analysis
- Time Intelligence and Period Comparison
- KPI Development
- Interactive Dashboard Design
- Business Requirements Analysis

## Dashboard Preview

### Main Sales Dashboard
<img width="577" height="330" alt="Image" src="https://github.com/user-attachments/assets/51b371b4-2626-4e2e-bc22-72f0b40b6577" />

### Sales Comparison Analysis
<img width="633" height="356" alt="Image" src="https://github.com/user-attachments/assets/6696b731-1bbf-45a5-bf35-e3ff5ebcba60" />

## Conclusion

The Consumer Sales Dashboard provides an interactive approach to analyzing sales performance, product profitability, discount strategies, order metrics, and geographical trends. By combining data preparation, data modeling, DAX calculations, and interactive visualizations, the project demonstrates how Power BI can convert raw business data into actionable insights.

The dashboard can help stakeholders make informed decisions regarding product performance, pricing, promotions, and sales growth.

## Author

Developed as a Power BI project to demonstrate practical skills in data analytics, business intelligence, data modeling, and dashboard development.
