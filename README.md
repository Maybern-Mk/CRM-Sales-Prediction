# CRM-Sales-Prediction

📊 CRM Sales Opportunities Analysis

This project performs exploratory data analysis (EDA) on a CRM sales dataset to understand account characteristics, sales performance, revenue distribution, and workforce patterns using Python.

The analysis combines account-level information with sales pipeline data and visualizes insights using both static (Matplotlib/Seaborn) and interactive (Plotly) charts.

🗂️ Dataset Used

accounts.csv

Contains company-level details such as sector, revenue, employee count, and parent company.

sales_pipeline.csv

Contains sales opportunity details including product, engagement dates, close dates, and deal values.

🛠️ Technologies & Libraries

Python

Pandas – data loading, cleaning, merging, and aggregation

Matplotlib & Seaborn – static data visualizations

Plotly Express – interactive charts

Jupyter Notebook

🔄 Data Processing Steps

Data Loading

CSV files are loaded using Pandas.

Missing Value Handling

Checked missing values in both datasets.

Dropped rows with critical missing fields such as:

subsidiary_of

account

engage_date

close_date

close_value

Data Merging

Accounts and sales pipeline data merged using a left join on the account column.

📈 Analysis Performed
Revenue Insights

Total revenue by:

Sector

Product

Average revenue per product

Visualizations

Bar Chart – Average revenue by product

Histogram / Distribution Plot – Revenue distribution

Pie Chart – Revenue share by product

Distribution Plot – Employee count distribution

Bar Plot – Employees per account

Interactive Dashboards (Plotly)

Product vs employee count (bar chart)

Employee distribution across sectors (pie chart)

📊 Key Visual Outputs

Static charts for quick insight and reporting

Interactive Plotly charts for deeper exploration and presentations

📦 Installation & Setup
pip install pandas matplotlib seaborn plotly
pip install "notebook>=5.3" "ipywidgets>=7.5"

🚀 How to Run

Place the CSV files in the correct directory (or update file paths).

Open the Jupyter Notebook.

Run cells sequentially to:

Clean data

Merge datasets

Generate insights and visualizations

🎯 Objective

The goal of this project is to:

Understand sales performance trends

Identify high-performing products and sectors

Analyze workforce size vs business outcomes

Practice real-world CRM data analysis using Python
