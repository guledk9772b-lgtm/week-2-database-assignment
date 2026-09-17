# SQL Assignment

## Description
This assignment contains SQL queries used to retrieve, filter, sort, and limit data from different tables in a database.

## Questions Covered

### Question 1: Retrieve Payment Information
Retrieves:
- checkNumber
- paymentDate
- amount

### Question 2: Find Orders in Process
Retrieves:
- orderDate
- requiredDate
- status

Only orders with the status **In Process** are displayed, sorted by order date in descending order.

### Question 3: Find Sales Representatives
Retrieves:
- firstName
- lastName
- email

Only employees with the job title **Sales Rep** are displayed, sorted by employee number in descending order.

### Question 4: Retrieve Office Information
Retrieves all columns and all records from the **offices** table.

### Question 5: Retrieve the Five Cheapest Products
Retrieves:
- productName
- quantityInStock

Products are sorted by **buyPrice** from lowest to highest, with only the first 5 records displayed.

## SQL Concepts Used
- SELECT
- FROM
- WHERE
- ORDER BY
- ASC
- DESC
- LIMIT
- Filtering records
- Sorting records

## Database Tables
The queries use the following tables:
- payments
- orders
- employees
- offices
- products
