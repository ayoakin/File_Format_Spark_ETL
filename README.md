# ETL Pipeline with Apache Spark using CSV, Parquet and JSON

## Project Overview
Extract, transform, and load (ETL) processes combine data from multiple sources into a large, central repository called a data warehouse.This project uses a toy pipeline to model an ETL in the wild working on different file format using PySpark(the Python API for Apache Spark). 

This project creates an ETL (extract, transform, load) pipeline that:
* Imports CSV, JSON, and Parquet data formats into `PySpark`
* Cleans and transform the data as required
* Joins the required columns from each into a final table
* Saves the joined dataset in different formats (CSV, JSON, Parquet)

For a detailed explanation on the ETL processes used, check out the accompanying [article on medium](https://medium.com/@ayoakinkugbe/build-a-neural-network-from-scratch-c7e03ad1b501)

### Code
You can find the code for this project [here](https://github.com/ayoakin/Image-Rec-Neural-Net-with-ReLU./blob/main/Image_Rec_Neural_Net_with_ReLU.ipynb).

File overview:

* `File_Format_Spark_ETL.ipynb` - the full code from this project


## Environment Setup

### Installation
To follow this project, please install the following locally:

* Python 3.8+
* Spark-3.2.1
* os
* sys
* Python packages
  * pyspark
  * pyspark.sql.functions

### Data

You can download the exact file used in this project here:

* [Consumer_Complaints](https://github.com/ayoakin/File_Format_Spark_ETL/blob/main/FormatETL%20dataset/Consumer_Complaints.csv) - CSV file used
* [us-states-population](https://github.com/ayoakin/File_Format_Spark_ETL/blob/main/FormatETL%20dataset/us-states-population.json) - JSON file used
* [US _States_ Long_Lat](https://github.com/ayoakin/File_Format_Spark_ETL/blob/main/FormatETL%20dataset/US%20_States_%20Long_Lat.parquet) - Parquet file used 

