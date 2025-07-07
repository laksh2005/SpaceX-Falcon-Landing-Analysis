# 🛰️ SpaceX Falcon 9 Landing Analysis

Analyze SpaceX Falcon 9 missions using survival analysis, geospatial maps, and EDA to uncover factors behind successful landings.

## 🚀 Highlights
- Fetched real-time data via SpaceX public API
- Flattened nested JSON (e.g., cores, rockets, launchpads)
- **Rule-Based Landing Success Estimator** to predict landing success rate using mission parameters — implemented directly in the notebook
- Kaplan-Meier survival curve using `lifelines`
- Interactive launch site map with `folium`
- Visualized booster reuse, landing types, and flight experience

## 🛠️ Tech Stack
- Python, Pandas, Matplotlib, Seaborn
- Lifelines, Folium, Requests
- Jupyter Notebook

## 📊 Sample Visuals

### Kaplan-Meier Survival Curve
![Kaplan-Meier Curve](plots/kaplan-meier-curve.png)

### Launchpad Map
![Launch Map](plots/launch-map.png)

