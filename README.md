# Mapping Earthquakes

The purpose of this project is to visually show the differences between the magnitudes of earthquakes around the world during the last seven days.
Additionally, a overlay is added that shows the tectonic plates and one more where the most intense earthquakes can be observed in the same period of time. 
Major Earthquakes are considered to be earthquakes with a magnitude of 5 or more.

The map es interactive and can shows three different styles:
* Streets
* Satellite
* Navigation Night

We used the Leaflet library to plot the data on a Mapbox map through an API request and created interactivity for the earthquake data.
Also, to retrieved the coordinates and magnitudes of the earthquakes from the GeoJSON data we used the JavaScript and the D3.js library.  
