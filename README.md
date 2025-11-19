# Global Earthquake Analysis Dashboard (1900–2014)

![Dashboard Preview](SCREENSHOT.png)
*A static preview of the dashboard. [Click here to view the interactive version on Tableau Public]((https://public.tableau.com/app/profile/sailesh.dahal/viz/Earthquakes1900-2013_17472010380270/Dashboard1)).*

## 📊 Project Overview
This Tableau project visualizes over a century of seismic activity data, analyzing patterns in earthquake magnitude, depth, and frequency across the globe. [cite_start]The dashboard provides a historical view of 8,308 recorded seismic events [cite: 7] [cite_start]between March 1900 and March 2014[cite: 2, 4].

## 💡 Key Insights & Findings

### 1. temporal Trends
* [cite_start]**Historical Increase:** The "Total Earthquakes by Year and Type" area chart reveals a significant increase in recorded seismic events starting in the mid-20th century, particularly escalating after 1960 and peaking around 2010[cite: 54]. *Note: This trend likely correlates with advancements in seismic detection technology.*
* [cite_start]**Event Frequency:** The dataset covers a total of 8,308 earthquakes over the 114-year period[cite: 7].

### 2. Magnitude & Depth Analysis
* [cite_start]**Depth Distribution:** The "Depth in km histogram" shows that the vast majority of earthquakes are shallow, occurring at depths between 0–100 km[cite: 106, 122]. [cite_start]The average depth across all recorded events is **76.84 km**[cite: 15].
* [cite_start]**Magnitude Frequency:** The magnitude histogram indicates a high frequency of earthquakes in the 6.0 to 7.0 magnitude range [cite: 21, 33][cite_start], with rarer, high-impact events reaching magnitudes of 9.0+[cite: 48].
* [cite_start]**Correlation:** A scatter plot analyzes the "Relationship between depths and magnitude" to identify if deeper quakes correlate with higher or lower energy release[cite: 137].

### 3. Geospatial Distribution
* [cite_start]**The Ring of Fire:** The map visualization clearly highlights major tectonic boundaries, with intense activity concentrated around the Pacific Rim, including Japan, Indonesia, and the Western Americas[cite: 51].
* [cite_start]**Specific Events:** The dashboard details specific historical events, such as the 6.9 magnitude quake in Northwest Ryukyu Islands (1900) and activity in Santa Cruz Islands and Hokkaido[cite: 51].

## 📉 Key Metrics
* [cite_start]**Total Recorded Events:** 8,308 [cite: 7]
* [cite_start]**Average Depth:** 76.84 km [cite: 15]
* [cite_start]**Average Gap:** 30.42 [cite: 11]
* [cite_start]**RMS (Root Mean Square):** 1.008 [cite: 17]

## 🛠️ Technical Details
* **Tool:** Tableau Desktop
* **File Type:** Tableau Packaged Workbook (`.twbx`)
* **Visualizations Used:**
    * [cite_start]Geospatial Mapping (Mapbox integration)[cite: 138].
    * [cite_start]Area Charts for time-series analysis[cite: 54].
    * [cite_start]Histograms for distribution analysis (Depth & Magnitude)[cite: 21, 106].
    * [cite_start]Scatter Plots for variable correlation[cite: 137].

## 🚀 How to Run This Project
1.  Download the `Earthquake_Analysis.twbx` file from this repository.
2.  Open the file in **Tableau Desktop** or **Tableau Public**.
3.  Explore the interactive filters to isolate data by Year, Magnitude type (Mw, Ms, Mb), or Region.
