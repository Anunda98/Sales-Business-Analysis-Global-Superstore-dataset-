# Sales Business Analysis – Global Superstore Dataset

## Project Overview

This project analyzes the Global Superstore dataset to evaluate business performance across sales, profit, customer segments, and regions. The objective is to identify key business trends, inefficiencies, and opportunities for improvement through exploratory data analysis (EDA).

The analysis focuses on understanding revenue behavior, profitability patterns, customer concentration, and regional performance to support data-driven business decisions.

---

## Dataset Overview

- Dataset: Global Superstore
- Records: 51,290 rows
- Features: 27 columns
- Key fields:
  - Sales
  - Profit
  - Category
  - Region
  - Order Date
  - Customer Name
  - Product Name

---

## Data Cleaning Process

The dataset was cleaned and prepared for analysis through the following steps:

- Removed incorrectly encoded column (`è®°å½æ°`)
- Standardized column names
- Converted date fields to datetime format
- Ensured numerical consistency for sales and profit columns
- Created a new feature: profit_margin = profit / sales
- Checked and handled duplicates
- Saved cleaned dataset in the processed folder

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

- Monthly sales trend analysis
- Profit by category
- Profit by region
- Sales by region
- Sales vs profit relationship analysis
- Top customers by sales
- Identification of top loss-making products

---

## Key Business Insights

### 1. Monthly Sales Trend
Sales show a consistent long-term upward trend, indicating overall business growth. However, recurring declines are observed in January, suggesting seasonal fluctuations in demand.

### 2. Profit by Category
Profit distribution is uneven across product categories. One category dominates profitability while others contribute less, indicating dependency on a limited product mix.

### 3. Profit by Region
Profitability varies significantly across regions. Some regions generate strong profits while others underperform despite contributing to sales.

### 4. Sales by Region
Sales are concentrated in a few regions, indicating uneven market penetration and dependency on high-performing areas.

### 5. Sales vs Profit Relationship
High sales do not always correspond to high profit. Some transactions with strong sales volumes show low or negative profitability.

### 6. Top Customers
A small group of customers contributes a large portion of total revenue, indicating customer concentration risk.

### 7. Top Loss-Making Products
Certain products consistently generate losses, negatively affecting overall profitability and indicating inefficiencies in pricing or cost structure.

---

## Business Recommendations

- Introduce targeted marketing campaigns in low-sales months (especially January)
- Diversify product profitability across categories to reduce dependency
- Investigate and improve low-performing regions
- Review pricing and discount strategies to improve profit margins
- Strengthen customer retention strategies while diversifying customer base
- Remove or re-evaluate consistently loss-making products

---

## Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Conclusion

This analysis highlights key drivers of sales and profitability in the Global Superstore dataset. The insights can help guide strategic decisions in pricing, customer management, regional expansion, and product optimization.