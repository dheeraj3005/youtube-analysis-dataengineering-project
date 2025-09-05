# Data Engineering YouTube Analysis Project
**by Dheeraj Lokesh**

---

## Overview

This project aims to securely manage, streamline, and perform analysis on structured and semi-structured YouTube video data, based on video categories and trending metrics.

---

## Project Goals

- **Data Ingestion:** Build a mechanism to ingest data from different sources.
- **ETL System:** Transform raw data into the proper format.
- **Data Lake:** Centralize storage for data coming from multiple sources.
- **Scalability:** Ensure the system scales as data size increases.
- **Cloud:** Use AWS to process large amounts of data efficiently.
- **Reporting:** Build a dashboard to answer key questions.

---

## Services We Will Be Using

- **Amazon S3:** Object storage service providing scalability, availability, security, and performance.
- **AWS IAM:** Identity and Access Management for secure access to AWS resources.
- **Amazon QuickSight:** Scalable, serverless, machine learning-powered business intelligence (BI) service for the cloud.
- **AWS Glue:** Serverless data integration service for analytics, machine learning, and application development.
- **AWS Lambda:** Serverless computing service for running code without managing servers.
- **AWS Athena:** Interactive query service for analyzing data directly in S3.

---

## Dataset Used

This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over many months. Up to 200 trending videos are published every day for various locations.  
For each region, data is stored in its own file and includes:

- Video title
- Channel title
- Publication time
- Tags
- Views
- Likes and dislikes
- Description
- Comment count

A `category_id` field (varies by region) is also included in a JSON file linked to each area.

Dataset link: [Kaggle - YouTube Trending Videos](https://www.kaggle.com/datasets/datasnaek/youtube-new)
