# Home_Sales

## Overview
In this project, I analyzed home sales data using SparkSQL. I identified the key metrics from the data including the average prices of homes per year based on variables such as number of bedrooms, bathrooms, squarefeet. In order to analyze big data, I created temporary views, partitioned the data, cached and uncached the temporary table, and verified that it was uncached.

## Focus Questions
* What is the average price of homes with 4 bedrooms?
* What is the average price of homes with 3 bedrooms and 3 bathrooms?
* What is the average price of homes that has 3 bedrooms, 3 bathrooms, 2 floors, and is greater than 2000 sq ft?
* What is the view rating of homes that cost more than $350,000?

## Components
* Creating a Repository
* Importing the findspark, pyspark, and time modules into Jupyter Notebook
* Read in the AWS S3 bucket into a DataFrame
* Analyze data

## Built with
* Python
* Juypyter Notebook
* CSV
* AWS
* SparkSQL
