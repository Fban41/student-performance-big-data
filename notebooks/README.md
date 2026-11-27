# Data Engineering Notebooks

This directory contains Databricks notebooks implementing
the end-to-end Medallion Architecture pipeline.

## Execution Order

| Notebook | Description |
|---|---|
| 00_setup | Environment and Unity Catalog setup |
| 01_bronze | Raw data ingestion |
| 02_data_quality | Data profiling and quality checks |
| 03_silver | Data cleaning and transformation |
| 04_gold_model | Dimensional modelling |
| 05_gold_aggregations | Analytical views |
| 06_pipeline_validation | Automated pipeline validation |

The notebooks can be executed manually in numerical
order or automatically using Databricks Lakeflow Jobs.
