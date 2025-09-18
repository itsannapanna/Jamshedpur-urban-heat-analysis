# Jamshedpur-urban-heat-analysis
A geospatial data science project to identify and analyze urban heat islands in Jamshedpur using satellite imagery.

## Live Demo
**[View the Interactive Heat Risk Map Here](https://itsannapanna.github.io/output/Jamshedpur_Heat_Risk_Map.html)**


---

## Problem Statement

Urban areas can be significantly warmer than surrounding rural areas due to human activity and infrastructure. This project aims to answer:
* Which wards in Jamshedpur are most affected by the urban heat island effect?
* What is the relationship between temperature, green cover (NDVI), and population density at the ward level?
* Can we create a composite "Heat Risk Score" to identify the most vulnerable areas?

---

## Tech Stack & Data

* **Programming:** Python
* **Libraries:** Geopandas, Pandas, Rasterio, Scikit-learn, Folium
* **Data Sources:**
    * **Satellite Imagery:** Landsat 9 data via Google Earth Engine.
    * **Ward Boundaries:** Extracted from an ArcGIS Web Service.
    * **Census Data:** Scraped from the 2011 Census of India website.

---

## Key Findings

* A strong negative correlation was found between average temperature and vegetation index (NDVI) at the ward level.
* Wards with high population density and industrial zones showed significantly higher average temperatures.
* A "Heat Risk Score" was calculated, identifying **Sakchi** as one of the most at-risk areas.

!
<img width="1273" height="677" alt="Screenshot 2025-09-18 at 2 54 21 PM" src="https://github.com/user-attachments/assets/978b37ab-328a-462e-8b98-fc6fa6890abc" />



---

## ## How to Run

1.  Clone the repository: `git clone https://github.com/YOUR_USERNAME/jamshedpur-urban-heat-analysis.git`
2.  Install the dependencies: `pip install -r requirements.txt`
3.  Run the Jupyter Notebook: `notebooks/analysis.ipynb`
