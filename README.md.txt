# Databricks Medallion Architecture – Acquisition Data Pipeline

This project simulates a data engineering pipeline built using **Databricks Medallion Architecture** to integrate data from an acquired company (SportsBar) into a parent company's analytics platform (AtliQon).

## Architecture

The pipeline follows the **Bronze → Silver → Gold** architecture.

- Bronze: Raw ingestion from S3
- Silver: Data cleaning, deduplication, and standardization
- Gold: Analytical tables integrated with the parent company platform

## Key Features

- Databricks Medallion Architecture
- Incremental data ingestion
- Data standardization across parent and child platforms
- Deduplication and data quality checks
- Dimension modeling (Date Dimension)

## Project Structure

notebooks/
dimension_processing
fact_processing
setup