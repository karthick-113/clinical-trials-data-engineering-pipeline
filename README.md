# clinical-trials-data-engineering-pipeline
End-to-end Clinical Trials Data Engineering Pipeline built using AWS S3, Databricks, PySpark, Delta Lake, SQL, and dimensional modeling with Bronze-Silver-Gold architecture.


# Clinical Trials Data Engineering Pipeline

## Overview

This project demonstrates an end-to-end Data Engineering solution built on clinical trial data from ClinicalTrials.gov. The pipeline ingests raw clinical trial data, performs data quality validation and transformations, implements a Bronze-Silver-Gold architecture, and creates a dimensional data model for analytical reporting.

The project processes over 15,000 clinical trial records and showcases modern data engineering concepts including PySpark transformations, Delta Lake storage, data quality checks, dimensional modeling, and SQL-based analytics.

## Technology Stack

* AWS S3
* Databricks
* PySpark
* Delta Lake
* SQL
* Dimensional Modeling
* Clinical Research Analytics

## Architecture

ClinicalTrials Dataset
→ Bronze Layer (Raw Data)
→ Silver Layer (Cleaned & Validated Data)
→ Gold Layer (Star Schema)
→ SQL Analytics & Reporting

## Key Features

* Data ingestion and validation
* Bronze-Silver-Gold architecture
* Null and duplicate handling
* Delta Lake implementation
* Star schema design
* Fact and dimension tables
* Clinical trial analytics
* Data quality validation framework
