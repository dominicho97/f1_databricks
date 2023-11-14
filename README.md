# f1_databricks
 Formula1 project using Azure Databricks,  Azure Data Factory, Delta Lake and Spark

### Project setup in Databricks
The projects is set up by accesing the data lakes with **Service Principals** <br>
And securing it with 0Auth **SECRETS**

#### Ingestion of raw data, json and csv
![ingestion](https://github.com/dominicho97/f1_databricks/assets/43000003/7ebf8126-e69b-46b8-b178-aeab9bfc7f07)


After that I used Spark / SQL to join and format the data.

###  Spark SQL visualisation in Databricks notebook

#### Most dominant F1 drivers in history
![drivers](https://github.com/dominicho97/f1_databricks/assets/43000003/4f2a2d57-7d11-4724-a1b3-2949d43f1a54)

#### Most dominant F1 teams in history
![teams](https://github.com/dominicho97/f1_databricks/assets/43000003/5c1b3cd5-afd5-4251-bba1-10ce8014b015)

## Azure Data Factory 
Setting up **pipeline** in **ADF** from the ingestion files
![adf_pipeline](https://github.com/dominicho97/f1_databricks/assets/43000003/ac7e81e2-9bcd-4d3b-b44c-1ff59d85a436)

#### Add metadata activity to pipeline to check for missing folders in Azure storage
![pipeline_metadata](https://github.com/dominicho97/f1_databricks/assets/43000003/279a581b-57b5-4477-b685-0d1e0e891e35)

