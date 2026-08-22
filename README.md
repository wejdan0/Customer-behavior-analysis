
# Data Analytics Project

## Overview

This project demonstrates an end-to-end data analytics workflow, from raw dataset exploration and cleaning to SQL analysis, interactive visualization, and business reporting.

The goal is to transform raw data into meaningful insights using Python, SQL, Power BI, and presentation/reporting tools.

## Dataset

The project uses a structured dataset containing business-related records for analysis.

The dataset is:

* Loaded and explored using Python
* Cleaned and prepared for analysis
* Stored in a relational database for SQL analysis
* Connected to Power BI for dashboard development

## Tools

* **Python** — Data loading, exploration, cleaning, and EDA
* **Pandas** — Data manipulation and analysis
* **Matplotlib / Seaborn** — Data visualization
* **PostgreSQL / MySQL / SQL Server** — Database storage and SQL analysis
* **SQL** — Data querying and business analysis
* **Power BI** — Interactive dashboard and data visualization
* **Gamma** — Presentation creation
* **Jupyter Notebook / VS Code** — Development environment

## Project Steps

### 1. Load the Data

The dataset is imported into Python using Pandas and reviewed to understand its structure, columns, data types, and overall quality.

### 2. Exploratory Data Analysis

EDA is performed to identify:

* Dataset structure and key variables
* Missing values
* Duplicate records
* Outliers
* Data distributions
* Relationships and trends between variables

### 3. Data Cleaning

The dataset is prepared for analysis by:

* Handling missing values
* Removing duplicates
* Correcting data types
* Standardizing values and formats
* Addressing inconsistent or invalid records

### 4. SQL Analysis

The cleaned data is loaded into a relational database and analyzed using SQL.

Queries are used to answer business questions, calculate KPIs, aggregate data, identify trends, and compare different categories or segments.

### 5. Power BI Dashboard

The analyzed data is connected to Power BI to create an interactive dashboard containing:

* Key performance indicators
* Charts and visualizations
* Trend analysis
* Category/segment comparisons
* Interactive filters and slicers

### 6. Report

A written report summarizes the project methodology, key findings, important trends, and business insights identified throughout the analysis.

### 7. Presentation

A presentation is created using Gamma to communicate the project, methodology, findings, and recommendations in a concise and professional format.

## Dashboard

The Power BI dashboard provides an interactive overview of the main KPIs and trends discovered during the analysis.

**Dashboard Preview:**
*Add Power BI dashboard screenshot here.*

## Results

The analysis produced actionable insights by combining exploratory analysis, SQL-based investigation, and interactive visualization.

Key outcomes include:

* Identification of important trends and patterns
* Analysis of key business performance indicators
* Identification of high- and low-performing segments
* Data-driven findings that can support business decision-making

Detailed findings and recommendations are available in the project report and presentation.

## How to Run

### Python Analysis

1. Clone or download the repository.
2. Open the project in Jupyter Notebook or VS Code.
3. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy
```

4. Place the dataset in the appropriate project folder.
5. Run the Python notebook/script to perform data loading, EDA, and cleaning.

### SQL Analysis

1. Set up PostgreSQL, MySQL, or SQL Server.
2. Create the required database.
3. Import the cleaned dataset.
4. Run the SQL scripts included in the project.
5. Review the query results and KPIs.

### Power BI

1. Open the `.pbix` file in Power BI Desktop.
2. Update the data source if required.
3. Refresh the dataset.
4. Explore the interactive dashboard.

## Project Structure

```text
data-analytics-project/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── presentation.pdf
│
└── README.md
```

## Skills Demonstrated

* Data Cleaning & Preparation
* Exploratory Data Analysis
* Python & Pandas
* SQL
* Relational Databases
* Data Visualization
* Power BI Dashboard Development
* Business Intelligence
* Data Storytelling
* Reporting & Presentation

## Conclusion

This project demonstrates a complete data analytics workflow, combining **Python, SQL, Power BI, and business reporting** to transform raw data into clear, actionable insights.
