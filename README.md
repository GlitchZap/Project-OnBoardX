# 🚗 Project-OnBoardX - IoT-Based Vehicle Monitoring System

## 📌 Overview
**Endurance** is a real-time **IoT-based vehicle monitoring system** that integrates **ESP32, Raspberry Pi, Firebase, FastAPI, Flask, and Machine Learning** to ensure vehicle safety and efficient monitoring.

## 🔥 Features
### 🚀 Real-Time Data Collection
- **ESP32 + Gyro Sensor** collects **acceleration & velocity** data.
- Data is stored in **Firebase** and processed using **FastAPI**.

### 📊 Data Processing & Visualization
- **FastAPI generates graphs** from raw sensor data (stored as bits).
- **ML Model** calculates **average acceleration & velocity**.
- **React UI + Flask** displays real-time **location tracking (latitude & longitude)**.

### 🚨 Speed & Acceleration Alerts
- If high acceleration/velocity is detected, alerts are sent via **EmailJS / Twilio**.
- Helps prevent **accidents by notifying drivers to slow down**.

### 🆘 Accident Detection & Emergency Alerts
