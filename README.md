# SQL-Data-Warehouse-Project

Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.

## Acknowledgment
This project was built following the [SQL Data Warehouse tutorial by Data With Baraa](PASTE-LINK-HERE).
The architecture and dataset come from his course; the implementation, notes, and additions are mine.

## Architecture
Medallion architecture with three layers:
- **Bronze:** raw data loaded as-is from the CRM and ERP source files
- **Silver:** cleaned, standardized, and integrated data
- **Gold:** star schema (fact and dimension views) ready for analytics

## Tech Stack
SQL Server, T-SQL, draw.io

## What I Learned
- (your own additions, e.g. extra data quality checks, a new gold view, a dashboard)
- (a challenge you hit and how you solved it)

## Repository Structure
- `datasets/` source CSV files
- `docs/` diagrams and documentation
- `scripts/` SQL scripts for each layer
- `tests/` data quality checks
