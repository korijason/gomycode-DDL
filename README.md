# Data Definition Language (DDL) Checkpoint

## Overview
This project involves creating a relational database model using SQL. The database consists of three tables: `CUSTOMER`, `PRODUCT`, and `ORDERS`. It includes constraints such as primary keys, foreign keys, and checks for data integrity.

## Instructions

### Tasks Performed:
1. **Created Tables**:
   - Defined `CUSTOMER`, `PRODUCT`, and `ORDERS` tables with appropriate attributes, data types, and constraints.
   
2. **Added Columns**:
   - Added a `Category` column (VARCHAR2(20)) to the `PRODUCT` table.
   - Added an `OrderDate` column (DATE) to the `ORDERS` table with a default value of the current date (`SYSDATE`).

### SQL Script
The full SQL script can be found in the file `create_tables.sql`.

### How to Run:
1. Open a database management tool such as SQL Developer or MySQL Workbench.
2. Copy and paste the SQL script into the query editor.
3. Execute the script to create the tables and apply the modifications.

## Author
Created by [Your Name]. Feedback and suggestions are welcome!
