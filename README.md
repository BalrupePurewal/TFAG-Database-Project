# Frisco Art Gallery Database Project (Part II)

## Overview
This project is a comprehensive database system designed for **The Frisco Art Gallery (TFAG)** as part of the Spring 2025 INSY 3304: Database Management Systems course at the University of Texas at Arlington. The goal was to design, implement, and query a normalized relational database using Oracle SQL to support the gallery's operational needs such as customer orders, shipments, and employee management.

## Project Objectives
- Define and model entities, attributes, and relationships based on business rules
- Construct Crow’s Foot ER diagrams to illustrate data flow and relationships
- Develop a normalized relational schema in 3NF
- Build a complete data dictionary specifying data types, formats, and constraints
- Create and populate tables in Oracle SQL with realistic sample data
- Execute queries to answer business questions

## Entity-Relationship Modeling
Two ER diagrams were created:
- **Initial Diagram:** Showcased all entities, including M:N relationships
- **Final Diagram:** Resolved M:N relationships with bridge entities such as `ORDER_LINE`

## Relational Schema
The schema includes entities such as:
- `CUSTOMER`
- `ORDER_TABLE`
- `ARTWORK`
- `ORDER_LINE`
- `SHIPMENT`
- `VEHICLE`
- `EMPLOYEE` (supertype for `CONSULTANT`, `DRIVER`, `OPERATIONS_MANAGER`)

Primary and foreign keys are clearly defined using naming conventions that distinguish between them.

## Data Dictionary
A detailed data dictionary outlines:
- Table and attribute names
- Data types and formats
- Key constraints (PKs, FKs)
- Requirements and business logic

## SQL Implementation
The database was implemented using **Oracle SQL*Plus** and includes:
- `CREATE TABLE` statements for all 13+ entities
- `INSERT INTO` statements with sample records (5+ per table)
- `DESC` and `SELECT *` statements to display structure and data

## Key Queries Executed
- List all customer names, addresses, and phone numbers
- Retrieve full details of a selected order (header and line items)
- Find the consultant’s phone number for a specific order
- Identify all customers served by a specific driver
- Calculate total value of in-stock items priced over $450

## Technologies Used
- Oracle SQL (SQL*Plus)
- Crow’s Foot ER Modeling (Lucidchart / Draw.io)
- Microsoft Word (documentation and formatting)

## Contact
**Balrupe Singh Purewal**  
📞 (817) 821-1437  
📧 Bickypurewal@gmail.com

---

> This project demonstrates real-world database modeling, design normalization to 4NF, and hands-on SQL development aligned with business rules and enterprise requirements. Ideal for portfolio showcase under database design or academic coursework.
