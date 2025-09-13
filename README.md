# 🌦️ Live Weather Nowcast + Forecast

A modern weather dashboard that fetches **real-time weather data** and applies statistical methods to generate **short-term forecasts** with visual insights.

![Preview Screenshot](screenshot.png) <!-- Add a screenshot of your app here -->

---

## 🚀 Features
- 🌍 **City selection or geolocation** support.
- ⏱️ Auto-refresh weather data (configurable 10s–300s).
- 📊 Real-time KPIs: temperature, humidity, wind, and trends.
- 📈 Interactive charts with:
  - Rolling Mean
  - Exponential Smoothing (configurable α)
  - Linear Regression Forecast + 95% Confidence Interval
- 🤖 Auto-generated insights comparing current vs. average values.
- 💾 Export options:
  - Save charts as **PNG**
  - Save report as **Markdown (.md)**
- ⌨️ Keyboard Shortcuts:
  - **R** → Refresh now
  - **P** → Save PNG
  - **M** → Save Markdown report

---

## 🛠️ Built With
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [TailwindCSS](https://tailwindcss.com/)
- [Chart.js](https://www.chartjs.org/)
- [Open-Meteo API](https://open-meteo.com/)

---

## 📂 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/live-weather-nowcast.git
   cd live-weather-nowcast
📸 Example Output

Temperature and forecast trends

Humidity & wind speed charts

Auto-insights (e.g., “Temperature is above the 24-hour average”)
