# NYC Citywide Annualized Calendar Sales
- A Data Warehousing for Analytics undergraduate student project for CIS 4400 course.
- Annualized sales file displays yearly sales information of properties sold in New York City.

**Requirements**: https://docs.google.com/document/d/1eNjW4EIh-_baU9HZFDWMddgD_fLYbvzxpggX--MA0xQ/edit?usp=sharing

**Link to Data Set**: https://data.cityofnewyork.us/City-Government/NYC-Citywide-Annualized-Calendar-Sales-Update/w2pb-icbu

**Data Dictionary**: https://docs.google.com/spreadsheets/d/17XyGmnw2fZuTMCWVKB1XiWGHQuwqWOidm0w80lbIyjE/edit?usp=sharing

**Cleaned Data Dictionary**: https://docs.google.com/spreadsheets/d/17XyGmnw2fZuTMCWVKB1XiWGHQuwqWOidm0w80lbIyjE/edit?usp=sharing

**Data Model**:

<img width="732" alt="DATAMODEL_CIS4400" src="https://github.com/garyanmai/NYC-Properties-Sold/assets/145724601/4ceb0052-55ed-48c4-9b72-503b7d02f964">

**Cloud Service**: AWS Simple Storage Service (S3), Google Cloud Storage, Google BigQuery, Google Looker Studio

**Python Libraries Needed**: pandas, InteractiveShell, warnings, requests, os, google-cloud-storage, google-cloud-bigquery, pandas gcsfs, pyarrow

**Presentation**: https://docs.google.com/presentation/d/1DbEQCUif4SYc6rnFVbkv-Sw25lSdYN0m-8CcNQjr1ME/edit?usp=sharing

**Final Dashboard**:
<img width="898" alt="DASHBOARD_CIS4400" src="https://github.com/garyanmai/NYC-Properties-Sold/assets/145724601/cbeebd17-2c63-4da2-a94b-3fe658fcabed">

Steps:
1. **Data-Sourcing**: Source the data set from the data set link (DataSourcing_Script_CIS4400)
2. **Data-Storing**: Create Storage Bucket in AWS S3 and Upload Data Set To Bucket ('AWS_S3_Storage_Script_CIS4400' or 'GoogleCloud_StorageScript_CIS4400' )
3. **Data-Cleaning-Transforming**: Clean and Transform Data (Clean_Transform_Script_CIS4400)
4. **Data-Warehouse**: Design The Data Model, Create Script for Data Warehouse, Load Data into Data Warehouse (BigQuery_DataWarehouse_Script_CIS4400)
5. **Data-Analytics**: Load cleaned data set from Google Cloud BigQuery Data Warehouse to Google Cloud Looker Studio to create Sales Dashboard

