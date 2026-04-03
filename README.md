# 🌏 GeoPulse — Real-Time GIS Analytics Dashboard

GeoPulse is a SaaS-style Web GIS dashboard that integrates real-time geospatial data, analytics, and environmental insights into a single interactive platform.

Built using Leaflet, Chart.js, and multiple open APIs, this project simulates a modern geo-intelligence system with real-time data streaming and layered visualization.

 Features

Core GIS Capabilities

* Asia-focused earthquake visualization (real-time)
* Spatial filtering using bounding box logic
* Interactive Leaflet map with dynamic layers

Analytics Engine

* Live earthquake count & average magnitude
* Magnitude distribution chart (Chart.js)
* Real-time data refresh (simulated streaming)

Environmental Intelligence

* Click-based weather insights:

  * Temperature
  * Humidity
  * Rain probability

Rain Heatmap Layer

* Dynamic precipitation visualization
* Multi-point API sampling
* Toggleable heatmap overlay

Smart Search System

* Location search using geocoding API
* Automatic zoom & marker placement
* Approximate area calculation (km²)

Modern UI/UX

* Glassmorphism (purple theme)
* Responsive dashboard layout
* Clean SaaS-style interface

---

Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Mapping:** Leaflet.js
* **Charts:** Chart.js
* **Heatmaps:** Leaflet.heat

APIs Used

* Earthquake Data — USGS API
* Weather Data — Open-Meteo API
* Geocoding — Nominatim (OpenStreetMap)

## ⚙️ Setup Instructions

1. Clone the repository:

```
git clone https://github.com/yourusername/geo-pulse-gis-dashboard.git
```

2. Open the project folder

3. Run:

```
Open index.html in browser
```

No backend or installation required.

Future Enhancements

* Time-series playback (earthquake timeline)
* Backend integration (Node.js + PostgreSQL + PostGIS)
* Real-time streaming (Kafka / WebSockets)
* User authentication & saved dashboards
* Deployment (Vercel / Netlify)

Author

Syed Tuaha Wasti
GIS Engineer | Developer | Geo-Intelligence Enthusiast

---

## 📄 License

This project is licensed under the MIT License.
