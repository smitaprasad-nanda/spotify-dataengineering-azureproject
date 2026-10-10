# 🎵 Spotify End-to-End Data Engineering Project on Microsoft Azure

**Building a scalable cloud data pipeline using Azure Data Factory, Azure Databricks, and Azure Data Lake Storage Gen2.**

## 📌 Project Overview

This project implements an end-to-end data engineering solution for Spotify data using Microsoft Azure services. It demonstrates how data can be ingested from source systems, orchestrated through automated pipelines, transformed using distributed processing, and organized into structured data layers for analytics.

The solution combines **Azure Data Factory (ADF)** for data ingestion and pipeline orchestration, **Azure Data Lake Storage Gen2 (ADLS Gen2)** for scalable storage, and **Azure Databricks with PySpark** for data transformation and processing.

The project also explores incremental data loading, data modeling, and data governance to demonstrate practical skills relevant to modern cloud data engineering.

## 🏗️ Architecture & Data Flow

The pipeline follows a layered data architecture, separating ingestion, transformation, and analytics-ready data.

1. **Source Layer - Azure SQL Database:** Provides structured source data for ingestion.
2. **Ingestion & Orchestration - Azure Data Factory:** Coordinates data movement and pipeline execution, with parameterized and reusable pipeline patterns.
3. **Storage Layer — Azure Data Lake Storage Gen2:** Stores data in organized layers for subsequent processing.
4. **Transformation Layer — Azure Databricks:** Uses PySpark and Apache Spark to clean, transform, and process data.
5. **Curated Layer — Gold:** Organizes processed data into analytics-ready structures, including dimensional models where implemented.
6. **Governance — Unity Catalog:** Supports centralized management and governance of data assets in Databricks.

## ⚙️ Key Features

### 1. Data Ingestion & Orchestration with Azure Data Factory
- Built data pipelines to coordinate source-to-storage data movement.
- Worked with linked services, datasets, pipeline activities, and parameters.
- Explored reusable pipeline designs for processing multiple datasets.
- Implemented incremental ingestion and backfilling patterns where configured.

### 2. Cloud Data Lake with ADLS Gen2
- Organized data using a layered storage architecture.
- Used Azure storage paths to separate data and processing checkpoints.
- Integrated cloud storage with Azure Data Factory and Databricks.

### 3. Data Transformation with Azure Databricks
- Processed data using PySpark and Apache Spark.
- Applied transformations to prepare datasets for downstream consumption.
- Explored Spark Structured Streaming and Auto Loader for file ingestion.
- Worked with Delta Lake for structured data storage and processing.

### 4. Data Modeling & Analytics
- Explored dimensional modeling concepts for analytics-ready datasets.
- Worked with dimension tables and data transformation workflows.
- Studied Slowly Changing Dimensions (SCD) and star-schema design where implemented.

### 5. Data Governance & Incremental Processing
- Worked with Unity Catalog concepts, including metastore and storage access configuration.
- Explored incremental processing patterns to support efficient data ingestion.
- Used checkpoints to manage streaming or incremental processing workflows.

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Cloud Platform | Microsoft Azure |
| Data Ingestion & Orchestration | Azure Data Factory |
| Cloud Storage | Azure Data Lake Storage Gen2 |
| Source Database | Azure SQL Database |
| Data Processing | Azure Databricks, Apache Spark, PySpark |
| Data Format & Storage | Parquet, Delta Lake |
| Streaming & Ingestion | Spark Structured Streaming, Auto Loader |
| Data Governance | Unity Catalog |
| Programming | Python, SQL |
| Version Control | Git, GitHub |

## 💡 Skills Demonstrated

- End-to-end cloud data pipeline development
- ETL/ELT concepts and data orchestration
- Distributed data processing with Apache Spark
- Cloud storage integration and access configuration
- Incremental data ingestion concepts
- Data transformation and dimensional modeling
- Data governance fundamentals
- Debugging and troubleshooting cloud data workflows

## 👨‍💻 About This Project

This project provided practical exposure to building cloud-based data pipelines and integrating Azure services across ingestion, storage, transformation, and governance.

It reflects my ongoing development in **cloud data engineering, scalable data processing, and modern data platform architecture**.
