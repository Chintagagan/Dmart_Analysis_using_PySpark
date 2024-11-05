# Sales Data Integration and Analysis with PySpark

## Table of Contents
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Setup Instructions](#setup-instructions)
4. [Data Sources](#data-sources)
5. [Tasks and Implementation](#tasks-and-implementation)
6. [Analytical Questions](#analytical-questions)
7. [How to Run](#how-to-run)
8. [Contributors](#contributors)
9. [License](#license)

## Project Overview
This project aims to create a data pipeline using PySpark to integrate and analyze sales data from three different sources: product information, sales transactions, and customer details. The pipeline processes the data, cleans and transforms it, and answers a set of analytical questions to derive insights from the integrated dataset.

## Technologies Used
- **PySpark**: For data processing and analysis
- **Python**: Programming language used for the pipeline
- **CSV**: Data format for input datasets

## Data Sources
The following datasets are used in this project:

- **products.csv**: Contains product information (e.g., Product ID, Product Name, Category, Sub-category).
- **sales.csv**: Contains sales transaction details (e.g., Sale ID, Product ID, Customer ID, Quantity Sold, Sale Amount, Discount).
- **customer.csv**: Contains customer details (e.g., Customer ID, Customer Name, Age, Segment, Region, State, City).

Ensure these CSV files are located in the same directory as your script or provide the appropriate file paths.



### Task 1: Establish PySpark Connection
- Set up a PySpark environment and create a connection to read CSV files into PySpark DataFrames.

### Task 2: Load Data into PySpark DataFrames
- Load `products.csv`, `sales.csv`, and `customer.csv` into separate PySpark DataFrames.

### Task 3: Data Transformation and Cleaning
- Perform necessary data cleaning and transformation:
  - Rename columns for consistency if needed.
  - Handle missing values appropriately.
  - Ensure data types are correctly set for each column.
  - Join the DataFrames on relevant keys (Product ID and Customer ID).

### Task 4: Data Analysis and Querying
- Formulate analytical questions and write PySpark code to answer them.

### Task 5: Run Queries on PySpark
- Answer the following analytical questions using PySpark:
  1. What is the total sales for each product category?
  2. Which customer has made the highest number of purchases?
  3. What is the average discount given on sales across all products?
  4. How many unique products were sold in each region?
  5. What is the total profit generated in each state?
  6. Which product sub-category has the highest sales?
  7. What is the average age of customers in each segment?
  8. How many orders were shipped in each shipping mode?
  9. What is the total quantity of products sold in each city?
  10. Which customer segment has the highest profit margin?
