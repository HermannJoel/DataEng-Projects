# DataEng-Projects

## 1. enr risk modeling data pipeline
![Image]( /enr_risk_modeling/env/Images/blx_mdp_etl_pipeline.jpeg "Portolio risk modling data pipeline")

## 
This project aims to model the exposure of a portfolio of renewable energy assets.
The 1st ETL pipeline is orchestrated with Airflow, uses databricks to collect data from excel files and load them in a stagging NoSQL database MongoDB. The second ETL pipeline also orchestrated with Airflow extracts data from the stagging db transform them into fact and dimensions and load them in the Postgres Datawarehouse. The ploty dashboard as well as the postgres data warehouse are deployed in a Heroku Virtual Marchine and are eccessible through an URL.

## 2. enr portfolio modeling data pipeline
![Image]( /enr_risk_modeling/env/Images/enr_portfolio_modeling.jpeg "enr portfolio modeling data pipeline")

## 3. Azure oltp-olap data pipeline
![Image]( /azure_oltp_olap/env/Images/oltp-olap.jpeg "Azure oltp-olap data pipeline") 
