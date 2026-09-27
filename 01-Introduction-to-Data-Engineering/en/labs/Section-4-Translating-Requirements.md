# Section 4 Lab Walkthrough: Translating Requirements on AWS

## Objective
Implement an End-to-End Batch and Streaming Data Pipeline based on stakeholder requirements.

## Introduction
The Marketing team needs a daily report (Batch), and the Data Scientist needs real-time clicks for a Recommender System (Streaming).

## Implementing the Batch Pipeline
1. Create an Amazon S3 bucket for raw data.
2. Set up AWS Glue (or a simple Python script running on a schedule) to run every night at midnight.
3. The script will clean the data and save it into an Amazon Redshift Data Warehouse.

## Setting up the Vector Database
1. For the Data Scientist's Recommender System, traditional databases are too slow for AI lookups.
2. Set up a fast NoSQL database (like Amazon DynamoDB) or an OpenSearch cluster.

## Implementing the Streaming Pipeline
1. Create an Amazon Kinesis Data Stream.
2. Configure the web application to send user clicks instantly to Kinesis.
3. Connect an AWS Lambda function to Kinesis. The Lambda function will read the click and instantly write it to the Vector Database.

*(Complete Assignment 3 to demonstrate your understanding!)*
