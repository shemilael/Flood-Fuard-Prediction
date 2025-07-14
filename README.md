
# 🌊 FloodGuard — Early Flood Detection System

**FloodGuard** is a responsive, AI-assisted web dashboard that monitors real-time weather conditions and estimates flood risk levels across different regions. Built with **HTML5**, **Tailwind CSS**, **Font Awesome**, and **Chart.js**, this interactive system is designed for visualizing flood probability, risk severity, and environmental indicators using simulated or real data (e.g., from BMKG).

## 🚀 Features

- 🔔 **Live Flood Alerts**: Displays dynamic warning messages based on risk probability thresholds.
- 📊 **Interactive Dashboard**:
  - Flood risk gauge with color-coded levels (Low to Extreme).
  - Current weather stats: temperature, precipitation, wind speed, and humidity.
  - AI-powered flood prediction with probability and model confidence.
- 🗺️ **Flood Risk Map**:
  - Visual markers indicating geographic flood risk levels.
- 📈 **Rainfall Analysis Chart**:
  - Bar and line graphs comparing daily rainfall to flood thresholds.
- 📍 **High-Risk Area Table**:
  - Lists city names, rainfall, water levels, and alert indicators.
- ♻️ **Auto Refreshing**:
  - Real-time updates every 30 seconds or on user demand.

## 📦 Technologies Used

- **HTML5**
- **Tailwind CSS** (via CDN)
- **Chart.js** for dynamic rainfall visualization
- **Font Awesome** for rich iconography
- **JavaScript** (vanilla) for dynamic UI, simulated API data, and logic

## 📸 UI Preview

> _Insert a screenshot here if needed (e.g., `dashboard.png`)_

## 🛠️ How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shemilael/Flood-Guard-Prediction.git
   ```
2. **Open `index.html` in your browser**.
3. **Customize**:
   - Replace the static Google Maps `background-image` with a valid `API_KEY` or integrate with a live map service like Leaflet or Google Maps JavaScript API.
   - Replace simulated weather logic with real-time data from BMKG or OpenWeatherMap.

## 🔐 API Integration (Optional)

To enable real-world functionality:
- Integrate with [BMKG Weather API](https://data.bmkg.go.id) or any other real-time weather service.
- Replace the dummy values in `fetchWeatherData()` with actual API calls.

## 💡 Project Motivation

Floods are among the most destructive natural disasters in Southeast Asia. This project is a prototype aimed to help early response teams, governments, and citizens visualize potential flood zones and take preemptive action.

## 👤 Author

**Muntaqim Asbuch**  
📧 [shemilael@gmail.com](mailto:shemilael@gmail.com)  
🐦 [@shemilael](https://x.com/shemilael)  
💻 [GitHub Profile](https://github.com/shemilael)

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
