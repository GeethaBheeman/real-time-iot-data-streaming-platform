\# Real-Time IoT Data Streaming and Event Processing Platform



\## Overview



This project demonstrates two end-to-end real-time data streaming workflows:



1\. An IoT telemetry pipeline using Python, MQTT, Eclipse Mosquitto, ThingsBoard, Firebase, and Docker.

2\. A Kafka-based vehicle-location streaming pipeline using Python, Apache Kafka, Node.js, Express.js, and Docker.



\## Architecture



\### IoT Telemetry Pipeline



Python MQTT Publisher  

→ Eclipse Mosquitto  

→ ThingsBoard  

→ Rule Chain Processing  

→ Firebase Realtime Database



\### Kafka Vehicle Location Pipeline



Python Kafka Producer  

→ Apache Kafka Topic  

→ Node.js Kafka Consumer  

→ Express Web Server  

→ Browser Output



\## Technologies Used



\- Python

\- JavaScript

\- Node.js

\- Express.js

\- Apache Kafka

\- MQTT

\- Eclipse Mosquitto

\- ThingsBoard

\- Firebase Realtime Database

\- Docker

\- Docker Compose

\- Confluent Platform

\- ZooKeeper

\- REST APIs

\- JSON



\## Project Structure



```text

iot-streaming-platform/

├── Project\_24\_Docker/

│   ├── docker-compose.yml

│   └── mosquitto/

│       └── config/

│           └── mosquitto.conf

├── Project\_24\_MQTT/

│   ├── paho-mqtt/

│   │   └── TBPublish.py

│   └── ThingsBoard/

│       └── docker-compose.yml

├── Project\_Kafka/

│   └── Project\_24\_2\_Kafka/

│       ├── kafka-docker/

│       ├── NodeJSConsumer/

│       └── pythonProducer/

│           └── PublishVehicleCoordinates.py

├── docs/

│   └── images/

├── .gitignore

└── README.md

