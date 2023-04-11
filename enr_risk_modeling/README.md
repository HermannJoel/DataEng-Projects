# Portfolio Risk Modeling data pipeline

## 1. Pipeline Architecture

![Image]( /enr_risk_modeling/env/Images/blx_mdp_etl_pipeline_.jpeg "Portolio risk modling data pipeline")

## 2. Overview
This project aims to model the exposure of a portfolio of renewable energy assets.
The 1st ETL pipeline is orchestrated with Airflow, uses databricks to collect data from excel files and load them in a stagging NoSQL database MongoDB. The second ETL pipeline also orchestrated with Airflow extracts data from the stagging db transform them into fact and dimensions and load them in the Postgres Datawarehouse. The ploty dashboard as well as the postgres data warehouse are deployed in a Heroku Virtual Marchine and are eccessible through an URL.

## 3. ETL

## 4. Data Warehouse Schemas

## 5. Visualization Layer -Plotly-dash
