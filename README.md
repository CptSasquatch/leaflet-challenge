# leaflet-challenge
repository for Module 15 Challenge
## Background
The purpose of this project is to visualize an earthquake data set. The data set is provided by the United States Geological Survey (USGS). The USGS is a primary Federal source of science-based information on ecosystems, natural hazards, and the environment. The USGS collects, monitors, analyzes, and provides scientific understanding about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. The USGS Earthquake Hazards Program is part of the National Earthquake Hazards Reduction Program (NEHRP), established by Congress in 1977, and the USGS Advanced National Seismic System (ANSS) was established by Congress as a response to the World Trade Center and US Government attack on September 11, 2001. The USGS operates a global network of sensors that provides earthquake data in near real-time. The USGS earthquake data feeds into the National Earthquake Information Center (NEIC) at the USGS in Golden, Colorado. The NEIC determines the location and magnitude of earthquakes worldwide, disseminates earthquake information to the public, and works with other national and international agencies to provide timely and accurate information about earthquakes.
## Data Set
The USGS provides earthquake data in a number of different formats, updated every 5 minutes. The data set used for this project is a GeoJSON feed that contains all earthquakes from the last 7 days. The data set is updated every 5 minutes.
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
* [Leaflet](https://leafletjs.com/)
* [D3](https://d3js.org/)
* [USGS Topographic Map](https://usgs.gov/)
* [Black and White Map](http://stamen.com)
* [GIS Topo Map](https://leaflet-extras.github.io/leaflet-providers/preview/)
* [OpenStreetMap](https://www.openstreetmap.org/)
* [Leaflet.js](https://leafletjs.com/)
