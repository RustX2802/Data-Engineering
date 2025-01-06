# Realtime Data Streaming: End-to-End Data Engineering Project

**A Comprehensive Guide to Building a Modern Data Pipeline**

## Table of Contents
1.  [Introduction](#introduction)
2.  [System Architecture](#system-architecture)
3.  [Key Learnings](#key-learnings)
4.  [Technology Stack](#technology-stack)

## Introduction

This project provides a hands-on experience in building a complete, end-to-end data engineering pipeline. It shows how to ingest, process, and store data using a combination of industry-standard tools and technologies. The entire project is containerized using Docker, making it easy to deploy and replicate the environment.
## System Architecture

![System Architecture](https://github.com/RustX2802/Data-Engineering/blob/main/Data%20engineering%20architecture.png)

The project is designed with the following components:

- **Data Source**: We use `randomuser.me` API to generate random user data for our pipeline.
- **Apache Airflow**: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.
- **Apache Kafka and Zookeeper**: Used for streaming data from PostgreSQL to the processing engine.
- **Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.
- **Apache Spark**: For data processing with its master and worker nodes.
- **Cassandra**: Where the processed data will be stored.

## Key Learnings

- Setting up a data pipeline with Apache Airflow
- Real-time data streaming with Apache Kafka
- Distributed synchronization with Apache Zookeeper
- Data processing techniques with Apache Spark
- Data storage solutions with Cassandra and PostgreSQL
- Containerizing your entire data engineering setup with Docker

## Technology Stack

- Apache Airflow: Data pipeline orchestration.
- Python: For data processing and Airflow DAGs.
- Apache Kafka: Real-time stream processing.
- Apache Zookeeper: Distributed coordination for Kafka.
- Apache Spark: Distributed data processing.
- Cassandra: Highly scalable database.
- PostgreSQL: Relational database for initial data storage.
- Docker: Containerization platform.
