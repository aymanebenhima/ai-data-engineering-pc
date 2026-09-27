# Section 2 Lab Walkthrough: The Data Engineering Lifecycle on AWS

## Objective
Set up a basic Data Engineering Lifecycle using AWS services.

## Guidelines before you start
- Always double-check that you are using Free Tier eligible resources.
- Delete your resources (like S3 buckets or EC2 instances) immediately after completing the lab.

## Introduction & Setting up the Lab
In this lab, we will simulate Data Generation, Ingestion, and Storage.

1. **Generation:** We will use a simple Python script to generate fake "user clicks".
2. **Ingestion:** We will use AWS Kinesis to capture these clicks.
3. **Storage:** We will save these clicks in an Amazon S3 Bucket (a cloud folder).

## Preview of the Lab Content
- Step 1: Open the AWS Console and search for **S3**. Create a new bucket named `my-data-lake-[your-name]`.
- Step 2: Search for **Kinesis Data Firehose**. Create a new delivery stream.
- Step 3: Set the source as "Direct PUT" and the destination as your new S3 bucket.
- Step 4: Run the provided Python script (found in the assignment materials) to send clicks to your Kinesis stream.
- Step 5: Check your S3 bucket—you should see new files appearing with your data!

*(Complete Assignment 1 to solidify this knowledge!)*
