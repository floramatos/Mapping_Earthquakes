# Mapping the Magnitude and the Location of Earthquakes over the World
Facilitating the visualization of earthquake data by using Leaflet.js to populate a geographical map with GeoJSON earthquake data.

## Overview
The main goal of this project was to facilitate the visualization of earthquake data. To achieve this goal, a html page containing a geographical map was built to show:
  - the different magnitudes and locations of earthquakes that took place in the last seven days;
  - the locations of the tectonic plates;
  - the locations of major earthquakes (magnitudes greater than 4.5).

Leaflet.js was used to populate the map with GeoJSON earthquake data.

## Results
To build the map shown below, data retrieved from the USGS website was used to get the geographical coordinates and the magnitudes of earthquakes for the last seven days as well as for the major earthquakes. Each earthquake is visually represented by a circle and color, where a higher magnitude corresponds to a circle with larger diameter and darker in color. In addition, each circle has a popup marker that, when clicked, shows the magnitude and the location of the earthquake.

![Screen Shot 2022-01-21 at 9 28 51 PM](https://user-images.githubusercontent.com/89421440/150626946-907f8f34-cddd-46b3-81ef-775698f364e1.png)

To map the tectonic plates locations, data was retrieved from the GeoJSON/PB2002_boundaries.json file.

## Summary
In sum, the html page built facilitates the visualization of earthquake data as it helps the user to quickly identify the occurrence of major and minor earthquakes along the tectonic plates.
