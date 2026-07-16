# Smart Weather Intelligence for Farmers

A React + Vite application that provides farm-focused weather monitoring, sensor dashboards, smart advisories, and climate risk analytics for farmers.

## 🚜 Project Overview

This project delivers a farmer-friendly dashboard for:
- real-time weather monitoring
- ESP32 sensor data visualization
- AI-based agricultural advisories
- climate risk and seasonal forecasting

It is built using modern frontend tools and focuses on helping farmers make informed decisions with weather and sensor intelligence.

## 🌐 Live Demo

https://smart-weather-monitoring-system-pearl.vercel.app/

## ✨ Key Features

- **Weather Dashboard**
  - temperature, humidity, wind, UV index, and precipitation insights
  - hourly and weekly charts
- **Smart Farming Advisories**
  - contextual recommendations for irrigation, pest control, harvesting, planting, and protection
  - Hindi / English advisory support
- **Sensors Monitoring**
  - ESP32 DHT11 environmental sensor integration
  - live sensor status, connection health, battery, and calibration controls
- **Climate Risk Analytics**
  - long-term seasonal risk trends
  - drought, flood, heatwave, pest outbreak, wind damage, and crop yield risk views

## 🧱 Tech Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- React Router DOM
- Recharts
- Framer Motion
- Lucide React

## 📁 Project Structure

- `src/App.tsx` — main router and layout
- `src/components/` — reusable UI components
- `src/pages/` — app screens like LandingPage, Dashboard, Advisories, ClimateRisk, Sensors
- `src/services/` — weather, sensor, and prediction service logic
- `src/data/` — mock data and weather data helpers
- `src/lib/` — utility helpers

## 🚀 Run Locally

```bash
npm install
npm run dev
