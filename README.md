# Global Earthquake Analysis Dashboard (1900–2014)

![Dashboard Preview](SCREENSHOT.png)
*A static preview of the dashboard. [Click here to view the interactive version on Tableau Public]((https://public.tableau.com/app/profile/sailesh.dahal/viz/Earthquakes1900-2013_17472010380270/Dashboard1)).*

## 📊 Project Overview
This Tableau project visualizes over a century of seismic activity data, analyzing patterns in earthquake magnitude, depth, and frequency across the globe. The dashboard provides a historical view of 8,308 recorded seismic events between March 1900 and March 2014.

## 💡 Key Insights & Findings

### 1. temporal Trends
* **Historical Increase:** The "Total Earthquakes by Year and Type" area chart reveals a significant increase in recorded seismic events starting in the mid-20th century, particularly escalating after 1960 and peaking around 2010. *Note: This trend likely correlates with advancements in seismic detection technology.*
**Event Frequency:** The dataset covers a total of 8,308 earthquakes over the 114-year period.

### 2. Magnitude & Depth Analysis
**Depth Distribution:** The "Depth in km histogram" shows that the vast majority of earthquakes are shallow, occurring at depths between 0–100 km.The average depth across all recorded events is **76.84 km**.
**Magnitude Frequency:** The magnitude histogram indicates a high frequency of earthquakes in the 6.0 to 7.0 magnitude range , with rarer, high-impact events reaching magnitudes of 9.0+.
**Correlation:** A scatter plot analyzes the "Relationship between depths and magnitude" to identify if deeper quakes correlate with higher or lower energy release.

### 3. Geospatial Distribution
**The Ring of Fire:** The map visualization clearly highlights major tectonic boundaries, with intense activity concentrated around the Pacific Rim, including Japan, Indonesia, and the Western Americas.
**Specific Events:** The dashboard details specific historical events, such as the 6.9 magnitude quake in Northwest Ryukyu Islands (1900) and activity in Santa Cruz Islands and Hokkaido.

## 📉 Key Metrics
**Total Recorded Events:** 8,308
**Average Depth:** 76.84 km 
**Average Gap:** 30.42 
**RMS (Root Mean Square):** 1.008

## 🛠️ Technical Details
* **Tool:** Tableau Desktop
* **File Type:** Tableau Packaged Workbook (`.twbx`)
* **Visualizations Used:**
    Geospatial Mapping (Mapbox integration).
    Area Charts for time-series analysis.
    Histograms for distribution analysis (Depth & Magnitude).
    Scatter Plots for variable correlation.

## 🚀 How to Run This Project
1.  Download the `Earthquake_Analysis.twbx` file from this repository.
2.  Open the file in **Tableau Desktop** or **Tableau Public**.
3.  Explore the interactive filters to isolate data by Year, Magnitude type (Mw, Ms, Mb), or Region.
