java cMET AD688 Assignment 2  SQL for E-Commerce Startups 
Assignment Objective: You have recently joined an e-commerce startup, "ShopSmart," which sells various products online. The company has been growing, but they are facing challenges with understanding their customers’ purchasing behaviors and optimizing their product offerings. Your task is to design a database that can store the company's data, populate it with realistic data, and then perform. a series of SQL queries to derive insights and solve business problems.
Possible Points: 8
Database Design Products: Stores Information about products available on the platform 
ProductID 
Primary Key 
ProductName 

Category 

Price 

StockQuantity 

DateAdded 



ShopSmart has enlisted the help of a few consultants in the data management field, and they’ve identified and recommended the following entities that are necessary to store the company’s data.Customers: Stores information about customers 
CustomerID 
Primary Key 
FirstName 

LastName 

Email 

SignUpDate 

LastPurchaseDate 


Orders: Stores information about customer orders 
OrderID 
Primary Key 
CustomerID 
Foreign Key 
OrderDate 

OrderStatus 


OrderItems: Stores information about the items within each order 
OrderItemID 
Primary Key 
OrderID 
Foreign Key 
ProductID 
Foreign Key 
Quantity 

PricePerUnit 
Reviews: Stores customer reviews for products 
ReviewID 
Primary Key 
CustomerID 
Foreign Key 
ProductID 
Foreign Key 
ReviewDate 

Rating (Note: this is on a scale of 1 - 5 

ReviewText 

Datasets 
You’ve been provided with the following .csv files, each containing critical data that ShopSmart has collected:
Customers_Data.csv 
Products_Data.csv 
Orders_Data.csv 
Order_Items_Data.csv 
Reviews_Data.csv 
Task 2-0: Managerial Report Structure 
Submission Requirements: You are required to submit a managerial report, along with your SQL file used for this assignment.
Your paper should be structured and presented in the form. of a managerial report, APA format. This report should include:
· Cover Page
· Table of Contents
· Executive Summary
· Main Body (3 - 6 pages, APA format)
· Appendices
o Visualizations
o Screenshots of code and output
(max 0.5 point) 
Task 2-1: Database design and development 1. You are required to review the data provided by the consultants for accuracy and create a design of this database (i.e. create an ERM). To be included in your design are cardinalities, relationships between entities, identification of primary and foreign keys and for each attribute, identify its datatype. In your managerial report, provide a description of the ERM you’ve created.2. Using SQL, Create and populate each table with the data 代 写MET AD688 Assignment 2 SQL for E-Commerce Startups
代做程序编程语言provided in the excel files. HINT: You should create a database in SQLite first, then proceed to create the tables.
(max 1.5 point) 
Task 2-2: Basic SQL Queries 
ShopSmart would like to gain insights into the current operations of the business. For each of the following questions, write the SQL query to retrieve the required data. In your managerial report, discuss your findings.1. Retrieve a list of all customers who signed up in the last 30 days.2. List all products that are currently out of stock.3. Find the total number of orders placed in the last month.4. Display all orders made by a specific customer of your choice.5. Show the top 5 products by the number of orders.6. Retrieve all reviews for a specific product.7. List all customers who have not made any purchases in the last 6 months.8. Show the total revenue generated from orders in the last year.9. Find the average rating of products in each category.10. Retrieve all orders with a status of "Pending."  
(max 2 points) 
Task 2-3: Intermediate SQL Queries 
ShopSmart’s Leadership team are very impressed with the work you’ve done so far and would like to dig deeper into their data for decision-making purposes. For each of the following questions, write the SQL query to retrieve the required data. In your managerial report, discuss your findings.1. Identify customers who have spent more than $500 on the platform.2. Calculate the average order value for each customer.3. Find products that have been added in the last 90 days but have not been sold.4. Generate a report of products with low stock (less than 10 items in stock).5. List customers who have given a rating of 5 to any product.6. Identify customers who have ordered more than 3 different products in a single order.7. Find the top 3 categories with the highest sales volume.8. Display all customers who have purchased from a specific category.9. Calculate the total spend by each customer since their signup.10. Identify orders that include items from multiple categories.
(max 2 points) 
Task 2-4: Advanced SQL queries 
“The work our new hire has done is outstanding! However, everything has seemed so effortless—let’s set a real challenge to determine the true extent of this talent.” - ShopSmart’s CEO
For each of the following questions, write the SQL query to retrieve the required data. Provide a short analysis for each advanced query, explaining the insights gained and how they could be used by the e-commerce company.1. Analyze the purchasing behavior. of customers by grouping them into segments based on their total spend and average order value.2. Identify patterns in the reviews to find products that receive consistently high or low ratings.3. Create a list of customers who have stopped purchasing (no orders in the last 6 months) and have given low ratings in their last reviews.
(max 2 points) 

         
加QQ：99515681  WX：codinghelp
