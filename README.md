# Stock-Market-Analysis-End-to-End-Pipeline

## Introduction 
In this project, you will execute an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.

We are going to use different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

## Architecture 
<img src="Architecture.jpg">

## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka


## Dataset Used
You can use any dataset, we are mainly interested in operation side of Data Engineering (building data pipeline) 

Here is the dataset used in the project- https://github.com/GauravVanmane/Stock-Market-Analysis-End-to-End-Pipeline/blob/main/indexProcessed.csv

## Data Analysis
Once the pipeline has been started to upload continuous data to our AWS s3 bucket then we can make use of the AWS Crawler and AWS Glue to make a lookup table for that incoming data. Once the lookup table has been made then we can use SQL commands to analyze our data. Background data is being uploaded to the S3 bucket continuously and getting added to the lookup AWS Athena table. 

## Learning from this project 
- What is Apache kafka?
- Architecture of Kafka?
- What is AWS S3 bucket?
- How to make real-time data pipeline using AWS?
- What is AWS Glue Crawler and Glue Catalog?
- Data analysis Using SQL commands.
