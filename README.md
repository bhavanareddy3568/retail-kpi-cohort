# 🛍️ Retail Sales Analysis with SQL & Python

This project analyzes a retail sales dataset from Kaggle using **SQL (DuckDB)** and **Python**.  
It demonstrates how to perform **data exploration, business KPIs, and customer behavior analysis** step by step.

---

## 📂 Project Structure
retail-sales-project/
│── notebooks/
│ └── 01_EDA.ipynb # Python exploratory data analysis (EDA) with charts
│
│── sql/
│ └── queries.sql.txt # SQL queries for KPIs & analysis
│
│── results/
│ ├── q1.csv
│ ├── q2.csv
│ └── ... # Outputs from SQL queries
│
│── README.md # Project documentation


**Skills demonstrated:** SQL (window functions, CTEs), DuckDB, Python (pandas, seaborn, matplotlib), cohort analysis, hypothesis testing, dashboard-ready visualizations.

## Dataset
Source: [Kaggle / UCI -- Retail sales dataset] (https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)
The dataset contains **retail sales transactions** with the following columns:
- `Transaction ID`
- `Date`
- `Customer ID`
- `Gender`
- `Age`
- `Product Category`
- `Quantity`
- `Price per Unit`
- `Total Amount`

### SQL Queries
The SQL file (`queries.sql.txt`) includes 12 queries, such as:
1. Total Revenue  
2. Number of Orders & Customers  
3. Monthly Revenue Trends  
4. Daily Sales Trends  
5. Top Product Categories  
6. Revenue by Gender  
7. Revenue by Age Groups  
8. Average Order Value (AOV)  
9. Repeat vs. One-time Customers  
10. Cohort Analysis (Retention)  
11. Top Spending Customers  
12. RFM Analysis  

Each query result is exported to the `results/` folder as CSV.

### Python EDA
The Jupyter notebook (`01_EDA.ipynb`) covers:
- Data cleaning & preprocessing  
- Exploratory visualizations (sales trends, customer segmentation, product analysis)  
- Charts & insights  

## ⚙️ Tools & Technologies
- **Python** (pandas, matplotlib, seaborn, duckdb)  
- **SQL (DuckDB engine inside Jupyter)**  
- **Jupyter Notebook**  
- **GitHub** for version control  

## How to run (local)
1. Clone/download this repo.  
2. Open `notebooks/01_EDA.ipynb` in Jupyter Notebook.  
3. Ensure you have DuckDB installed:  
   ```bash
   pip install duckdb
   
## Key findings 
- Top product categories drive the majority of revenue.
- Younger customers (<35) spend more frequently, while older groups spend higher per order.
- Repeat customers contribute significantly to long-term revenue.
- Cohort analysis highlights customer retention over time.
