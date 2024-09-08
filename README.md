# Real-Time Streaming: Integrating Apache Flink, Kafka, Postgres, Elasticsearch, Kibana, and Docker

This project demonstrates how to integrate Apache Flink, Kafka, Postgres, Elasticsearch, and Kibana to build a robust real-time data processing architecture. It is based on the Medium article by Yusuf Ganiyu. (https://medium.com/towards-data-engineering/real-time-streaming-at-scale-integrating-apache-flink-kafka-postgres-elasticsearch-kibana-and-132a7fd59e00)

<img width="1461" alt="System Architecture" src="https://github.com/user-attachments/assets/ba963f09-0709-4858-adb9-d201ee8d850c">

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

# Activate docker containers:

<img width="954" alt="Activate docker containers" src="https://github.com/user-attachments/assets/d081bf6b-d5f3-4483-ab0c-c389c5730b10">

# This is what main.py generate:

<img width="950" alt="This is what main py generate" src="https://github.com/user-attachments/assets/6b1990b1-f001-4432-9dc7-df9880d15554">

# Example how kafka consumer works:

<img width="948" alt="Start kafka consumer" src="https://github.com/user-attachments/assets/252ce68d-ef27-4ecf-8d08-bc5ce64d59a2">

# To iniciate Flink cluster:

<img width="731" alt="iniciate Flink cluster" src="https://github.com/user-attachments/assets/270cc701-e24c-426f-a3d0-d392a6bbf0cb">

# Access Flink cluster:

<img width="958" alt="Access Flink cluster in port 8081" src="https://github.com/user-attachments/assets/c15e7750-f9f6-4fa7-a9f9-558506e2eb75">

# Task manager Flink cluster:

<img width="954" alt="task manager properties 1" src="https://github.com/user-attachments/assets/360e862d-4037-41b6-8c04-bf5a36256820">
<img width="807" alt="task manager properties 2" src="https://github.com/user-attachments/assets/d883e0e9-8efb-44e2-b986-b20efc2ac8ed">

# Create java project before compile:

<img width="584" alt="create a new project jetbrains" src="https://github.com/user-attachments/assets/f478c2e7-bc41-4f38-b15a-bb858f0a1b13">

# Compile:

<img width="953" alt="compile" src="https://github.com/user-attachments/assets/017945cf-0e5c-453c-af53-ac8b772a6ea0">

# mvn package:

<img width="514" alt="mvn package" src="https://github.com/user-attachments/assets/4ebca15e-35d5-48c3-b8bf-807076ed5125">

# Sumit SNAPSHOT.jar:

<img width="946" alt="Sumit SNAPSHOT jar" src="https://github.com/user-attachments/assets/0dbddaeb-e113-453f-b506-096024d21f36">

#Running job in Flink:

<img width="958" alt="Running jobs in Flink" src="https://github.com/user-attachments/assets/bffa132a-93e6-4b71-97c9-4a55d9457820">

# Data sent to postgres by docker container:

<img width="956" alt="Data sent to postgres by docker container" src="https://github.com/user-attachments/assets/61771e90-966c-4f90-9792-003bfc7fe28f">

# Get the correct date format in Elasticsearch:

<img width="958" alt="Get the correct date format in elastic shearch" src="https://github.com/user-attachments/assets/9099bcde-e3cf-43fe-880f-633e5aa0dac5">

# Kibana dashboard

<img width="958" alt="Elasticsearch dashboard" src="https://github.com/user-attachments/assets/0deef4cd-beed-42c1-9b21-99993de945c4">
