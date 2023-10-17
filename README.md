# E2E_Analytics_Sales_Project
End-to-End Data Analysis Sales Project utilizing PostGreSQL, BigQuery, dbt and Looker

Answer the questions:
- Which products have had the highest sales in the last 3 months?
- What customers have not purchased a product in the last 6 months?
- What is the lowest performing sales month? 

Step 1:
Setup database in Postgres
Design Sales database
  Create tables: 
    Product
    Sales
    Customer

Step 2:
Use Datastream to connect PostgreSQL to BigQuery to replicate data
https://www.cloudskillsboost.google/focuses/53925?parent=catalog#:~:text=Datastream%20for%20BigQuery%20features%20seamless,Google%20Cloud's%20serverless%20data%20warehouse.


Step 3:
Connect BigQuery tables to dbt

Step 4:
Transform Product, Sales, and Customer tables in dbt

Step 5: 
Visualize data in Looker Studio
