# Geospatial Analysis of Nashville School Districts  

This project demonstrates geospatial analysis techniques applied to **Nashville school districts** using Python libraries such as **GeoPandas, Folium, and Matplotlib**. The analysis highlights how spatial data can provide insights into regional patterns, boundaries, and socioeconomic factors like unemployment.

## Project Overview  

The goal of this project is to explore and visualize geospatial data, working with shapefiles and GeoJSON data for **school districts, parks, and zip code boundaries** in Nashville. By combining demographic datasets with spatial boundaries, we are able to create meaningful visualizations such as choropleths and thematic maps.  

Key analyses include:  
- Visualizing Nashville school district boundaries.  
- Overlaying school districts with unemployment data to understand socioeconomic variation.  
- Integrating parks and zip code boundaries to add context to district-level analysis.  
- Creating interactive maps with **Folium** to explore the data dynamically.  

## Data Sources  

- **school_districts.geojson** – Defines geographic boundaries of Nashville’s school districts.  
- **parks_facilities.geojson** – Contains geospatial data about local park facilities.  
- **zip_code_boundaries_nashville.geojson / zipcodes.geojson** – Provides geographic boundaries for Nashville zip codes.  
- **unemployment.csv** – Socioeconomic dataset with unemployment rates by region.  

## Repository Structure  

- **environment.yaml** – Conda environment file with dependencies.  
- **geospatial_intro.ipynb** – Introduction to geospatial data, geopandas, folium maps.  
- **geospatial_vmisonh.ipynb** – Project notebook with Nashville school district analysis.  
- **school_districts.png** – Visualization of Nashville school districts.  
- **school_districts.geojson** – Boundary data for school districts.  
- **parks_facilities.geojson** – Park facilities data.  
- **zip_code_boundaries_nashville.geojson** – Nashville zip code boundaries.  
- **unemployment.csv** – Dataset with unemployment rates.  

## Skills Demonstrated  

- **Geospatial Data Handling**: Reading and processing shapefiles/GeoJSON.  
- **Visualization**: Thematic maps with GeoPandas, choropleths, and Folium interactivity.  
- **Spatial Joins**: Combining geospatial and demographic data.  
- **Exploratory Data Analysis (EDA)**: Understanding spatial relationships between school districts, parks, and socioeconomic indicators.  

## How to Use  

1. Clone this repository.  
2. Install dependencies using `environment.yaml`.  
3. Open the Jupyter notebooks and run the code to explore geospatial data.  
4. Modify datasets or add new layers for extended analysis.  

---  
This project showcases **real-world applications of geospatial analysis** in education and public policy contexts, demonstrating how data-driven mapping can inform decision-making.  
