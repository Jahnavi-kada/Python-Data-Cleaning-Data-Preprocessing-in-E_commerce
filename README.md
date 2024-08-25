# Python-Data-Cleaning-Data-Preprocessing-in-E_commerce
Cleaning the data and preprocessing the data before proceeding to EDA and understand customer behavior and trend using their point of sales data.

## Technologies Used
* Python: The core programming language for data analysis and visualization.
* Pandas: A powerful library for data manipulation and analysis.
* NumPy: A fundamental library for numerical computations.
* Matplotlib & Seaborn: Libraries for creating static, animated, and interactive visualizations in Python.
* Jupyter Notebook: An interactive coding environment for documenting and sharing analysis results.

## Dataset Description:

## Customers
### Variables:
* Customer_ID (int): Unique identifier for each customer.
* DOB (date): Date of birth of the customer.
* Gender (varchar): Gender of the customer.
* City_Code (int): City code of the customer.

## Schema:
* Number of variables: 4
* Number of records: 5647
### Purpose: This dataset is used to store customer demographics and information.

## Prod_cat_info
### Variables:
* Prod_cat_code (int): Product category code.
* Prod_cat (varchar): Product category.
* Prod_sub_cat_code (int): Product subcategory code.
* Prod_subcat (varchar): Product subcategory.

## Schema:
* Number of variables: 4
* Number of records: 23
### Purpose: This dataset is used for categorizing products based on their category and subcategory.

## Transactions
### Variables:
* transaction_id (int): Unique identifier for each transaction.
* cust_id (int): Customer ID associated with the transaction.
* tran_date (date): Date of the transaction.
* prod_subcat_code (int): Product subcategory code.
* prod_cat_code (int): Product category code.
* Qty (int): Quantity of products purchased (Negative if it is a return order).
* Rate (decimal): Unit rate of the product (Negative if it is a return order).
* Tax (decimal): Tax amount for the transaction.
* total_amt (decimal): Total amount of the transaction (Negative if it is a return order).
* Store_type (varchar): Type of store where the transaction occurred.

## Schema:
* Number of columns: 10
* Number of rows: 23053
### Purpose: This dataset is used for analyzing transactional data, including customer purchase behavior and store performance metrics. 

## Objectives
* To gain a general overview of the e-commerce dataset and its contents.
* To clean and preprocess data, thereby handling missing values, removing duplicates, and resolving inconsistencies.
* To visualize data in order to identify interesting patterns, trends, and potential outliers.
* To perform basic statistical analysis to answer relevant business questions pertaining to sales and customer behavior.
* To understand customer profiles through segmentation and grouping analyses, thereby providing insights into purchasing patterns.

## Process to run Analysis 
### Load dataset
 df = pd.read_csv('ecommerce_data.csv')  # Replace with your file path

### Data Cleaning & Preprocessing:
Handle missing values and perform any necessary data type conversions and cleaning processes.

## Conclusion
This ReadMe file outlines the structure of an exploratory data analysis project focused on e-commerce data using Python. It details the dataset, objectives, required technologies, and steps required to execute the analysis. ​Ultimately, the Data Cleaning and Data Preprocessing in the data sets sources in making informed decisions and gives insights that enhance performance and customer satisfaction within the e-commerce space.


