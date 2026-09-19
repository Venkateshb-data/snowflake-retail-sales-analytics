## Snowflake Retail Sales Analytics
A self-developed Data Engineering project built on Snowflake to demonstrate an end-to-end incremental retail sales pipeline.

## Business Scenario
Daily sales files are received from multiple retail stores and processed centrally in Snowflake to maintain reporting-ready sales data.

## Architecture
Retail Stores → CSV Files → Internal Stage → RAW layer → Stream → Task + MERGE → CURATED layer → Analytics Queries

## Key Features Implemented
- CSV file ingestion using Internal Stage
- RAW and CURATED data layers
- Incremental change tracking using Streams
- Automated processing using Tasks
- INSERT, UPDATE and DELETE handling using MERGE
- Duplicate file-load testing
- Data validation and reconciliation
- Store-wise, product-wise and daily sales analytics

## Repository Contents
- 'RETAIL_SALES_SNOW_PROJ_VENKATESHB.pdf' - Complete project documentation with implementation steps, SQL examples, results and screenshots
- 'RETAIL_SALES_OBJECTS.sql' - Snowflake object creation and pipeline scripts
- 'RETAIL_SALES_VALIDATION_QUERIES.sql' - Validation and reporting queries
- 'RETAIL_SALES_SAMPLE_RAW_RECORDS.zip' - Sample source CSV files used for pipeline testing

## Project Documentation
- The complete project walkthrough is available in the PDF included in this repository.
- If the PDF preview is unavailable in GitHub, download the repository using: **Code → Download ZIP**
- Then open the PDF locally.

## Technology
Snowflake | SQL | Streams | Tasks | MERGE | CSV | Data Engineering
