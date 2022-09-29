# Mapping_Earthquakees

## Function and Purpose
This project main focus was to take data and use geoJson and Leaflet to produce a web map with multiple interactive layers. The subject matter was recent seismic activity in the last 7 days pulled through an api from the [USGS real-time feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). Also linked was the github repository [fraxen/tectonicplates](https://github.com/fraxen/tectonicplates/) for the tectonic plate map used as a layer. The challenge_logic.js file will pull up index page with 3 different mapbox maps that can be changed as well as three layers that can be toggled. The first layer is all earthquakes in the last 7 days, the second is all within the last 7 days with a magnitude of 4.5 or greater, and the last is the tectonic plates map. This map will update, when refreshed, to show any new data from the USGS real-time feed. 

## Improvements to be Made
Next steps for this would be adding an auto refresh to the script as well to add date and time to the popup tags. Other optional things that could be useful would be a way to highlight the most recent or the newest earthquakes to be added.
