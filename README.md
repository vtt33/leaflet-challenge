# Earthquake Data Visualization

This project visualizes earthquake data from the USGS Earthquake API using Leaflet.js and D3.js. It also overlays tectonic plate boundaries to analyze seismic activity patterns.

## Project Overview

- Plots earthquakes from the past week based on latitude & longitude.
- Marker size represents earthquake magnitude.
- Marker color represents earthquake depth.
- Popups provide details on each earthquake (magnitude, location, depth).
- Legend explains color coding for depth.
- Tectonic plates layer shows global fault lines.

## Technologies Used

- HTML, CSS, JavaScript
- Leaflet.js – Interactive map library
- D3.js – Data-driven visualization
- GeoJSON – Geospatial data format

## Data Sources

- Earthquake Data: USGS GeoJSON Feed (https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
- Tectonic Plates: GitHub Repository (https://github.com/fraxen/tectonicplates)

## How to Run the Project

### 1. Clone the Repository`

### 2. Open the `index.html` File
Simply open the `index.html` file in a web browser. The interactive map will load.

## Features

- Interactive map with earthquake markers
- Depth-based color coding (legend included)
- Magnitude-based marker size
- Dynamic popups with earthquake details
- Tectonic plate overlay
