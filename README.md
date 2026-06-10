# 📊 Sales & Revenue Analysis Dashboard

## Project Overview
This project analyzes retail sales data from the Superstore dataset using Python and Power BI. The goal is to identify sales trends, profitable categories, top-performing regions, and best-selling products to support business decision-making.

---

## Tools Used
- Python
- Pandas
- Jupyter Notebook
- Power BI
- Git & GitHub

---

## Dataset
- Superstore Sales Dataset
- ~10,000 Orders
- Multiple Regions, Categories, and Products

---

## Data Preparation
Performed data cleaning and feature engineering using Pandas:

- Removed missing values
- Converted Order Date to datetime format
- Created Year column
- Created Month column
- Calculated Profit Margin (%)

```python
df['profit margin'] = (df['Profit'] / df['Sales']) * 100
df['year'] = df['Order Date'].dt.year
df['Month'] = df['Order Date'].dt.month_name()
```

---

## Business Questions

1. Which region generates the highest sales?
2. Which category generates the highest profit?
3. Which products generate the most revenue?
4. How do sales change across months?
5. What is the overall profit margin?
6. How many orders were placed?

---

## Key Insights

### Sales by Region
- West Region generated the highest sales.
- South Region generated the lowest sales.

### Profit by Category
- Technology produced the highest profit.
- Furniture produced the lowest profit.

### Monthly Sales Trend
- November recorded the highest sales.
- February recorded the lowest sales.

### Top Products
- Canon imageCLASS 2200 Advanced Copier was the top-selling product.

---

## Dashboard Metrics

- Total Sales: 2.30M
- Total Profit: 286.40K
- Average Profit Margin: 12.03%
- Total Orders: 9,994

---

## Dashboard Features

- Region Filter
- Category Filter
- Year Filter
- Sales by Region
- Profit by Category
- Monthly Sales Trend
- Top Products by Sales

---

## Dashboard Preview

(Add dashboard screenshot here)

![Dashboard](dashboard.png)

---

## Project Structure

```
Sales-Revenue-Analysis/
│
├── sales.ipynb
├── cleaned_superstore.csv
├── dashboard.png
└── README.md
```

---

## Author

David V

Aspiring Data Analyst | Python | SQL | Power BI | Excel
