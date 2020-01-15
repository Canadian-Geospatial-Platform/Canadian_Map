# Canadian_Map
Boundary Canadian map  created in OpenStreetMap using leaflet, BS 4 and Jquery.

## Map Image Created using  OpenStreetMap and Leaflet js library.we can show any kind of Geospatial Information with leaflet just need to have that information in Geojson format.

![Image of Map](https://github.com/Canadian-Geospatial-Platform/Canadian_Map/blob/master/img/map.png)


 ## Leaflet GeoJson format.
 ##### for Canada boundary canada.js file on this repository /Data folder
 var CanData = {"type":"FeatureCollection","features":[
{"type":
"Feature","id":"CAN",
"properties":{"name":"Canada"},
"geometry":{"type":"MultiPolygon",
"coordinates":[[[[-63.6645,46.55001],[-62.9393,46.41587],[-62.01208,46.44314],[-62.50391,46.03339],[-62.87433,45.96818],[-64.1428,46.39265],[-64.39261,46.72747],[-64.01486,47.03601],[-63.6645,46.55001]]]..... continue with more data

###### for Provinces points and information e.js
var ProvData =   {
 "type": "FeatureCollection",
 "features": [
   {
     "type": "Feature",
     "id": "01",
     "properties": {
       "Name": "Alberta",
       "short": "AB",
       "rank": 4,
       "population": 4067175,
       "capital": "Edmonton",
       "Description": "Gimme espresso bars are found in New York City and Upstate New York."
     },
     "geometry": {
       "type": "Point",
       "coordinates": [-113.423,53.514]
     }
   },
   {
   
  ### Plugins 
  - leaflet-search
  - laeftlet-Icon.Glyp
  
 # More information about leaftlet.
 
* https://github.com/Leaflet/Leaflet/blob/master/docs/plugins.md
* https://docs.mapbox.com/mapbox.js/plugins/#leaflet-draw
* https://www.openstreetmap.org
* https://leafletjs.com/


