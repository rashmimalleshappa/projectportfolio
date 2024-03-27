# Data Analysis Portfolio

Welcome to my GitHub portfolio showcasing a diverse array of Power BI Dashboards! Within this repository, you'll discover a compilation of data projects, each offering a unique blend of insightful reports, compelling visualizations, and robust data sources. Whether you're delving into business intelligence analysis, embarking on data exploration endeavors, or monitoring performance metrics, these dashboards serve as powerful tools to gain key insights and drive decision-making.

# Dashboard projects

1. [# Problem Statement
A Warehouse business reporting system lacks the ability to analyze the flow of goods from purchase order to sale. This creates a blind spot, hindering their understanding of inventory turnaround time and potential inefficiencies in the purchasing and sales processes.

# Business Requirements

1. Combine data from three separate datasets (Purchases, Receiving, Billing) with no pre-existing relationships between them.
2. Measure the time elapsed between placing a purchase order and receiving the goods into the warehouse.
3. Determine the time between receiving goods and billing the customer.
4. Create a summary report presenting the calculated lead times, sales cycle analysis, and billing insights.

# Solution

The Purchases data tells us when we ordered products and how many, while Receiving data reveals how long it takes for goods to arrive after placing an order. Then, we analyze Billing data to see how quickly we invoice customers after receiving goods.

# Data Transformation and Modelling- 
1. Imported tables from the dataset
2. Extended Date Table was added as [Date]
3. Identified Fact and Dimension tables
4. Created Duplicates for Purchasing and Receiving for creating a separate table for unique Customers and Materials (Lookup tables)
5. Created relationships between all the tables
6. A new table was derived by merging the Purchases and Receiving tables for the calculation of time elapsed between purchase orders and receiving.

# Snapshot of Data Model

![data model](https://github.com/rashmimalleshappa/projectportfolio/assets/164936428/652e0c54-e93d-4a97-979d-b4001b01f8b2)

# Snapshot of Power BI Dashboard

![warehouse1](https://github.com/rashmimalleshappa/projectportfolio/assets/164936428/9ebd1cff-a9f5-41dc-bdc7-6884c029fda0)](Warehouse Dashboard)
2. [Project 2- HR Insights Dashboard]

Within each project folder in this repository, you'll discover a detailed README.md file outlining the dashboard's purpose, utilized data sources, and any relevant information. Additionally, accompanying screenshots offer a visual preview of the dashboard's interface.
