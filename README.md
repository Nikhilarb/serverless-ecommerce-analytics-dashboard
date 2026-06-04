# Serverless E-Commerce Analytics Dashboard

## Overview

Built an end-to-end serverless analytics pipeline on AWS that generates e-commerce order data, stores it across operational and analytics data layers, queries the data using SQL, and visualizes business insights through interactive dashboards.

## AWS Services Used

* AWS Lambda
* Amazon DynamoDB
* Amazon S3
* Amazon Athena
* AWS Glue
* Amazon QuickSight
* AWS IAM

## Architecture

1. AWS Lambda generates sample e-commerce order data.
2. Data is written to DynamoDB for operational storage.
3. Data is written to Amazon S3 for analytics storage.
4. AWS Glue catalogs the data.
5. Amazon Athena queries the data using SQL.
6. Amazon QuickSight visualizes insights through dashboards and KPI metrics.

## Analytics & Reporting

The dashboard includes:

* Revenue trends over time
* Product category performance
* Regional sales analysis
* Total Revenue KPI
* Total Orders KPI
* Average Order Value KPI
* Interactive date range filters

## Skills Demonstrated

* Serverless architecture
* Data pipeline design
* SQL analytics
* Cloud data storage
* Data visualization
* IAM permissions management
* AWS CLI deployment workflows

## Key Learnings

* Operational vs analytics data layers
* Lambda-based data ingestion
* DynamoDB and S3 integration
* Athena SQL querying
* AWS Glue data cataloging
* QuickSight dashboard development

## Project Documentation

Detailed project walkthrough and implementation notes are included in this repository.
