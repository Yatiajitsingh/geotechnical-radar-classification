# Automated Geotechnical Radar Classification Pipeline

## Overview
This project provides a machine learning pipeline that translates raw, unreadable satellite radar data into actionable geotechnical risk maps. Applied to the surface of Titan using Cassini mission data, this methodology demonstrates how autonomous classification can be used for large-scale remote site feasibility and structural risk assessment.

## Engineering & Strategic Value
* **Automated Site Feasibility:** Translates raw microwave reflections into a clear risk matrix (Safe Bedrock vs. Unstable Dunes).
* **Big Data Processing:** Engineered an out-of-core chunking pipeline to successfully process gigabytes of spatial data without memory failure.
* **Scalable Architecture:** The methodology can be directly adapted for Earth-based smart infrastructure applications, such as identifying stable ground for rapid modular construction or analyzing climate-adaptive urban landscapes.

## Tech Stack
* **Machine Learning:** Python, scikit-learn (Random Forest Classifier)
* **Spatial Engineering:** Rasterio, GeoPandas, NumPy
* **Visualization:** QGIS

---
### Final Classification Output
![Titan Map]((https://github.com/Yatiajitsingh/geotechnical-radar-classification/blob/main/Titan_Map.png))
