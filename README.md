# leaflet-challenge
repository for Module 15 Challenge
## Background
The purpose of this project is to visualize an earthquake data set. The data set is provided by the United States Geological Survey (USGS) who is a primary Federal source of science-based information on ecosystems, natural hazards, and the environment. They operate a global network of sensors that provides earthquake data in near real-time.
## Data Set
The USGS provides earthquake data in a number of different formats, updated periodically and can be found at the following URL: [https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). The data set used for this project is the "All Earthquakes from the Past 7 Days" data set.
## Visualizing the Data
The data set is visualized using Leaflet. The following features are included in the visualization:
* A map is created using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.
* Plot markers reflect the magnitude of the earthquake in their size. Earthquakes with higher magnitudes appear larger.
* The color of the marker is determined by the depth of the earthquake. A legend is included to provide context for the colors and their corresponding depth.
* Popups provide additional information about the earthquake when a marker is clicked.
* A second data set is pulled in to visualize the tectonic plates' location on the map.
## Attribution
* [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
* [Tectonic Plates GeoJSON](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
* [Leaflet.js](https://leafletjs.com/)
* [D3](https://d3js.org/)
* [USGS Topographic Map](https://usgs.gov/)
* [Black and White Map](http://stamen.com)
* [Stadia Maps Outdoors](https://stadiamaps.com/)
* [OpenStreetMap](https://www.openstreetmap.org/)