# seedzones-WA
Leaflet-pheongap code for android app displaying seed zones for state of WA

This app was written in leaflet/html/js and is wrapped using phonegap into an apk.  

Seed Zones are temperature and precip defined areas within which propagation materials (seeds etc) are 
adapted.  Using seed materials outside the zone in which they were collected could result 
in  unsuccessful establishment and a possible compromised restoration effort. 

This app was developed for field collectors to identify which seed zone they are in, and to provide a map
reference to locate the seed zone boundaries. Collecting often takes place in a areas where mobile data 
is not available so the app contains a limited local tile cache and seed zones as a local geojson.  The 
app is designed to switch to and from connected environments seamlessly - when in a connected environment
it will use map (OSM) and image (ESRI) sources via URL, when disconnected it will use the local
tile cache (OSM, zoom level 13) and imagery is not available. 
