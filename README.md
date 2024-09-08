# Apache Flink E-Commerce Analytics with Elasticsearch and Postgres

This repository contains an Apache Flink application for real-time sales analytics built using Docker Compose to orchestrate the necessary infrastructure components, including Apache Flink, Elasticsearch, and Postgres. The application processes financial transaction data from Kafka, performs aggregations, and stores the results in both Postgres and Elasticsearch for further analysis.

## Requirements
- Docker
- Docker Compose

# Real-Time Streaming at Scale: Integrating Apache Flink, Kafka, Postgres, Elasticsearch, Kibana, and Docker

This project demonstrates how to integrate Apache Flink, Kafka, Postgres, Elasticsearch, and Kibana to build a robust real-time data processing architecture. It is based on the Medium article by Yusuf Ganiyu. (https://medium.com/towards-data-engineering/real-time-streaming-at-scale-integrating-apache-flink-kafka-postgres-elasticsearch-kibana-and-132a7fd59e00)

![Architecture]("C:\Users\danie\Desktop\Apache-Flink Docker\Procesos\System Architecture.png")

## Components

### Apache Kafka
- **Description**: A distributed streaming platform that excels at publishing and subscribing to streams of records, storing these records, and processing them as they occur.
- **Usage in Project**: Real-time data ingestion.

### Apache Flink
- **Description**: A framework and distributed processing engine for stateful computations over unbounded and bounded data streams.
- **Usage in Project**: Real-time data processing, including aggregations and complex computations.

### PostgreSQL (Postgres)
- **Description**: A powerful, open-source object-relational database system known for its reliability and performance.
- **Usage in Project**: Storage of processed data for transactional needs.

### Elasticsearch
- **Description**: A distributed, RESTful search and analytics engine.
- **Usage in Project**: Indexing data for real-time analytics.

### Kibana
- **Description**: A visualization dashboard for Elasticsearch.
- **Usage in Project**: Visualization and analysis of data stored in Elasticsearch.

## Architecture

1. **Data Ingestion**: Kafka acts as the entry point for streaming data.
2. **Stream Processing**: Flink processes the data, performing tasks such as aggregations and enrichments.
3. **Storage and Indexing**: Processed data is stored in Postgres and indexed in Elasticsearch.
4. **Visualization**: Kibana is used to visualize the data indexed in Elasticsearch.

## Results:
