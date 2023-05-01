# azure-stock-market-etl-pipeline

Project: Build an ETL pipeline for analyzing stock market data using Azure Data Factory

Overview:
In this project, you will build an ETL (Extract, Transform, Load) pipeline using Azure Data Factory to extract stock market data from a public API, transform it into a format suitable for analysis, and load it into a data warehouse for further processing. You will use Azure services like Azure Data Factory, Azure Blob Storage, and Azure Synapse Analytics to complete this project.

Steps:
1. Identify a public API that provides stock market data. You can use a free API like Alpha Vantage, Yahoo Finance, or IEX Cloud.
2. Create an Azure Data Factory instance and set up a pipeline to extract data from the API using the Web activity.
3. Use the Data Flow activity to transform the data into a format suitable for analysis. You can clean, filter, aggregate, or join the data as needed.
4. Store the transformed data in Azure Blob Storage or Azure Data Lake Storage.
5. Create a data warehouse in Azure Synapse Analytics and use the Copy Data activity to load the transformed data into the data warehouse.
6. Create a SQL Pool in Azure Synapse Analytics and use SQL queries to analyze the stock market data. You can calculate metrics like daily returns, volatility, or correlation.
7. Visualize the results using tools like Power BI or Azure Synapse Studio.

Key skills:
- Azure Data Factory
- Data Flow
- Azure Blob Storage or Azure Data Lake Storage
- Azure Synapse Analytics
- SQL queries for data analysis
- Data visualization
