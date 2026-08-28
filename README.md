# OpsLens — Business Analytics API

> **An end-to-end Data Engineering & Analytics project that transforms raw retail transaction data into a PostgreSQL database and exposes business insights through a FastAPI REST API.**

---

## Overview

**OpsLens** is a business analytics API built around real-world retail transaction data.

The project demonstrates a complete data workflow:

```text
Raw Retail Data
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
PostgreSQL
      ↓
SQL Analytics
      ↓
FastAPI REST API
      ↓
Testing
      ↓
Docker
```

Rather than focusing solely on dashboards, OpsLens focuses on **practical Data Engineering, SQL, backend API development, and Business Analytics**.

---

## Dataset

The project uses the **Online Retail Dataset** from the **UCI Machine Learning Repository**.

The dataset contains transaction records from a UK-based online retailer, including:

| Column        | Description                  |
| ------------- | ---------------------------- |
| `InvoiceNo`   | Invoice / transaction number |
| `StockCode`   | Product code                 |
| `Description` | Product description          |
| `Quantity`    | Quantity purchased           |
| `InvoiceDate` | Date and time of transaction |
| `UnitPrice`   | Price per item               |
| `CustomerID`  | Customer identifier          |
| `Country`     | Customer's country           |

**Dataset Source:**
[UCI Machine Learning Repository — Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)

---

### Data Engineering & Analytics

* 🐍 **Python**
* 🐼 **Pandas**
* 🗄️ **PostgreSQL**
* 📊 **SQL**
* 🔗 **SQLAlchemy**

### Backend

* ⚡ **FastAPI**
* 📦 **Pydantic**

### Development & Deployment

* 🐙 **Git & GitHub**
* 🐳 **Docker** *(planned)*

---

## Business Analytics

OpsLens is designed to answer practical business questions such as:

* What is the **total revenue**?
* What are the **monthly revenue trends**?
* Which products generate the **most revenue**?
* Which customers generate the **highest revenue**?
* Which countries perform the **best**?
* What is the **Average Order Value (AOV)**?
* What are the **busiest sales periods**?
* What percentage of transactions were **cancelled**?

These insights will ultimately be accessible through the **FastAPI REST API**.

---

## Project Architecture

```text
                    ┌─────────────────────┐
                    │  UCI Online Retail  │
                    │       Dataset       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Data Understanding  │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    Data Cleaning    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Data Transformation │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │     PostgreSQL      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    SQL Analytics    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │     FastAPI API     │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │       Testing       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │       Docker        │
                    │      (Planned)      │
                    └─────────────────────┘
```

---

## Project Structure

```text
OpsLens/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── data_exploration.ipynb
│
├── src/
│   ├── data/
│   ├── database/
│   ├── analytics/
│   └── api/
│
├── tests/
│
├── requirements.txt
├── README.md
└── .gitignore
```

> Project structure may evolve as development progresses.

---

## Project Status

**In Development**

### Current Progress

* [x] Dataset selected
* [x] Project architecture defined
* [ ] Data understanding
* [ ] Data cleaning
* [ ] Data transformation
* [ ] PostgreSQL database setup
* [ ] SQL analytics
* [ ] FastAPI endpoints
* [ ] API testing
* [ ] Dockerization

---

## What This Project Demonstrates

OpsLens is designed to demonstrate practical skills in:

* Data cleaning and preprocessing
* Exploratory data analysis
* Relational database design
* PostgreSQL
* SQL analytics and aggregations
* Python data pipelines
* REST API development
* FastAPI
* Pydantic data validation
* SQLAlchemy database integration
* API testing
* Containerization with Docker

---

## Author

### Athel

**B.Tech CSE (Hons.) — Data Science & Data Engineering**
**Lovely Professional University**

This project is created for **educational and portfolio purposes** using publicly available data from the UCI Machine Learning Repository.

---

## Project Goal

> **Turn raw business data into reliable, queryable, and accessible business intelligence through a complete data pipeline and REST API.**

**OpsLens** — *From transactions to business insights.*
