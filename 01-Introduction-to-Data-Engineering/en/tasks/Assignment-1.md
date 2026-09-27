# Assignment 1: An Example of the Data Engineering Lifecycle

## Objective
Map a real-world scenario to the stages of the Data Engineering Lifecycle.

## Scenario
You work for a food delivery app (like UberEats). Every time a user orders a pizza, the app generates a JSON file containing the user's location, the restaurant, and the price. The Data Scientists need this data every morning to predict how many drivers to hire for the next day.

## Your Task
Write a short report (or diagram) explaining how you would build this lifecycle on AWS.

1. **Data Generation:** Where does the data come from?
2. **Ingestion:** How does the data get into your system? (Batch or Streaming?)
3. **Storage:** Where do you save the raw JSON files?
4. **Queries, Modeling, and Transformation:** How do you clean the data? (e.g., removing orders that were cancelled).
5. **Serving Data:** Where do you put the cleaned data so the Data Scientists can access it every morning?

*Hint: Use the concepts learned in Section 2! (EC2, S3, Batch vs Streaming).*
