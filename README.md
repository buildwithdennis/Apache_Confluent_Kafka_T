# Apache Kafka with Confluent - Producer and Consumer Example

This repository demonstrates how to use **Apache Kafka** with **Confluent Cloud** to build a simple **Producer-Consumer** data pipeline using Python.  
It includes Jupyter notebooks that show how to send and receive messages between Kafka topics through the Confluent platform.

---

## 📘 Project Overview

The project is divided into two main parts:

1. **Apache_Kafka_Confluent_Producer.ipynb**  
   Demonstrates how to:
   - Connect to a Kafka cluster in Confluent Cloud.
   - Produce messages to a Kafka topic using Python.
   - Configure authentication with Confluent credentials.
   - Handle serialization and delivery reports.

2. **Apache_Kafka_Confluent_Consumer.ipynb**  
   Demonstrates how to:
   - Consume messages from a Kafka topic.
   - Continuously listen for new messages.
   - Acknowledge and process data in real time.
   - Gracefully handle errors and interruptions.

---

## 🧰 Technologies Used

- **Apache Kafka**
- **Confluent Cloud**
- **Python 3.x**
- **Confluent Kafka Python Client (`confluent-kafka`)**
- **Jupyter Notebook**

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/dennissmithkofi/kafka-confluent-demo.git
cd kafka-confluent-demo 
```
### 2. Create and Activate a Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

```
### 3. Install Dependencies
```bash
pip install confluent-kafka jupyter


```
### 4. Run the Notebooks
#Launch Jupyter and open the notebooks:
```bash
jupyter notebook
```

Then open:

Apache_Kafka_Confluent_Producer.ipynb

Apache_Kafka_Confluent_Consumer.ipynb

### 🧪 Example Flow

Producer sends sample messages to a Kafka topic (e.g., "test-topic").

Consumer subscribes to the same topic and prints incoming messages in real time.

Demonstrates the core publish-subscribe model in Kafka using Confluent’s managed service.

### 📊 Learning Objectives

Understand how Kafka Producers and Consumers work.

Learn how to integrate with Confluent Cloud using API keys.

Practice event streaming and message queue concepts.

Get hands-on experience with real-time data processing in Python.

### 👨‍💻 Author

Dennis Smith
📧 dennissmithkofi@gmail.com
🌍 https://github.com/buildwithdennis