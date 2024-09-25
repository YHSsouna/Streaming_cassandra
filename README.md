# 🚀 End-to-End Data Engineering Pipeline

This project serves as a **comprehensive guide** to building a full **data engineering pipeline**, from **data ingestion** to **processing** and **storage**. It leverages a powerful tech stack including **Apache Airflow**, **Python**, **Apache Kafka**, **Apache Zookeeper**, **Apache Spark**, **Cassandra**, and **Docker** for **efficient deployment** and **scalability**.

---

## 🛠 System Architecture

This pipeline integrates the following components:

### **1. Data Source**  
🔗 **Randomuser.me API**  
Random user data is fetched from the [randomuser.me](https://randomuser.me/) API.

### **2. Orchestration - Apache Airflow**  
⏳ **Apache Airflow** orchestrates the entire pipeline, storing data in a PostgreSQL database.

### **3. Streaming - Apache Kafka & Zookeeper**  
💬 **Apache Kafka & Zookeeper** stream data from PostgreSQL to the processing engine.

### **4. Monitoring - Control Center & Schema Registry**  
📊 **Control Center & Schema Registry** monitor Kafka streams and manage schemas.

### **5. Data Processing - Apache Spark**  
🔧 **Apache Spark** processes the data using master and worker nodes.

### **6. Storage - Cassandra**  
🗄 **Cassandra** stores the processed data.

---


## 💻 Technology Stack

Here’s the tech stack used in this project:

- **Apache Airflow**
- **Python**
- **Apache Kafka**
- **Apache Zookeeper**
- **Apache Spark**
- **Cassandra**
- **PostgreSQL**
- **Docker**
