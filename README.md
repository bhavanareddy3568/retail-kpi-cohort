# retail-kpi-cohort
Exploratory analysis and cohort/retention analytics on a retail transactions dataset. Uses SQL (DuckDB) and Python (pandas, seaborn) to compute KPIs, segment customers by gender/age, and produce a cohort retention matrix. Includes notebooks, SQL scripts, charts, and reproducible instructions.

# Retail Sales KPI & Cohort Analysis

**Short summary:** SQL + Python analysis of retail transactions to compute KPIs, product & demographic trends, cohort retention, and business recommendations.

**Skills demonstrated:** SQL (window functions, CTEs), DuckDB, Python (pandas, seaborn, matplotlib), cohort analysis, hypothesis testing, dashboard-ready visualizations.

## Dataset
Source: [Kaggle / UCI -- Retail sales dataset] (https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)
Columns expected:
`Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, Total Amount`
Place the CSV file as `data/retail_sales_dataset.csv`.

## Deliverables
- `notebooks/01_EDA.ipynb` — reproducible EDA & analysis
- `sql/queries.sql` — SQL used for KPI calculations & cohort analysis
- `results/charts/` — exported charts (PNG)
- Optional: Tableau Public dashboard: <link>

## How to run (local)
1. Create Python venv and install `requirements.txt`.
2. Put `data/retail_sales_dataset.csv` inside `data/`.
3. Open `notebooks/01_EDA.ipynb` and run cells.
4. Run SQL queries using DuckDB or your SQL engine: `duckdb -c "SELECT * FROM read_csv_auto('data/retail.csv') LIMIT 5;"`

## Key findings (examples)
- Top 5 products accounted for ~X% of revenue.
- Retention drops significantly after month 6; consider targeted retention offers.

## Author
Bhavana Reddy — MS Statistical Data Science (FSU, Dec 2025)  
[LinkedIn](your-link) | [Portfolio](your-site) | [Contact email]
