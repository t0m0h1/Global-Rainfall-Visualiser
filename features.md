# Global Rainfall Visualiser – App Features

## Purpose

Visualise worldwide rainfall patterns over time to understand the effects of climate change, historical trends, and predictive scenarios.

---

## Core Features

1. **Interactive 2D World Map**

   * Zoom and pan across continents.
   * Rainfall visualised via heatmaps, gradient shading, or contour lines.
   * Optional overlays: country borders, rivers, population density, agricultural zones.

2. **Historical & Real-Time Data**

   * Import historical rainfall datasets (NASA, NOAA, ERA5 reanalysis).
   * Display monthly, seasonal, or yearly averages.
   * Optionally show current real-time precipitation.

3. **Climate Change Projections**

   * Visualise predicted rainfall under different warming scenarios (baseline, moderate, severe).
   * Show trends and potential anomalies like droughts or floods.

4. **Time Slider**

   * Animate rainfall changes over decades or centuries.
   * Compare past, present, and future rainfall patterns.

5. **Analytics & Insights**

   * Highlight regions with increasing or decreasing rainfall trends.
   * Simple statistics: e.g., “Rainfall in West Africa decreased by 15% over 30 years.”
   * Anomaly detection using ML models.

---

## Optional Advanced Features

1. **User Input Simulation**

   * Simulate “what if” scenarios: e.g., “What if global temperature rises by 2°C?”
   * See rainfall impact on specific regions in real time.
   * Compare scenarios to current trends.

2. **Download & Share**

   * Export rainfall maps, charts, or animations.
   * Share insights directly on social media or generate PDF reports.

3. **Mobile App Version**

   * Simplified interface with swipeable global map.
   * Time-lapse animations for historical and predicted rainfall.
   * Lightweight overlays for mobile-friendly visualization.

---

## Technical Stack

* **Frontend**: React.js or Vue.js, Leaflet.js or Mapbox GL JS, D3.js for visualisations.
* **Backend**: Python (Flask/FastAPI) or Node.js.
* **Database**: PostgreSQL + PostGIS for geospatial data.
* **Data Sources**: NASA GPM, ERA5, NOAA for historical; IPCC CMIP6 for predictive.
* **Machine Learning**: LSTM, Prophet, regression for predictive models; anomaly detection using unsupervised methods.
* **Deployment**: Cloud hosting (AWS, GCP, Azure), WebGL for map rendering, PWA support for mobile users.
