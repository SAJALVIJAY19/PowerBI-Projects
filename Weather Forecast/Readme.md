# 🌦️ Power BI Weather Dashboard

## 📊 Overview

This Power BI project presents a **real-time weather dashboard** using data fetched from a weather API. It visualizes live and forecasted weather metrics for cities such as:

- Ajmer
- Guwahti
- Hyderabad
- Lucknow
- Mumbai
- Noida

### 🔍 Key Features:
- **Live Temperature & Weather Conditions**
- **Forecasted Trends for the Week**
- **Air Quality Index (AQI) Monitoring**
- **Environmental Metrics** like UV Index, Wind Speed, and Pressure
- **Sunrise & Sunset Times**
- **Rain Probability per Day**

---

## 🧰 Tech Stack

- **Power BI Desktop**
- **Weather API** (e.g., [WeatherAPI.com](https://www.weatherapi.com)
- Data pulled using:
  - Power BI’s **Web Connector** or custom Python/Power Query scripts

---

## 🔗 API Integration

The dashboard consumes weather data from a weather API and visualizes the following endpoints:
- ✅ **Current Weather Data**
- ✅ **7-Day Forecast**
- ✅ **Air Quality Index (AQI)**
- ✅ **Sunrise/Sunset Times**

**Sample Fields Created:**
- `temp_c`, `condition.text`, `humidity`, `uv`, `pressure_mb`, `wind_kph`
- `forecast.forecastday[]`
- `air_quality.pm2_5`, `co`, `no2`, etc.

---
