Here’s an enhanced and beautified version of your README.md file:

---

# 🌦️ Weather Data Retrieval and Analysis System

## Overview

This project retrieves weather data from the OpenWeatherMap API at configurable intervals, converts temperature values based on user preferences, and provides daily weather summaries, including parameters like humidity and wind speed. The system is built to be robust, easy to set up, and extendable.

## ✨ Features

- **System Setup:** Initializes and connects to the OpenWeatherMap API using a valid API key.
- **Data Retrieval:** Retrieves weather data for specified locations at configurable intervals.
- **Temperature Conversion:** Converts temperature values from Kelvin to Celsius or Fahrenheit based on user preferences.
- **Daily Weather Summary:** Provides daily summaries, including average, maximum, and minimum temperatures, along with dominant weather conditions.
- **Additional Parameters:** Supports analysis of additional weather parameters such as humidity and wind speed.
- **5-Day Weather Forecast:** Offers a 5-day weather forecast.

## 🛠️ Design Choices

- **Modularity:** The system is divided into distinct modules for initialization, data retrieval, temperature conversion, and summary generation, making it easy to maintain and extend.
- **Configurability:** API call intervals and temperature units are configurable for flexibility.
- **Extensibility:** Designed to easily incorporate additional weather parameters from the OpenWeatherMap API.

## 📋 Requirements

- Screen resolution: 1070x680 (minimum)
- Node.js (optional if the system does not have a live server utility)

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed on your system

### 📥 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/mrudulap26/Real-Time-Data-Processing-System-for-Weather-Monitoring.git
   ```

2. **Install Backend Dependencies**
   ```bash
   npm install
   ```

3. **Run the Live Server**
   ```bash
   npm install http-server -g
   http-server -p 8080
   ```

## ✅ Running Tests

You can add and run tests to ensure that everything is working correctly.

---
