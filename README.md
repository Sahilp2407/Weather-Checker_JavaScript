<h1 align="center">🌤️ Weather Checker Web App</h1>

<p align="center">
  A simple, fast, and reliable web app that gives real-time weather updates using the OpenWeatherMap API.
  <br/><br/>
  <img src="https://img.shields.io/badge/HTML-CSS-JS-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/API-OpenWeatherMap-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Responsive-Mobile%20Ready-lightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Stable-brightgreen?style=flat-square" />
  <br/><br/>
  <strong>🌦️ Type a city. Get weather instantly!</strong>
</p>

---

## 🚀 Live Demo

🌐 **Check out the app (Hosted version):** [Coming Soon]

---

## 📸 Flow Diagram

```mermaid
graph TD;
    A[🌇 User enters city name] --> B[Click on Get Weather button]
    B --> C[Fetch weather data from API]
    C --> D[Parse the API response]
    D --> E[Display weather data: temperature, condition, humidity, wind]
    C --> F[Show error message if city not found]
