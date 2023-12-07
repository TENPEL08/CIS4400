# Analyzing TSA Throughput Data and Historical Weather Information
- A Data Warehousing for Analytics undergraduate student group project for CIS 4400 course.

**Requirements**: https://docs.google.com/document/d/1djD0VMOxct1eiHj7tiv0HYmfNdgD4YXA1nGX4urJj_U/edit?usp=sharing

**Link to TSA Data Set**: https://www.tsa.gov/foia/readingroom?page=1

**Link to Weather API Data Set**: https://open-meteo.com/en/docs/historical-weather-api

**Data Dictionary**: https://docs.google.com/spreadsheets/d/1IMv8EoMX21I7BfsayR2Qs0bNYVQoMm-qADgmQC2n_Bk/edit?usp=sharing

**Data Model**: ![SAve](https://github.com/TENPEL08/CIS4400/assets/74534392/23ee5fc3-0690-483d-8d9b-cf12250e26ef)


**Cloud Service**: Azure Storage Service, Azure Blob, Google BigQuery, Google Cloud Storage, Google Looker Studio

**Python Libraries Needed**: pdfplumber, pandas, os, azure-storage-blob, azure.storage.blob,geopy, openmetro_requests, requests_cache, retry_requests, geopy, 

**Presentation**: https://docs.google.com/presentation/d/1EuS2QrsZNMp_pGg0LIwexvZJP1ALPeWN-lgObN8_OzY/edit?usp=sharing

**Final Dashboard**: [Insert Image]

Steps:
1. **Data-Sourcing**: Source the data set from the data set link (Insert_Script_Name)
2. **Data-Storing**: Upload Data Set to Azure Blob Cloud Storage ('Insert_Script_Name' )
3. **Data-Cleaning-Transforming**: Clean and Transform Data (Insert_Script_Name)
4. **Data-Warehouse**: Design The Data Model, Create Script for Data Warehouse, Load Data into Data Warehouse (In-Progress)
5. **Data-Analytics**: Load cleaned data set from Azure Synapse Analytics Data Warehouse to Tableau/PowerBi to create Dashboard

