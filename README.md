# 🌱 SmartAgriAI: AI-Powered Smart Farming for Sustainable Agriculture

A smart, low-cost AI and IoT-based decision support system that empowers smallholder farmers in rural Kenya with real-time insights to improve crop yields, save water, and adapt to climate change.

---

## 🌍 Project Overview

**SmartAgriAI** is an intelligent agriculture assistant combining Internet of Things (IoT), Machine Learning (ML), and cloud services to enhance precision farming. The system enables farmers to make data-driven decisions by monitoring environmental conditions and predicting key farming activities such as watering, fertilizing, and disease risk.

---

## 🎯 UN SDG Goals Addressed

- **SDG 2 – Zero Hunger**: Improves agricultural productivity and resilience.
- **SDG 13 – Climate Action**: Promotes sustainable, climate-smart farming practices.

---

## 🧠 Core Features

- 🌾 **Crop Recommendation** based on soil, climate, and user history (ML Decision Tree)
- 💧 **Smart Irrigation** control using soil moisture and weather forecasts
- ☁️ **Cloud-based Dashboard** to visualize farm data (Firebase/Supabase)
- 🔔 **Real-time Alerts** via SMS/email for critical thresholds
- 🌦️ **Weather Forecast Integration** to guide planting/harvesting
- 📱 **Multilingual Interface**: Supports English and Swahili for accessibility

---

## 🔧 Tech Stack

| Layer           | Technologies                              |
|----------------|--------------------------------------------|
| Hardware        | ESP32, DHT11, Soil Moisture Sensor, Relay |
| Backend         | Python, FastAPI, TensorFlow / Scikit-learn |
| ML Models       | Decision Trees, Time Series Forecasting   |
| Frontend        | React / Flutter (Mobile), Chart.js        |
| Database        | Firebase Realtime DB / Supabase Postgres  |
| Deployment      | Raspberry Pi, Google Cloud (optional)     |

---

## 📦 Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/SmartAgriAI.git
   cd SmartAgriAI
