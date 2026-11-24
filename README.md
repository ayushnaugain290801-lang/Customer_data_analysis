# 📊 Customer Behavior Analysis Project – End-to-End Data Analysis

## 📌 Overview
This project demonstrates an end-to-end data analytics workflow, starting from raw dataset loading and data exploration to data cleaning, SQL-based analysis, and interactive dashboard development.

The objective is to extract meaningful insights from the data, identify key trends and patterns, and present findings through a Power BI dashboard to support data-driven decision-making.

## 📂 Dataset
- **Name:** Customer_shopping_behavior
- **Format:** CSV
- **Description:** The dataset contains customer info like id, item, category, purchase amount, discount applied and other column.
- **Purpose:** To analyze the data, identify trends, and generate actionable business insights.

## 🛠️ Tools & Technologies
- **Python:** Data loading, exploration, and preprocessing.
- **Pandas & NumPy:** Data manipulation and cleaning.
- **Matplotlib & Seaborn:** Exploratory Data Analysis (EDA) and visualization.
- **MySQL:** Data storage and querying.
- **SQL:** Data analysis using filtering, aggregation, joins, and subqueries.
- **Power BI:** Interactive dashboard development and data visualization.
- **Jupyter Notebook:** Python development and analysis.

## 🔄 Project Workflow

### 1. Data Loading
- Imported the dataset into Python using Pandas.
- Inspected the dataset structure, dimensions, and data types.
- Reviewed initial records to understand the available information.

### 2. Exploratory Data Analysis (EDA)
- Analyzed data distributions and statistical summaries.
- Identified trends, patterns, and relationships.
- Used visualizations to understand key variables.
- Checked for missing values, duplicates, and outliers.

### 3. Data Cleaning & Preprocessing
- Handled missing and duplicate values.
- Corrected inconsistent data types.
- Standardized column names and data formats.
- Addressed data inconsistencies.
- Prepared the cleaned dataset for further analysis.

### 4. SQL Analysis Using MySQL
- Imported the cleaned dataset into MySQL.
- Performed SQL queries to extract meaningful insights.
- Used SQL concepts such as:
  - SELECT, WHERE, ORDER BY
  - GROUP BY and HAVING
  - Aggregate Functions
  - JOIN Operations
  - Subqueries and CTEs
  - Window Functions (where applicable)
- Answered business-related questions using SQL.

### 5. Power BI Dashboard
- Connected the analyzed data to Power BI.
- Created interactive visualizations and KPI cards.
- Designed charts, tables, and filters for better data exploration.
- Developed an interactive dashboard to communicate key findings.

## 📈 Dashboard & Key Results

The Power BI dashboard provides a visual summary of the analysis, highlighting important metrics, trends, and business insights.

**Key Highlights:**
- Identified important trends and patterns in the dataset.
- Analyzed key performance indicators (KPIs).
- Compared performance across different categories.
- Presented actionable insights through interactive visualizations.

## 📁 Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
```

## ▶️ How to Run

### Prerequisites
Make sure you have the following installed:
- Python 3.x
- Jupyter Notebook
- MySQL Server
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone <repository-url>
cd Data-Analytics-Project
```

### Step 2: Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Run the Python Notebook
- Open Jupyter Notebook.
- Navigate to the `notebooks` folder.
- Open `data_analysis.ipynb`.
- Run the cells sequentially to perform EDA and data cleaning.

### Step 4: Run SQL Queries
- Open MySQL Workbench.
- Create a database and import the cleaned dataset.
- Open `analysis_queries.sql`.
- Execute the queries to explore and analyze the data.

### Step 5: Open Power BI Dashboard
- Open Power BI Desktop.
- Load the `.pbix` file from the `dashboard` folder.
- Update the data source connection if required.
- Refresh the data to view the dashboard.

## 🎯 Conclusion
This project demonstrates practical skills in data analysis, data cleaning, SQL querying, and business intelligence reporting.

It showcases the ability to work with raw datasets, transform data into meaningful insights, and communicate findings through interactive dashboards.

**Key Skills Demonstrated:** Python | Pandas | NumPy | EDA | Data Cleaning | MySQL | SQL | Power BI | Data Visualization

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
