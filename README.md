# Foodpanda-Dataset
## Project Overview
This project focuses on analyzing and extracting insights from a Foodpanda customer and order dataset using Apache Hive. The main goal is to utilize Hive’s SQL-like querying capabilities to explore customer behavior, restaurant performance, ordering patterns, and payment trends. It demonstrates how structured transactional data can be effectively managed in a Big Data ecosystem (Hadoop/Cloudera) and how HiveQL can be used to perform large-scale analytical queries for actionable business insights.

## Dataset Description
The dataset, titled Foodpanda Analysis Dataset.csv, provides detailed information on customer demographics, order details, and restaurant data. It includes the following fields:
•	Customer ID
•	Gender
•	Age
•	City
•	Signup Date
•	Order Date
•	Restaurant Name
•	Dish Name
•	Category
•	Quantity
•	Price
•	Payment Type
•	Order Frequency
•	Last Order
•	Loyalty Policy
•	Churned
•	Rating
•	Rating Date
•	Delivery Status

## Objectives
The project’s main objectives are as follows:
•	To import and store the Foodpanda dataset from CSV format into Hive tables.
•	To perform analytical queries that uncover trends in customer behavior, restaurant performance, and payment modes.
•	To extract valuable insights such as:
o	Top restaurants by order volume and revenue.
o	Average order value by city and category.
o	Customer loyalty and churn rate analysis.
o	Most popular dishes and cuisines.
o	Payment method preferences and delivery success rate.

## Technologies Used
•	Apache Hive
•	Hadoop (Cloudera Environment)
•	HiveQL (SQL-like Query Language)
•	CSV File Data Loading
•	HDFS (Hadoop Distributed File System)

## Steps Involved
1.	Created a new Hive database and defined a table schema for the Foodpanda dataset.
2.	Loaded the CSV file from local storage or HDFS into the Hive table.
3.	Executed various analytical queries to derive insights, including:
o	SELECT COUNT(*) to find total orders.
o	GROUP BY to analyze city-wise or restaurant-wise performance.
o	AVG() and SUM() to calculate average revenue and order values.
o	ORDER BY and LIMIT to identify top-performing restaurants and popular dishes.
o	WHERE and CASE statements to analyze churned vs. loyal customers.
4.	Generated analytical reports summarizing key findings and visual insights.

## Key Insights
•	Identified the top-performing restaurants with the highest number of orders.
•	Determined the most popular dishes and food categories among customers.
•	Analyzed customer loyalty trends and churn patterns.
•	Revealed revenue patterns based on city and age demographics.
•	Highlighted preferred payment methods and delivery success rates.

## Conclusion
This project demonstrates how Apache Hive can be used effectively to manage and analyze large-scale Foodpanda transactional data. By leveraging HiveQL within the Hadoop ecosystem, the project extracts meaningful insights into customer preferences, restaurant performance, and order behavior. These findings can support data-driven decision-making for marketing, operations, and customer engagement strategies.
