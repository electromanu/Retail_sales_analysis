# Retail Sales & Profit Analysis

## 📊 Project Overview

An interactive Power BI dashboard developed to analyze retail sales, profit, product performance, and monthly sales trends.

The project focuses on understanding how sales and profit vary across product categories and products, while providing interactive filters for exploring the business performance.

---

## 🎯 Business Problem

The business has retail transaction data containing information about orders, customers, products, categories, sales, quantity, discounts, and profit.

The objective of this project is to transform the raw sales data into meaningful business insights and create an interactive dashboard that helps understand:

- Overall sales performance
- Overall profit performance
- Monthly sales trends
- Product performance
- Category performance
- Sales and profit contribution

---

## 🎯 Objectives

- Analyze total sales and profit
- Identify the highest-performing product categories
- Identify products generating the highest sales and profit
- Analyze monthly sales trends
- Compare sales and profit across categories
- Analyze product-level performance
- Create an interactive Power BI dashboard

---

## 🗂️ Dataset

The dataset contains **300 retail orders** and includes:

- Order ID
- Order Date
- Customer Name
- City
- Category
- Product Name
- Quantity
- Unit Price
- Discount
- Sales
- Profit

### Analytical Metrics

The main metrics used in the dashboard are:

- Total Sales
- Total Profit
- Total Quantity
- Monthly Sales
- Category Sales
- Category Profit
- Product Sales
- Product Profit

---

## 🧹 Data Preparation

The dataset was checked and prepared before visualization.

Key data-quality checks included:

- Checked for missing values
- Checked data types
- Reviewed category naming inconsistencies
- Checked sales and profit values
- Checked quantity values
- Checked discount values
- Checked for duplicate order IDs
- Validated date fields
- Reviewed negative profit records

The dataset contains some missing values, particularly in City, Quantity, Discount, Sales, and Profit, which were considered during the analysis.

---

## 🔍 Business Questions

### Sales Performance

1. What are the total sales?
2. How do sales change by month?
3. Which category generates the highest sales?
4. Which products generate the highest sales?

### Profit Performance

1. What is the total profit?
2. Which category generates the highest profit?
3. Which products generate the highest profit?
4. Which products have negative profit?

### Product Performance

1. Which products contribute most to sales?
2. Which products contribute most to profit?
3. Are the highest-selling products also the highest-profit products?

---

## 📌 Key KPIs

The dashboard contains the following KPIs:

| KPI | Value |
|---|---:|
| Total Sales | $4.07M |
| Total Profit | $3.74M |
| Total Quantity | 1,427 |

---

## 📈 Sales Analysis

### Monthly Sales

Sales varied across the analyzed months.

The highest monthly sales occurred in **June**, with approximately:

**$472.49K**

The lowest monthly sales occurred in **October**, with approximately:

**$298.16K**

This shows a noticeable difference between the highest and lowest monthly sales in the dataset.

---

## 🏷️ Category Analysis

Sales and profit were analyzed across product categories.

| Category | Sales | Profit |
|---|---:|---:|
| Electronic | $1.31M | $1.21M |
| Furniture | $0.94M | $0.87M |
| Furniture* | $0.93M | $0.85M |
| Office Supplies | $0.89M | $0.82M |

> *The raw dataset contains both `Furniture` and `Furn` as category values. These should be standardized before treating them as separate business categories.

The electronic category has the highest sales and profit among the recorded category values.

---

## 🖥️ Product Analysis

The product-level analysis shows the following sales and profit results:

| Product | Sales | Profit |
|---|---:|---:|
| Monitor | $819.98K | $751.13K |
| Printer | $748.01K | $691.18K |
| Laptop | $691.91K | $643.98K |
| Mouse | $684.01K | $628.88K |
| Desk | $591.79K | $540.51K |
| Chair | $533.16K | $487.84K |

### Key Product Insight

**Monitor** generated the highest sales and profit among the products in the dataset:

- Sales: **$819.98K**
- Profit: **$751.13K**

**Chair** had the lowest sales and profit among the listed products:

- Sales: **$533.16K**
- Profit: **$487.84K**

---

## ⚠️ Profitability Analysis

The dataset contains **4 orders with negative profit**.

These records indicate transactions where the recorded profit was below zero and may require further investigation.

Possible areas for further analysis include:

- Discount levels
- Product
- Category
- Order value
- Unit price

---

## 📊 Dashboard

The Power BI dashboard provides an interactive view of:

- Total Sales
- Total Profit
- Total Quantity
- Monthly Sales
- Sales by Category
- Profit by Category
- Product Sales
- Product Profit

### Interactive Filters

The dashboard includes filters for:

- Category
- Product Name
- City
- Order Date

<img width="1317" height="827" alt="image" src="https://github.com/user-attachments/assets/6c184d52-98d8-4885-ac69-b64914ad4c38" />


---

## 💡 Key Insights

### 1. Strong overall sales and profit

The dataset contains approximately:

- **$4.07M in total sales**
- **$3.74M in total profit**

---

### 2. June recorded the highest monthly sales

June generated approximately **$472.49K** in sales, making it the highest-sales month in the dataset.

---

### 3. October recorded the lowest monthly sales

October generated approximately **$298.16K** in sales.

This represents a substantial difference compared with the June peak.

---

### 4. Electronic products have the highest category-level sales

The electronic category recorded approximately:

**$1.31M in sales**

and

**$1.21M in profit**

among the category values in the dataset.

---

### 5. Monitor is the strongest individual product by sales

Monitor generated approximately:

**$819.98K in sales**

and

**$751.13K in profit**.

---

### 6. Negative-profit transactions require investigation

Four transactions have negative recorded profit.

These transactions can be investigated further to understand whether discounts, pricing, or specific products contributed to the losses.

---

## 🛠️ Tools Used

### Excel
- Data inspection
- Data preparation
- Data-quality checks

### Power BI
- Data visualization
- KPI development
- Interactive dashboard
- Sales and profit analysis
- Business insight generation

---

## ⚠️ Data Limitations

The dataset provides information about sales transactions, products, categories, customers, and financial metrics.

However, it does not contain additional information such as:

- Customer acquisition cost
- Marketing expenditure
- Inventory levels
- Competitor pricing
- Delivery costs
- Customer satisfaction
- Customer retention

Therefore, the analysis focuses specifically on the sales and profit patterns available in the dataset.

---

## 📌 Conclusion

This project demonstrates how retail transaction data can be cleaned, analyzed, and transformed into an interactive Power BI dashboard.

The analysis identifies monthly sales patterns, category-level performance, product-level performance, and negative-profit transactions.

The dashboard allows users to interactively explore sales and profit performance using category, product, city, and date filters.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Preparation
- Exploratory Data Analysis
- Business Question Formulation
- KPI Analysis
- Sales Analysis
- Profit Analysis
- Data Visualization
- Power BI
- Excel
- Business Insight Generation
