# 🌦️ How the OpenWeather API Works

## 📌 What is OpenWeather API?
The OpenWeather API provides real-time and forecast weather data for any location worldwide. You can retrieve weather information using HTTP requests.

---

## 🔑 1. Getting an API Key
To use OpenWeather API, you need an API key. Follow these steps:
1. Go to [OpenWeather](https://openweathermap.org/api).
2. Sign up and create a free account.
3. Navigate to **API Keys** in your dashboard.
4. Copy your API key – you’ll need it to make requests.

---

## 🌍 2. API Endpoints & Usage

### 📌 Current Weather Data
**Endpoint:**  
```bash
https://api.openweathermap.org/data/2.5/weather?q=YOUR_CITY&appid=YOUR_API_KEY&units=metric
