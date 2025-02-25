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
- **Raspberry Pi + Pressure Sensor** detects abnormal pressure.
- **Emergency signal is sent** via **ESP32 WiFi**.
- Nearby **hospitals, people, ambulances, and fire stations** receive alerts.

  ## 🖼️ System Architecture

![image](https://github.com/user-attachments/assets/1e3662e7-e4ad-41bc-9e32-7be377db5413)

![image](https://github.com/user-attachments/assets/7c31d06d-b148-4bdb-8247-8574d5cefa87)

![image](https://github.com/user-attachments/assets/062290f0-99e1-4221-bb83-66f84acdf3d5)

![image](https://github.com/user-attachments/assets/85ce79d9-0794-4bd1-9f0a-fd9d642b124b)

![image](https://github.com/user-attachments/assets/af127a8f-e339-4e1e-a7db-7d4235ec2ae0)


## 📸 Implementation Screenshots
### 🔹 ESP32 + Gyro Sensor Data Logging
