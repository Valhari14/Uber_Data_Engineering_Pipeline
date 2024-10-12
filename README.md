# Uber ETL Pipeline Data Engineering Project

This project demonstrates an **End-to-End ETL pipeline** for analyzing Uber trip data using modern data engineering tools on Google Cloud Platform (GCP). The process involves extracting, loading, and transforming the data with an ETL tool and performing data analysis using BigQuery and Looker.

## Project Overview

### Data Source:
- **Dataset**: [Uber Trip Record Data](https://www.kaggle.com/datasets/praveenluppunda/uber-dataset) includes yellow and green taxi trip records. The dataset captures details such as pick-up and drop-off locations, trip distances, fares, payment types, and passenger counts.
  
### Objective:
- To process Uber trip data and perform analytics using GCP and Mage, a modern data pipeline tool.

## Process Workflow

1. **Extract (Raw Data Storage)**:
   - Data is ingested and stored in **Google Cloud Storage** as the raw data layer.

2. **ETL with Mage**:
   - The raw data is processed using **Mage**, a modern ETL tool running on a **Compute Engine VM**.
   - Mage automates the transformation of the dataset.

3. **Data Load and Transformation**:
   - Transformed data is loaded into **BigQuery** for analytics.

4. **Data Analysis using Looker**:
   - Once the data is loaded into BigQuery, it is analyzed and visualized using **Looker Studio** to generate insights.

## Architecture

The architecture for the ETL process is as follows:

- **Raw Data Storage**: Data is stored in Google Cloud Storage.
- **Mage ETL**: Running on a Compute Engine VM, Mage performs the extraction, transformation, and loading process.
- **BigQuery**: Stores the final processed data for querying and analysis.
- **Looker Studio**: Used for visualization and creating reports on the processed data.

## Tools and Technology Used

- **Programming Language**: Python
- **Cloud Platform**: Google Cloud Platform (GCP)
  - Google Cloud Storage
  - Compute Engine VM
  - BigQuery
  - Looker Studio
- **Modern Data Pipeline Tool**: [Mage](https://www.mage.ai/)


