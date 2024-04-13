# Home Sales Analysis Project

## Overview
This project utilizes Apache Spark to analyze home sales data, providing insights into pricing trends based on various characteristics such as the year a home was built, its features, and view ratings. The analysis involves reading, processing, and writing data in Parquet format, caching data for performance optimization, and conducting complex SQL queries.

## Features
- **Data Loading and Processing**: Load home sales data from CSV files into Spark DataFrames.
- **Data Analysis**: Use Spark SQL to perform detailed analysis and aggregation of the data.
- **Performance Optimization**: Implement caching strategies to improve query performance.
- **Data Output**: Save processed data in Parquet format, partitioned by key columns.

## Prerequisites
Before you can run this project, you'll need the following installed:
- Apache Spark
- Python 3.6 or higher
- PySpark
- Google Colab or a local setup capable of running Jupyter Notebooks if you prefer to execute the code in an interactive environment.

## Set Up Spark (if running locally):
Ensure that Apache Spark is installed and properly configured on your local machine, including setting the SPARK_HOME environment variable.
Usage
Navigate to the project directory and start the Jupyter Notebook server.

Open the Home_Sales_Analysis.ipynb notebook and run the cells sequentially to perform the data analysis.

## Running the Analysis
Execute the notebook cells directly to load data, run queries, cache results, and save outputs in Parquet format.
The analysis involves examining the average price of homes based on various filters and conditions, partitioning data for optimized storage, and comparing cached vs. uncached performance.
