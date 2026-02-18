📊 COVID-19 Data ETL Pipeline using Python

This project implements an ETL (Extract, Transform, Load) pipeline to process and analyze global COVID-19 time series data. The pipeline extracts raw data from multiple CSV files, cleans and transforms it into a structured format, and prepares it for analysis and visualization.

🔧 Project Workflow

Extract
Data is collected from multiple raw datasets, including global confirmed cases, deaths, and recovered cases.

Transform
The raw data is cleaned and processed by:

Handling missing values

Renaming and formatting columns

Converting wide time-series data into a tidy/long format

Aggregating data by country and date for easier analysis

Load
The transformed dataset is stored in a structured format (DataFrame/file) ready for analysis or visualization.

📈 Key Outcomes

Unified dataset containing confirmed, death, and recovered cases

Country-wise and date-wise trend analysis

Clean, analysis-ready dataset for dashboards or reporting

🛠️ Tech Stack

Python

Pandas & NumPy

Jupyter Notebook
