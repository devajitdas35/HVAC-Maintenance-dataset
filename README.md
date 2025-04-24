# HVAC-Maintenance-dataset
This repository contains the **HVAC Maintenance Dataset** for predictive maintenance and anomaly detection in HVAC systems. The dataset includes sensor data collected from **DHT11** (temperature and humidity) and **BMP280** (temperature and pressure) sensors, transmitted via the **MQTT protocol**. The dataset can be used for tasks such as anomaly detection, system failure prediction, and time-series analysis of HVAC system performance.

## Dataset Structure

The dataset includes the following columns:

- **id**: Unique identifier for each data point.
- **temperature_bmp**: Temperature reading from the BMP280 sensor (°C).
- **pressure**: Atmospheric pressure reading from the BMP280 sensor (hPa).
- **temperature_dht**: Temperature reading from the DHT11 sensor (°C).
- **humidity**: Humidity reading from the DHT11 sensor (%).
- **timestamp**: Timestamp of the data collection (in UTC format).

## Features

- **Sensing Layer**: Includes IoT sensors (temperature, humidity, pressure).
- **Processing Layer**: Data is processed using Node-RED and stored in a MySQL database.
- **Application Layer**: Data is visualized through a real-time dashboard for system monitoring.

## Purpose

The dataset can be used to:
- Build machine learning models for **predictive maintenance** of HVAC systems.
- Detect **anomalies** and predict system **failures**.
- Analyze sensor data over time for performance insights.

## Installation

To access the dataset, clone the repository:

