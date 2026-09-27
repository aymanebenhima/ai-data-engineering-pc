# Section 3 Lab Walkthrough: Investigating Your Architecture on AWS

## Objective
Learn how to monitor a web app and apply the AWS Well-Architected Framework principles to improve it.

## Introduction to the Lab
You have a basic web app running on a single Amazon EC2 instance. This is a "Monolith" architecture. It works fine for 10 users, but what happens if 10,000 users visit?

## Monitoring the Web App
1. Go to the AWS Console and open **CloudWatch** (AWS's monitoring tool).
2. Look at the CPU Utilization metric for your EC2 instance. If it goes above 80%, the server is struggling!

## Applying the Principles of Good Data Architecture
If your server is crashing (Reliability Pillar) and slow (Performance Efficiency Pillar), how do you fix it?
1. **Vertical Scaling (Bigger Server):** Stop the EC2 instance and change it to a more powerful machine. (Fast, but expensive).
2. **Horizontal Scaling (More Servers):** Use an Auto-Scaling Group to automatically launch 5 smaller EC2 instances when traffic is high, and turn them off when traffic is low (Cost Optimization).

*(Complete Assignment 2 to test your architecture skills!)*
