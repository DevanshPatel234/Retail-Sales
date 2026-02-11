# Retail Sales Analysis - SQL Project

- Retail Sales Analysis project demonstrates SQL skills used in real-world data analysis
- Designed for beginners who want to build a strong foundation in SQL
- Includes database creation, data cleaning, exploratory data analysis (EDA), and business insights
- Uses retail sales dataset to answer practical business questions
- Focuses on customer behavior, sales trends, and product performance analysis
- Helps understand how SQL is used by data analysts in industry
- Provides hands-on experience with aggregate functions, window functions, and CTEs
- Generates meaningful insights that support business decision-making


### Project Objectives

- Set up retail sales database (p1_retail_db)
- Create and structure retail_sales table
- Perform data cleaning and remove null values
- Conduct exploratory data analysis
- Solve business problems using SQL queries
- Identify sales trends and customer insights


### Database Structure

- Database Name: p1_retail_db
- Table Name: retail_sales
- Columns Included:
  - transactions_id (Primary Key)
  - sale_date
  - sale_time
  - customer_id
  - gender
  - age
  - category
  - quantity
  - price_per_unit
  - cogs
  - total_sale


### Data Cleaning Process

- Checked total number of records
- Identified unique customers and categories
- Verified presence of null or missing values
- Removed records with missing data
- Ensured dataset consistency before analysis


### Business Analysis Performed

- Retrieved sales for specific dates
- Filtered category-based transactions
- Calculated total sales per category
- Found average age of customers by category
- Identified high-value transactions (total_sale > 1000)
- Counted transactions by gender and category
- Determined best selling month in each year
- Identified top 5 customers by total sales
- Calculated unique customers per category
- Analyzed sales distribution by shift (Morning, Afternoon, Evening)


### Key Findings

- Sales vary across months indicating seasonal trends
- Certain customers contribute significantly to total revenue
- Clothing and Beauty categories show strong performance
- High-value transactions indicate premium purchases
- Evening and afternoon shifts show higher order volume

### Conclusion

- This project provides practical SQL experience for beginners
- Demonstrates real-world data cleaning and analysis workflow
- Builds strong foundation for data analyst roles
- Helps in understanding customer behavior and sales performance
