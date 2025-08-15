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

<img width="1366" height="768" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/b1db656d-48e6-4887-973d-39b092db5c0c" />
<img width="1366" height="768" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/0894c98e-4ffb-40a7-86c6-b1cc49f597a6" />
<img width="1366" height="768" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/11639796-3591-4722-8a8d-99399cd33eb8" />
<img width="1366" height="768" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/fe2790d0-0acb-4afe-a3ed-0653ce98f6e3" />
<img width="1366" height="768" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/09223e84-30ab-4608-90cc-22680954b3a5" />


## 🔐 Security Notes

API keys are stored locally in config.js and never committed to GitHub.
Each user must supply their own API keys.

### 1️⃣ Clone this repository
```bash
git clone https://github.com/your-username/skycast-ai-weather-assistant.git
cd skycast-ai-weather-assistant

