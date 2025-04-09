# Earthquake Map Visualization

This project creates an interactive map displaying recent earthquake data. The map is built using Leaflet and D3, and it visualizes earthquake magnitude with the size of the markers and depth with marker color. A legend explains the depth color scale.

## Overview

- **Data Source:**  
  USGS All Week GeoJSON Feed: [https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson).

- **Technologies:**  
  - **Leaflet:** For map rendering and interactivity.  
  - **D3:** For fetching and parsing GeoJSON data.  
  - **JavaScript and HTML:** For the map and UI logic.

## Key Features

- **Basemap and Marker Layers:**  
  A base map is set up using OpenStreetMap tiles. Earthquake data is shown as circle markers whose sizes are scaled by magnitude and whose colors indicate depth.

- **Interactive Popups:**  
  Each marker displays popup information such as location, magnitude, depth, and time when clicked.

- **Dynamic Legend:**  
  A legend with color swatches for different depth intervals is displayed in the bottom-right corner. The inline style (added in JavaScript) ensures that each colored box appears to the left of its associated depth range.

## Assignment Summary

1. **Basemap and Layers:**  
   The map is initialized with a basemap, and earthquake data is added as a separate layer.

2. **Data Visualization:**  
   Earthquake data is fetched with D3, and each earthquake is visualized using a circle marker.  
   - **Marker Sizing:** Markers are scaled based on earthquake magnitude.  
   - **Marker Coloring:** Marker color is determined by the depth value via a custom function.

3. **Legend Implementation:**  
   A legend is created with inline styles in JavaScript to display color swatches corresponding to earthquake depth intervals.

This assignment demonstrates how to integrate real-time data into an interactive map and effectively use dynamic styling to convey additional data dimensions.
