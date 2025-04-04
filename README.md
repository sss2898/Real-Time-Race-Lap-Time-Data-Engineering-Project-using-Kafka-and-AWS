# 🏁 Real-Time Race Lap Time Data Pipeline using Kafka and AWS

This project simulates a real-time data engineering pipeline for **racing lap times** using **Apache Kafka**, **Python**, and **AWS services** like EC2, S3, Glue, and Athena. It mimics a real-world motorsport analytics system where data flows live from a race to analytical dashboards.

---

## 📦 Tech Stack

- Language: Python
- Streaming: Apache Kafka (on EC2)
- Cloud Services:
  - AWS S3 (storage)
  - AWS Glue Crawler & Catalog (schema inference & metadata)
  - AWS Athena (querying)
- Format: CSV 


## 🗂️ Project Structure

├── Kafka_Producer.ipynb             # Kafka producer for lap time simulation
├── Kafka_Consumer.ipynb             # Kafka consumer sending to S3
├── lap_times_with_precise_milliseconds.csv   # Simulated race dataset
