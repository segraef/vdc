# Data & AI PaaS Pattern

This orchestration deploys the infrastructure for a Data and AI environment.


## Deployed Resources

The following resources are deployed as part of this code orchestration:

Global Dependencies
Azure Active Directory
Subscription

Resource Group 1: Shared Services for Data & AI (with VNet and NSG)
Azure Monitor
Azure Security
Azure Log Analytics
Azure App Insights
Azure Key Vault

Resource Group 2: Data & AI Components (with VNet and NSG)

Source Data
Azure Blob Storage: to store unstructured content for ingestion to the data. 
Azure SQL Server: to store structured content for ingestion to the data pipeline. (with TDE)
Azure Event Hub: Real-Time Telemetry Ingestion

Data Processing & Storage
Azure Data Factory: to create pipelines to move and transform data
Azure Data Lake Store: Deep storage of structured and unstructured data
Azure SQL DW Server: Structured enterprise data warehouse
Azure HDInsights: Hadoop Services for data processing (with Jupyter & Zeppelin notebooks)
Azure Data Bricks: Apache Spark-based analytics platform
Azure Stream Analytics: Real-Time Stream Analytics
Azure Analysis Services: OLAP Data Marts

Machine Learning
Azure ML
Cognitive Services

Data Visualization
PowerBI: Data Visualization

-------------------
+ **SQL Server**
