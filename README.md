# London Crime Analytics (ArcGIS + Power BI + Python)

## Overview  
This project demonstrates how to transform a **large real-world dataset** into actionable insights using **Python, Power BI, and ArcGIS**.  
I built an **interactive dashboard** that identifies hotspots, tracks trends, and forecasts future patterns — the same techniques used in **finance, risk, and business analytics** for budgeting, demand planning, and anomaly detection.  

## Key Features  
- **Geospatial Analysis**: ArcGIS heatmaps in Power BI to highlight hotspots. In finance, similar methods apply to **branch performance, risk exposure, or regional sales**.  
- **Trend Tracking**: 24 months of time-series data broken down by category, transferable to **revenue or cost trend analysis**.  
- **Dynamic KPIs + Slicers**: Interactive filtering with KPIs and visuals updating in real time, mirroring **executive dashboards for financial decision-making**.  
- **Forecasting with Python**: Regression model (scikit-learn) projecting 2025 outcomes, directly applicable to **revenue forecasting and budget planning**.  

## Tools & Tech Stack  
- **Python**: pandas, scikit-learn (ETL + forecasting)  
- **Power BI**: dashboards, KPIs, ArcGIS integration  
- **ArcGIS**: geospatial visualisation  

## Applications Across Domains  
The techniques here apply beyond crime data:  
- **Anomaly detection** → fraud monitoring, cost overruns, system errors  
- **Forecasting demand** → revenue, inventory, staffing needs  
- **Regional trends** → branch profitability, marketing impact, resource allocation  

## Screenshots  

**Dashboard Overview**  
*ArcGIS hotspots, KPIs, and forecast integration.*  
![Dashboard Overview](screenshots/dashboard_plain.png)  

**ArcGIS Hotspot Map (Zoomed)**  
*Interactive map of London crimes, filterable by month, with tooltip details per location.*  
![ArcGIS Zoom](screenshots/Heatmap.png)  

**KPI + Charts Reacting to Slicer**  
*Three-month selection: KPIs, bar chart, and line chart dynamically update with filters.*  
![Slicer Reaction](screenshots/month_decrease.png)  

**Forecast Projection (July 2025)**  
*Python-generated forecast integrated into Power BI.*  
![Forecast Projection](screenshots/forecast_crime.png)  

## Planned Extensions  
- Seasonal forecasting models (ARIMA/Prophet)  
- Anomaly detection to highlight outliers in time-series  
- Clustering (KMeans/DBSCAN) to detect persistent hotspots  

## Note  
This dashboard is published as a **skills showcase**. It prioritises demonstrating technical capability in **Python ETL, Power BI, and ArcGIS integration** rather than polished aesthetics for executive delivery.  

Due to **GitHub file size limits**, the full `.pbix` and raw datasets are not uploaded. Instead, **screenshots** are provided as representative outputs.  
