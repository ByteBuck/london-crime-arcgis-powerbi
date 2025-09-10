# London Crime Analytics (ArcGIS + Power BI + Python)

An end-to-end geospatial analytics project for London crime:
- **ArcGIS Maps** heatmap (Power BI) for hotspots
- **24 months of crime trends by type (2023–2024)**
- **Dynamic KPIs + slicers for interactive filtering**
- **Python ETL + Forecast** (pandas, scikit-learn) projecting into 2025

## Screenshots

**Dashboard Overview**  
*Full Power BI report: ArcGIS hotspots, KPIs, trends by crime type, and a 12-month forecast.*  
![Dashboard Overview](screenshots/dashboard_plain.png)

**ArcGIS Hotspot Map (Zoomed)**  
*Interactive map of London crimes, filterable by month, with tooltip details per location.*  
![ArcGIS Zoom](screenshots/Heatmap.png)

**KPI + Charts Reacting to Slicer**  
*Three-month selection: KPIs, bar chart, and line chart dynamically update with filters.*  
![Slicer Reaction](screenshots/month_decrease.png)

**Forecast Projection (July 2025)**  
*Python-generated forecast imported into Power BI, projecting the trend into 2025.*  
![Forecast Projection](screenshots/forecast_crime.png)

## Data
- Source: UK Police (Metropolitan Police Service)  
- Period: Jan 2023 – Dec 2024 (actuals) + Jan–Dec 2025 (forecast)  
- Attribution:  
  - “Powered by TfL Open Data”  
  - “Contains OS data © Crown copyright and database rights 2016 and Geomni UK Map data © and database rights [2019]”  

## About
Power BI + ArcGIS dashboard of London crime hotspots with a Python ETL and 12-month forecast (UK Police open data).  

## AI / ML Components

- **Applied**:  
  - Built a Python forecasting pipeline using **scikit-learn regression** on 24 months of crime data to project crime counts into 2025.  
  - Integrated results into Power BI for visualisation alongside KPIs, slicers, and ArcGIS mapping.  

- **Planned Extensions**:  
  - **Enhanced forecasting** with RandomForest and seasonal/lag features to improve accuracy.  
  - **Anomaly detection** (z-score or Isolation Forest) to highlight unusual monthly crime spikes.  
  - **Geospatial clustering** (DBSCAN/KMeans) to detect persistent hotspots beyond raw heatmaps.  

These extensions would deepen the AI/ML application, turning the dashboard into a more predictive and diagnostic tool for decision-makers.

## Disclaimer
This project is **not fully finalized in terms of aesthetics or visual polish** to be team-ready. It is published here to **demonstrate technical capability with ArcGIS, Power BI, and Python forecasting** to recruiters.  

Due to **GitHub file size limits** (and not holding a premium account), the full `.pbix` and raw datasets are not uploaded. Instead, **screenshots** are provided as representative outputs.
