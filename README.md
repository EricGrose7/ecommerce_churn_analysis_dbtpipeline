# E-Commerce Data Analysis and Churn Prediction

This repository contains code, analysis, and results for a project focused on analyzing e-commerce data and predicting customer churn. The e-commerce data comes from multiple CSV files, including information about customers, orders, payments, products, and sellers. 

## Project Objective

The main objectives of this project are:

1. Conduct an Exploratory Data Analysis (EDA) on the e-commerce dataset.
2. Perform a churn analysis to understand the characteristics and behaviors of churned customers.
3. Predict customer churn using machine learning models.
4. Transform and model the data using dbt (data build tool).

## Data

The data used in this project comes from multiple CSV files, including:

- `customers.csv`: Information about the customers.
- `orders.csv`: Information about the orders.
- `payments.csv`: Information about the payments.
- `products.csv`: Information about the products.
- `sellers.csv`: Information about the sellers.

## Methodology

The project is divided into several stages:

### 1. Data Loading and Preprocessing

The first step of this project involves loading the data from the CSV files into a PostgreSQL database. Each CSV file is loaded into a separate table in the database. The data is then preprocessed to handle missing values and outliers.

### 2. Exploratory Data Analysis (EDA)

The EDA phase includes the analysis of the dataset to identify patterns, trends, and anomalies in the data. This involves the calculation of various statistics, the creation of visualizations, and the testing of hypotheses.

### 3. Churn Analysis

The churn analysis includes identifying churned customers and analyzing their behavior compared to retained customers. This involves the calculation of various statistics and the creation of visualizations.

### 4. Churn Prediction

The churn prediction phase involves the development and evaluation of machine learning models to predict customer churn. This includes feature selection, model training, model evaluation, and model selection.

### 5. Data Transformation and Modeling with dbt

dbt (data build tool) is used to transform the data in our PostgreSQL database and to create data models that are more suitable for analysis and machine learning. This includes using a lookup table to translate product category names and append a churn flag.

## Tools Used

- Python: Data preprocessing and analysis
- PostgreSQL: Database to store and retrieve the data
- Jupyter Notebook: Interactive coding environment used for data analysis
- dbt: Data build tool for transforming and modeling the data
- GitHub: Version control

## How to Use

To use this repository, first clone it to your local machine. Then, navigate to the folder containing the Jupyter notebooks and run them using a Jupyter server. Make sure you have a PostgreSQL server running and update the database connection parameters in the notebooks as necessary.

## Note

This project is still ongoing. The next steps include:

- Refine the churn prediction models.
- Add visualizations to the BI dashboard.

## Contribution

Contributions are always welcome! Please read the contribution guidelines first.

## Contact

If you have any questions, feel free to reach out to us.
