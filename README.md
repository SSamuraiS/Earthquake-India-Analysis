# Earthquake India Analysis

Jupyter notebook exploring USGS earthquake data for India (1947-2025)—data loading, preview, and setup for trends/viz.

## Overview
- **Dataset**: CSV with columns like time, latitude, longitude, depth, mag, place (e.g., recent: 2025 event at 36°N).
- **Why?**: Builds insights for disaster risk—perfect for Bharat Digital public good projects.

## Sample Data Preview
| time              | latitude | longitude | depth | mag | place                  |
|-------------------|----------|-----------|-------|-----|------------------------|
| 2025-03-20...     | 36.x     | ...       | ...   | ... | 56 km ENE of [location] |

## How to Run
1. Clone: `git clone https://github.com/SSamuraiS/Earthquake-India-Analysis.git`
2. `pip install pandas numpy matplotlib seaborn jupyter`
3. Open `Earthquake_India_Analysis_Samaradhi.ipynb` in Jupyter/Colab (CSV loads local).
4. Run cells: See df.head() output instantly.

## Upgrades
- Add plots: e.g., `df.plot.scatter(x='longitude', y='latitude', c='mag')` for quake map.

#DataAnalysis #Geospatial #DigitalIndia 🚀
