# Flight Operations Data Warehouse & Analytics System

## Overview
This project implements a data warehouse solution for analyzing airline operations, including flight performance, profitability, and delays.

The system is designed using a star schema and supports analytical queries for business insights.

---

## Key Features
- Designed star schema (fact and dimension tables)
- Implemented ETL process using PL/SQL
- Integrated data from simulated OLTP system
- Calculated business metrics (profit, delay, load factor)
- Performed advanced analytics using OLAP operations

---

## Technologies
- Oracle SQL
- PL/SQL
- Data Warehousing
- OLAP (ROLLUP, CUBE, GROUPING SETS)
- MODEL clause (what-if analysis)

---

## Data Model
The warehouse is structured using:

- Fact table: flight metrics
- Dimension tables:
  - Date
  - Route
  - Aircraft
  - Time

---

## Analytical Capabilities
- Route profitability analysis
- Delay and on-time performance tracking
- Load factor analysis
- Seasonal trend evaluation
- Fuel cost impact simulation (what-if analysis)

---

## Project Structure
/sql → ETL scripts and warehouse implementation  
report.pdf → Full project documentation  

---

## Documentation
[Full Project Report](report.pdf)

---

## Purpose
This project demonstrates practical implementation of data warehousing concepts and advanced SQL analytics for real-world business scenarios.
