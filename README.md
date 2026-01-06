# Unlocking-Insights-Retail-Sales-Analysis
This project demonstrates a modern data pipeline for retail sales data using the Medallion Architecture within Databricks Unity Catalog.

PROJECT OVERVIEW:

Data Ingestion: Automated downloading and unzipping of raw retail datasets from GitHub using Python and Spark.
Governance: Leveraged Unity Catalog Volumes for secure staging of unstructured data.
Exploratory Data Analysis (EDA): Performed deep-dive analysis into sales trends, customer behavior, and product performance using Spark SQL and Python.
Storage: Managed raw data in an Azure Data Lake (ABFSS) via Unity Catalog-managed locations.

TECH STACK:

Platform: Databricks
Governance: Unity Catalog (Volumes & External Locations)
Language: Python (PySpark, Zipfile, OS),SQL
Storage: Azure Data Lake Storage Gen2 (ADLS)
Version Control: Git Integration via Databricks Git Folders
