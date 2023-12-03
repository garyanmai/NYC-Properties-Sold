# NYC Citywide Annualized Calendar Sales
- A Data Warehousing for Analytics undergraduate student project for CIS 4400 course.
- Annualized sales file displays yearly sales information of properties sold in New York City.

**Requirements**: https://docs.google.com/document/d/1eNjW4EIh-_baU9HZFDWMddgD_fLYbvzxpggX--MA0xQ/edit?usp=sharing

**Link to Data Set**: https://data.cityofnewyork.us/City-Government/NYC-Citywide-Annualized-Calendar-Sales-Update/w2pb-icbu

**Data Dictionary**: https://docs.google.com/spreadsheets/d/17XyGmnw2fZuTMCWVKB1XiWGHQuwqWOidm0w80lbIyjE/edit?usp=sharing

**Cleaned Data Dictionary**: https://docs.google.com/spreadsheets/d/17XyGmnw2fZuTMCWVKB1XiWGHQuwqWOidm0w80lbIyjE/edit?usp=sharing

**Data Model**:
<img width="799" alt="DataModel_CIS4400" src="https://github.com/garyanmai/NYC-Properties-Sold/assets/145724601/74083e37-03d7-48b0-9822-93f6f5fcd243">

**Cloud Service**: AWS Simple Storage Service (S3), Google Cloud Storage, Google BigQuery, Google Looker Studio

**Python Libraries Needed**: pandas, InteractiveShell, warnings, requests, os, google-cloud-storage

**Presentation**:

**Final Dashboard**:

Steps:
1. **Data-Sourcing**: Source the data set from the data set link (DataSourcing_Script_CIS4400)
2. **Data-Storing**: Create Storage Bucket in AWS S3 and Upload Data Set To Bucket ('AWS_S3_Storage_Script_CIS4400' or 'GoogleCloud_StorageScript_CIS4400' )
3. **Data-Cleaning-Transforming**: Clean and Transform Data (Clean_Transform_Script_CIS4400)
4. **Data-Warehouse**: Design The Data Model, Create Script for Data Warehouse, Load Data into Data Warehouse (In-Progress)
5. **Data-Analytics**: (In-Progress)

