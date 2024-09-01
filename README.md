## Data Analysis Project using Python and MySQL

In this project we are going to use an Orders & Sales dataset from Kaggle using an api call to retrieve the csv file in order to work on it. 

#### The Dataset

The dataset contains the information of various orders over multiple categories and sub-categories over the course of two years i.e. 2022 and 2023.

The data contains various columns which will act as our feature vectors. In total we have 16 feature vectors as following

*'Order Id', 'Order date', 'Ship Mode',*
*'Segment', 'Country', 'City',* 
*'state', 'Postal Code', 'Region',*
*'Category', 'Sub Category',* 
*'Product Id', 'Cost price',* 
*'List Price', 'Quantity', 'Discount Percent'*

### Data Cleaning and Analysis

#### Python
- Read the data from the file.
- Handle the null values.
- Convert column names to lowercase and replacing space with an underscore.
- Derive new columns *'discount', 'sale_price', 'profit'*.
- Convert the *order_date* from object datatype to datetime.
- Load the data to Sql server.

#### SQL

After loading the data to SQL server we used some queries to gain inferences from the data to answer some questions to gain some insight.

- The top 10 highest revenue generating products. 
    Answer: *top_10_revenue_products.csv*

- Find top 5 selling products in each region. 
    Answer: *top_5_products_regionwise.csv*

- Find month over month growth comparison for 2022 and 2023 sales. 
    Answer: *month_over_month_campare.csv*

- For each category which month had highest sales.
    Answer: *highest_sale_month_each_categ.csv*

- Which sub-category saw highest growth from 2022 to 2023.
    Answer: *sub_categ_with_highest_growth.csv*
