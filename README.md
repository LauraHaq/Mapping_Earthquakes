# Mapping_Earthquakes

## Overview
As a Data Visualization Speicialist this project is to to build a user-friendly website of JSON data pulled from the U.S. Geological data source. The website it to load all earthquakes in the last seven days and techtonic plate fault lines. The marker sizes are to be related to magnitude sizes displayed in an added legend. An interactive input box is to provide at least three different map styles and give the user the option to turn earthquake markers and techtonic plate lines off and on.

### Tools
- Visual Studio Code
- JavaScript
- D3 Library
- Leaflet Library
- Mapbox Maps
- API Requests

## Results
- Webpage when loaded:
![loaded](https://github.com/LauraHaq/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/initial_webpage.png)

  - data source:
[techtonic boundary lines](https://github.com/fraxen/tectonicplates/blob/master/GeoJSON/PB2002_boundaries.json)
  - code using geoJSON() to pull data to my website:
![VS](https://github.com/LauraHaq/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/getJSONplates.png)

- Input box opened and "Major Earthquakes" chosen:
![majorEarthquakes](https://github.com/LauraHaq/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/major_earthquakes.png)

  - data source:
[major earthquakes data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)
  - code using functions to diplay requested layer:
 
    ![vs2](https://github.com/LauraHaq/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/getfunctions.png)

- Additional map layers added:
![darkoption](https://github.com/LauraHaq/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/dark_layer.png)
  
  - code to add layer options:
  
 ![layers](https://github.com/LauraHaq/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/images/layers.png)
 

## Summary
The website loads with current earthquake data displayed and user-friendly point-and-click input box to filter to user needs. The code can be easily edited to add addtional layers such as I did when adding "Major Earthquakes" as well as additional map styles such as I added "Dark" and "Outdoors". With addtional data sources of relateable content of other natural disasters could be added as well making the website even more useful.
