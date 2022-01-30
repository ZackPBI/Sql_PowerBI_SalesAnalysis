# Sql_PowerBI_SalesAnalysis_Project

Business Request & User Stories

The business request for this data analyst project was an executive sales report for sales managers. Based on the request that was made from the business we following user stories were defined to fulfill delivery and ensure that acceptance criteria’s were maintained throughout the project.  

As a (role)	I want (request / demand)	So that I (user value)	Acceptance Criteria
1	Sales Manager	To get a dashboard overview of internet sales	Can follow better which customers and products sells the best	A Power BI dashboard which updates data once a day
2	Sales Representative	A detailed overview of Internet Sales per Customers	Can follow up my customers that buys the most and who we can sell more to	A Power BI dashboard which allows me to filter data for each customer
3	Sales Representative	A detailed overview of Internet Sales per Products	Can follow up my Products that sells the most	A Power BI dashboard which allows me to filter data for each Product
4	Sales Manager	A dashboard overview of internet sales	Follow sales over time against budget	A Power Bi dashboard with graphs and KPIs comparing against budget.
Data Cleansing & Transformation (SQL)

To create the necessary data model for doing analysis and fulfilling the business needs defined in the user stories the following tables were extracted using SQL.

One data source (sales budgets) were provided in Excel format and were connected in the data model in a later step of the process.

Below are the SQL statements for cleansing and transforming necessary data.

# DIM_Calendar:

![](https://github.com/ZackPBI/Sql_PowerBI_SalesAnalysis/blob/main/dim_calander.png)

# DIM_Customers:
![](dim_customer.png)
