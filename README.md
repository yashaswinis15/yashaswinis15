<h1 align="center">Hi 👋, I'm Yashaswini</h1>

<h3 align="center">
Data Engineer | Cloud Data Platforms | ETL/ELT | Distributed Data Processing
</h3>

<p align="center">
Building scalable data pipelines and cloud-based data platforms that transform raw data into reliable, analytics-ready datasets.
</p>

---

## 👩‍💻 About Me

- 🔹 Data Engineer focused on building scalable **ETL/ELT and data processing pipelines**
- ☁️ Working with cloud data platforms across **AWS and Azure**
- ⚡ Experienced with **Spark, PySpark, Kafka, Airflow, Databricks, and dbt**
- 🏗️ Interested in **Data Architecture, Data Warehousing, Distributed Processing, and Streaming**
- 📊 Building data systems that support reliable analytics and business insights
- 🚀 Currently building **FinStream — Real-Time Fraud Detection & Analytics Pipeline**

---

## 🛠️ Tech Stack

### Languages

<p>
<img src="https://skillicons.dev/icons?i=python" height="45"/>
<img src="https://skillicons.dev/icons?i=postgres" height="45"/>
<img src="https://skillicons.dev/icons?i=bash" height="45"/>
</p>

`Python` • `SQL` • `Bash`

### Data Engineering

<p>
<img src="https://skillicons.dev/icons?i=kafka" height="45"/>
</p>

`Apache Spark` • `PySpark` • `Apache Kafka` • `Apache Airflow` • `Databricks` • `dbt`

### Cloud

<p>
<img src="https://skillicons.dev/icons?i=aws,azure" height="45"/>
</p>

**AWS**

`S3` • `Glue` • `Redshift` • `EMR` • `Lambda` • `Kinesis` • `Step Functions` • `CloudWatch` • `IAM`

**Azure**

`Azure Data Factory` • `Azure Synapse Analytics` • `Azure Data Lake Storage`

### Databases & Warehousing

<p>
<img src="https://skillicons.dev/icons?i=postgres,mysql" height="45"/>
</p>

`PostgreSQL` • `MySQL` • `SQL Server` • `Oracle` • `Snowflake` • `Amazon Redshift` • `Azure Synapse`

### DevOps & Tools

<p>
<img src="https://skillicons.dev/icons?i=docker,git,github,linux" height="45"/>
</p>

`Docker` • `Git` • `GitHub` • `Linux` • `Jira`

---

# 🚀 Featured Project

## FinStream — Real-Time Fraud Detection & Analytics Pipeline

A production-style data engineering project designed to process financial transactions, detect suspicious activity, and provide analytics-ready data through a real-time streaming architecture.

### 🔄 Pipeline Architecture

```text
PostgreSQL
    │
    ▼
Debezium CDC
    │
    ▼
Apache Kafka
    │
    ▼
Spark Structured Streaming
    │
    ▼
Delta Lake
Bronze → Silver → Gold
    │
    ▼
dbt
    │
    ▼
PostgreSQL
    │
    ▼
Grafana
