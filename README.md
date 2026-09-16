# ⛅ SkyNow — Weather App

A clean, responsive weather web application built with **Spring Boot** that provides real-time weather data, forecasts, and smart tips for any city worldwide

---

## Features

- 🔍 **City Search** — Get instant weather for any city around the world
- 📍 **My Location** — Detect and display weather based on your current location
- 🌡️ **Current Weather** — Temperature, feels like, humidity, wind speed, and pressure
- 🌅 **Sunrise & Sunset** — Daily sunrise and sunset times
- 📅 **5-Day Forecast** — Extended weather forecast
- 💡 **Tips & Suggestions** — Smart weather-based tips
- 📱 **Responsive Design** — Works on desktop and mobile

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Java 21, Spring Boot 3.5 |
| Frontend | HTML, CSS, JavaScript |
| Build Tool | Maven (mvnw) |
| Deployment | Render (Docker) |

---

## Getting Started

### Prerequisites

- Java 21+
- Maven

### Run Locally

```bash
# Clone the repository
git clone https://github.com/kishorenagarajan-git/skyNow-WeatherApp.git
cd skyNow-WeatherApp

# Build and run
./mvnw spring-boot:run
```

App runs at `http://localhost:8080`

---

## Project Structure

```
skyNow-WeatherApp/
├── src/
│   └── main/
│       ├── java/com/examplecom/weatherapp/weather_app/
│       │   ├── controller/
│       │   ├── service/
│       │   │   └── WeatherService.java
│       │   └── WeatherAppApplication.java
│       └── resources/
│           ├── static/
│           └── application.properties
├── Dockerfile
├── mvnw
├── pom.xml
└── render.yaml
```
---
