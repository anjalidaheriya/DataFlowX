# 🚀 StreamForge: End-to-End Data Engineering Pipeline

An **end-to-end data engineering pipeline** that orchestrates **data ingestion, processing, and storage** using modern big data tools.  
All components are containerized with **Docker** for seamless deployment and scalability.  

## 🛠 Tech Stack
- **Apache Airflow** – Workflow orchestration  
- **Apache Kafka & Zookeeper** – Real-time data ingestion & streaming  
- **Apache Spark** – Distributed data processing & transformations  
- **Apache Cassandra** – Scalable NoSQL storage  
- **Python** – Glue logic, transformations & operators  
- **Docker & Docker Compose** – Containerization & deployment  

---

## 📌 Project Overview
This project simulates an **enterprise-grade data pipeline** with the following workflow:

1. **Ingestion Layer**  
   - Data is ingested into **Kafka topics** (e.g., streaming JSON logs, transactions, or sensor data).  

2. **Processing Layer**  
   - **Apache Spark Structured Streaming** consumes Kafka messages.  
   - Performs ETL (Extract, Transform, Load) operations: cleaning, aggregation, enrichment.  

3. **Storage Layer**  
   - Transformed data is persisted into **Cassandra**, enabling fast queries on large volumes of structured data.  

4. **Orchestration Layer**  
   - **Airflow DAGs** schedule & monitor data ingestion → processing → storage workflows.  

5. **Deployment**  
   - Entire pipeline runs in **Docker Compose**, ensuring portability and scalability.  

---

## 📂 Project Structure 
<img width="3274" height="1221" alt="Data engineering architecture" src="https://github.com/user-attachments/assets/d718f07b-077a-4924-8dd9-f6f93eca87e3" />



