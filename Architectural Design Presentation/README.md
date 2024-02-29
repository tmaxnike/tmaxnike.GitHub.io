## Data Ingestion   
Kafka acts as a high-throughput streaming platform, ingesting real-time credit card transactions, account logins, and other relevant data.
NiFi ingests historical data from various sources like transaction logs, customer profiles, and external fraud intelligence feeds into HDFS, the distributed storage system.  

## Data Processing  
Spark Utilizes YARN, the resource manager, to run parallel processing tasks on HDFS data. Spark analyzes transactions, identifying anomalies and suspicious patterns through machine learning algorithms.
Hive Enables querying of historical data stored in HDFS using SQL-like syntax. Analysts can identify trends and patterns across historical data to refine fraud detection models.
HBase Stores real-time data with low latency for fast lookups. Spark can access HBase for real-time enrichment of transaction data with customer information or past fraud flags.  

##  Fraud Detection & Alerting  

Solr Indexes enriched transaction data, enabling fast search and retrieval by analysts investigating flagged transactions.
Alerting: When a transaction is flagged as fraudulent, alerts are sent to security teams in real-time using Kafka or other notification systems.
Interactive Analysis: Hive and Solr enable analysts to interactively explore data, validate alerts, and investigate suspicious activities using tools like Tableau or Kibana.
