# 🌦 SkyCast AI – Real-time Weather & AI Chat Assistant

SkyCast AI is a modern, interactive web app that delivers real-time weather updates, forecasts, and insights.  
It combines the **OpenWeather API** for weather data with the **Google Gemini API** for an intelligent weather chat assistant.  

## ✨ Features
- 📍 **Live Weather** – Real-time temperature, humidity, wind speed, and more based on your location.
- 📅 **Forecast View** – Hourly and daily forecasts with graphical temperature trends.
- 🗺 **Interactive Maps** – Weather data displayed on maps using Leaflet.js.
- 💬 **AI Chat Assistant** – Ask questions like “What should I wear today?” and get AI-powered advice.
- 📊 **Weather Metrics Dashboard** – UV Index, Air Quality, Dew Point, Visibility, Cloud Cover, and more.
- 📱 **Responsive UI** – Works on desktop, tablet, and mobile devices.

---

## 🛠 Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript  
- **APIs:** [OpenWeather API](https://openweathermap.org/api), [Google Gemini API](https://ai.google.dev/)  
- **Libraries:** Chart.js (graphs), Leaflet.js (maps)  

---

## 🚀 Setup Instructions

### 1. Create config.js
Create a file named config.js in the project root:
// config.js
const OPENWEATHER_API_KEY = "your-openweather-api-key";
const GEMINI_API_KEY = "your-gemini-api-key";

⚠ Important:
Do NOT commit config.js to GitHub.
Add it to .gitignore so it remains private.

### 2. Run the App

Simply open index.html in your browser.
📂 Project Structure
.
├── index.html       # Main application
├── config.js        # API keys (excluded from GitHub)
├── download.jpeg    # Background image
├── README.md        # Documentation
└── .gitignore       # Ensures config.js is not uploaded

## 🖼 Screenshot

(Add your app screenshot here)

## 🔐 Security Notes

API keys are stored locally in config.js and never committed to GitHub.
Each user must supply their own API keys.

### 1️⃣ Clone this repository
```bash
git clone https://github.com/your-username/skycast-ai-weather-assistant.git
cd skycast-ai-weather-assistant

