🌾 IoT Intelligent Food and Grain Storage Warehouse Management System
📌 Project Overview

This project presents an IoT-based Intelligent Food and Grain Storage Warehouse Management System developed as part of the Introduction to Software Engineering (IS1103-1) course.

The system continuously monitors environmental conditions inside grain warehouses using IoT sensors and provides real-time alerts to prevent spoilage, fire hazards, gas accumulation, and unauthorized access.

It also includes a comparative study of three Software Development Life Cycle (SDLC) models:

Waterfall Model

Incremental Model

Spiral Model

The Spiral Model was identified as the most suitable model for this IoT-based system due to its strong risk management and iterative development approach.

🎯 Problem Statement

Traditional grain storage methods rely heavily on manual monitoring, which:

Is slow and unreliable

Fails to detect early warning signs

Leads to grain spoilage and economic losses

This project aims to design and analyze an automated IoT-based monitoring system that ensures safe storage conditions through real-time environmental monitoring and alert generation.

🛠️ System Architecture

The system consists of:

Sensor Module – Collects environmental data

Microcontroller Module – Processes sensor inputs

Cloud Platform – Stores and visualizes data

User Interface – Displays dashboards and sends alerts

📊 Data Collected

The system monitors:

🌡️ Temperature

💧 Humidity

🫁 Gas Levels (CO₂ detection)

🔥 Smoke (Fire detection)

🚶 Motion (Unauthorized movement detection)

Each reading is stored with a timestamp for:

Real-time monitoring

Historical analysis

Future predictive analysis

⚙️ Hardware Components Used

NodeMCU ESP8266 (WiFi-enabled microcontroller)

DHT11 – Temperature & Humidity Sensor

MQ135 – Gas Sensor (CO₂ detection)

MQ2 – Smoke Sensor

PIR Sensor – Motion Detection

💻 Software & Technologies Used
Programming Languages

Embedded C

Arduino

Python

IoT & Cloud Platforms

ThingSpeak (Data storage & visualization)

Blynk Application (Mobile notifications)

📋 Functional Requirements

Continuous environmental monitoring

Wireless data transmission

Cloud data storage

Real-time dashboards

Threshold-based alert generation

Remote monitoring capability

📈 Non-Functional Requirements

High reliability

Low latency

Secure data transmission

Scalability

Low power consumption

Robustness against network failures

🔄 SDLC Models Compared
1️⃣ Waterfall Model

Structured and well-documented

Less flexible for changes

Not ideal for dynamic IoT systems

2️⃣ Incremental Model

Developed in stages

Allows gradual improvements

Easier testing

3️⃣ Spiral Model (Selected Model ✅)

Iterative development

Continuous risk analysis

Best suited for hardware–software integration

Flexible and scalable

🧪 Experiments & Testing

Sensor calibration testing

Abnormal condition simulation

Alert response verification

Network reliability testing

Scalability evaluation

📊 Results

Reduced grain spoilage

Improved monitoring accuracy

Instant alert generation

Reduced dependency on manual inspection

Stable long-term system performance

⚠️ Limitations

Requires stable internet connectivity

Hardware maintenance required

Network issues may delay alerts

Limited effectiveness in remote areas

🚀 Future Enhancements

AI-based predictive analytics

Centralized multi-warehouse monitoring

GPRS-based communication

Dedicated mobile application

Enhanced cloud integration

Advanced alert mechanisms
