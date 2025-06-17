# Weather-Forecast-app

# 🌍 Weather Forecast App using Java Swing

A desktop application built with **Java Swing** that displays global weather forecasts and real-time room temperature & humidity using an **ESP32** and **DHT22 sensor**. It integrates **OpenWeatherMap API** for global data and the **Blynk IoT platform** for live sensor readings.

---

## 🚀 Features

- **🌐 Global Weather Forecast**  
  Get current weather data for any city worldwide, including:
  - Temperature
  - Weather description
  - Feels like temperature
  - Min/Max temperature
  - Humidity
  - Wind speed

- **🌤️ Visual Weather Icons**  
  Dynamic icons based on current weather conditions.

- **🌡️ Room Environment Monitoring**  
  Real-time temperature and humidity from an ESP32 + DHT22 sensor using Blynk.

- **📍 Location Search**  
  Search for weather info for any city using the OpenWeatherMap API.

- **🔁 Dynamic Updates**  
  Periodic updates of room temperature and humidity readings.

- **🎨 Custom Look and Feel**  
  Enhanced UI using **JTattoo Aluminium** theme.

---

## 🛠 Technologies Used

### 💻 Application
- **Java Swing** – GUI Framework
- **Apache Maven** – Build tool

### 🌐 APIs & Platforms
- **OpenWeatherMap API** – Global weather data
- **Blynk IoT Platform** – Real-time sensor data

### 📡 Hardware
- **ESP32 Microcontroller**
- **DHT22 Temperature & Humidity Sensor**

### 📚 Libraries
- `org.json` – JSON parsing
- `com.google.code.gson` – JSON processing
- `com.googlecode.json-simple` – Alternate JSON handling
- `com.jtattoo.JTattoo` – Look and Feel (Aluminium theme)

---

## ⚙️ Setup and Installation

### ✅ Prerequisites
Make sure the following are installed:

- **Java Development Kit (JDK)** – Version 22 or higher  
- **Apache Maven** – For dependency management and build  
- **Git** – To clone the repository  
- **Arduino IDE** – For setting up the ESP32 microcontroller
