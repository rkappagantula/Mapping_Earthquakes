# Mapping_Earthquakes

## Overview
This project consisted on supporting website and mobile application development by using the latest GeoJSON data on earthquakes around the World to come up with an interactive map visualization. The goal was to traverse these GeoJSON data files using JavaScript, D3, and Leaflet to then plot the data on a mapbox map to an API request. 

## Resources
- Datasets
  - Earthquakes [GeoJSON file](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
  - Tectonic Plates [GeoJSON file](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
  - Major Earthquakes [GeoJSON file](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)

- Software
  - JavaScript
  - D3, Leaflet and Mapbox
  - GeoJSON files
  - HTML
  - Visual Studio Code

## Results


As it can be seen, the final result was an interactive map displaying all the different earthquakes around the world. The circle-marker's size and color was correlated to the earthquake's magnitude. 
![image](https://user-images.githubusercontent.com/96051648/161673639-3dd656bd-215b-43c8-b391-a4fa39afae32.png)




Additionally, the map included a control legend where the user could choose from 3 different map styles (dark, satellite, and streets) and toggle (on and off) between all earthquakes, major earthquakes, and the tectonic plates.  

- Satellite view with tectonic plates and only major earthquakes being displayed (4.5 magnitude and above):

![image](https://user-images.githubusercontent.com/96051648/161673700-f26f6d8a-8441-4182-a183-e360fb87832d.png)

- Dark view with all earthquakes being displayed:

![image](https://user-images.githubusercontent.com/96051648/161673849-8f695bd4-b0e2-4231-957a-4d3a2cccf345.png)




