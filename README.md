# Sales Data Analysis and Forecasting

This repository contains code and analysis for processing, cleaning, and analyzing sales data using PySpark and conducting sales forecasting with Facebook Prophet. The analysis is performed both locally and on Databricks, showcasing the versatility of the approach.

## Overview

The project leverages the power of Apache Spark for big data processing and Spark SQL for data querying and cleaning. The final part of the project involves using the fbprophet library to forecast future sales based on historical data.

## Contents

- `data_ingestion.py`: Script for reading in sales data using PySpark.
- `data_cleaning.sql`: Spark SQL queries for cleaning and transforming the data.
- `data_analysis.sql`: Spark SQL queries for advanced data analysis.
- `sales_forecasting.ipynb`: Jupyter notebook detailing sales forecasting using fbprophet.
- `databricks_notebooks/`: Folder containing equivalent notebooks for execution on Databricks.

## Usage

1. **Data Ingestion**: The sales data is read into Spark DataFrames using PySpark, allowing for scalable data processing.
   
2. **Data Cleaning and Transformation**: Spark SQL is utilized to clean the data, dealing with inconsistencies, missing values, and schema enforcement.
   
3. **Data Analysis**: Further analysis is performed using Spark SQL to derive insights such as sales trends, product performance, and customer behavior.
   
4. **Sales Forecasting**: fbprophet is used for time-series forecasting, predicting future sales trends based on historical data.
   
5. **Databricks Integration**: The same processes are replicated on Databricks, demonstrating cloud-based big data analytics capabilities.

## Results

The analysis provides valuable insights into sales patterns and predicts future trends, aiding in strategic decision-making for inventory management, marketing, and sales strategies.

## How to Run

Ensure that you have PySpark installed, and clone this repository to your local system. The Jupyter notebook can be run directly if you have fbprophet and Jupyter installed. For Databricks, import the notebooks into a Databricks workspace and attach them to a cluster to execute.

## Contributions

Feel free to fork this project and submit pull requests. For any major changes, please open an issue first to discuss what you would like to change.


## References

- [Apache Spark](https://spark.apache.org/)
- [Databricks- SalesDataPrep](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2440750105006843/3792990910911030/2307370778381610/latest.html)
- [Databricks-SalesAnalytics](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2440750105006843/4359897715315070/2307370778381610/latest.html)
- [Databricks-Dashboard](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2440750105006843/4359897715315070/2307370778381610/latest.html)
  

