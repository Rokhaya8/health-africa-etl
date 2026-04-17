# Health Indicators ETL Pipeline — Africa

## Overview
End-to-end ETL pipeline analyzing World Bank health data across 54 African countries, with a focus on Senegal.

## Pipeline
- **Extract** — Dataset downloaded from Kaggle (World Bank Health Nutrition and Population Statistics)
- **Transform** — Data restructuring and cleaning with Pandas (wide to long format, filtering, type conversion)
- **Load** — Storage in a SQLite database
- **Analyze** — SQL queries and visualizations with Matplotlib

## Tools
Python, Pandas, SQLite, Matplotlib, Jupyter Notebook

## How to Run
1. Clone the repository
2. Install dependencies: `pip install pandas matplotlib kaggle`
3. Set up your Kaggle API credentials
4. Run the notebook: `HETL.ipynb`

## Key Insights
- Algeria has the highest life expectancy in Africa (74.8 years in 2014)
- Senegal's life expectancy increased by +8.6 years between 2000 and 2014
- Infant mortality in Senegal dropped by nearly 40% between 2000 and 2014

## Data Source
World Bank Health Nutrition and Population Statistics — via Kaggle
