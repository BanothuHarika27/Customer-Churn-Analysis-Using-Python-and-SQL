# Customer Churn Analysis Using Python and SQL

## Project Overview

This project analyzes customer churn to understand why customers leave a service and which customers are more likely to churn.

The project follows a real-world data analyst workflow, starting with loading data from a SQL database, cleaning and preparing the data, analyzing customer behavior, creating visualizations, and presenting business insights.

## Tools and Technologies

- Python
- SQL
- SQLite
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

### 1. Data Import

The customer data is stored in a SQLite database. Python is used to connect to the database and load the data using `sqlite3` and `pandas`.

### 2. Data Cleaning

The dataset is prepared for analysis by:

- Handling missing values
- Fixing incorrect data types
- Checking and removing duplicate records
- Cleaning inconsistent data
- Creating useful new columns

### 3. Exploratory Data Analysis

The data is analyzed to find patterns and trends in customer churn.

The analysis includes:

- Customer churn rate
- Churn by customer type
- Churn by age group
- Churn by subscription or service type
- Customer behavior and usage patterns
- Grouping and aggregation
- Pivot table analysis

### 4. Data Visualization

Charts are created using Matplotlib and Seaborn to make the analysis easier to understand.

The visualizations help identify important differences between customers who stay and customers who leave.

### 5. SQL Analysis

Custom SQL queries are executed directly from Python to perform additional analysis and answer specific business questions.

### 6. Business Insights

The final step is to convert the analysis into simple business insights.

The main objectives are to understand:

- Why customers are leaving
- Which customer groups have higher churn
- What factors may be related to churn
- Which areas the business can focus on to improve customer retention

## Key Learning Outcomes

Through this project, I practiced the complete data analytics process:

```text
SQL Database
     ↓
Data Cleaning
     ↓
Data Analysis
     ↓
Data Visualization
     ↓
Business Insights
