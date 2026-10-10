# E-Commerce Medallion Architecture

This is a Databricks practice project demonstrating the implementation of a Medallion Data Architecture (Bronze, Silver, Gold layers) using e-commerce data.

## Project Structure

* **Setup**: Contains the initial environment and data configuration (`setup`).
* **1_medallion_processsing_dim**: Processing pipelines for Dimension tables.
  * `1_dim_bronze`: Raw data ingestion.
  * `2_dim_silver`: Cleansed and filtered data.
  * `3_dim_gold`: Business-level aggregated data.
* **2_medallion_processing_fact**: Processing pipelines for Fact tables.
  * `1_fact_bronze`: Raw transactional data ingestion.
  * `2_fact_silver`: Cleansed transactional data.
  * `3_fact_gold`: Final aggregated fact tables for reporting.
