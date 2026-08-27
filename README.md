OpsLens — Business Analytics API

A data engineering and analytics project that transforms real-world retail transaction data into a PostgreSQL database and exposes business insights through a FastAPI REST API.

🎯 Objective

The project demonstrates an end-to-end data workflow:

Raw Data → Data Cleaning → PostgreSQL → SQL Analytics → FastAPI

It focuses on practical Data Engineering and Data Analytics skills rather than simply building dashboards.

📊 Dataset

The project uses the Online Retail dataset from the UCI Machine Learning Repository.

The dataset contains transaction data from a UK-based online retailer, including:

Invoice number
Product code
Product description
Quantity
Invoice date
Unit price
Customer ID
Country

Dataset source:
https://archive.ics.uci.edu/dataset/352/online+retail

🛠️ Tech Stack
Python
Pandas
SQL
PostgreSQL
SQLAlchemy
FastAPI
Pydantic
Git & GitHub
Docker (planned)
📈 Planned Analytics

OpsLens will answer business questions such as:

What is the total revenue?
What are the monthly revenue trends?
Which products generate the most revenue?
Which customers generate the highest revenue?
Which countries perform the best?
What is the average order value?
What are the busiest sales periods?
What percentage of transactions were cancelled?
🏗️ Project Pipeline
UCI Online Retail Dataset
          ↓
   Data Understanding
          ↓
    Data Cleaning
          ↓
 Data Transformation
          ↓
     PostgreSQL
          ↓
      SQL Analysis
          ↓
     FastAPI API
          ↓
      Testing
          ↓
      Docker
🚧 Project Status

In Development

Currently working on the data understanding and cleaning stage.

👤 Author

Athel
B.Tech CSE (Hons.) — Data Science & Data Engineering
Lovely Professional University

This project is for educational and portfolio purposes and uses publicly available data from the UCI Machine Learning Repository.
