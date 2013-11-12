osm-static-maps
===============

This pretends to be inspired in Google(c) static map service. But made using open source technologies.

You can find osm-static-maps [running in heroku](http://osm-static-maps.herokuapp.com/ "Fabulous!")

Here you have a [demo](http://osm-static-maps.herokuapp.com/?geojson=[{"type":"Feature","properties":{"party":"Republican"},"geometry":{"type":"Polygon","coordinates":[[[-104.05,48.99],[-97.22,48.98],[-96.58,45.94],[-104.03,45.94],[-104.05,48.99]]]}},{"type":"Feature","properties":{"party":"Democrat"},"geometry":{"type":"Polygon","coordinates":[[[-109.05,41.00],[-102.06,40.99],[-102.03,36.99],[-109.04,36.99],[-109.05,41.00]]]}}]&height=300&width=300 "Just what I wanted!")

And a [dynamic version](http://osm-static-maps.herokuapp.com/dynamic?geojson=[{"type":"Feature","properties":{"party":"Republican"},"geometry":{"type":"Polygon","coordinates":[[[-104.05,48.99],[-97.22,48.98],[-96.58,45.94],[-104.03,45.94],[-104.05,48.99]]]}},{"type":"Feature","properties":{"party":"Democrat"},"geometry":{"type":"Polygon","coordinates":[[[-109.05,41.00],[-102.06,40.99],[-102.03,36.99],[-109.04,36.99],[-109.05,41.00]]]}}]&height=300&width=300 "Wow it gets even better!!") of the demo, for testing purposes.

As a first approach, the service can render a geoJSON in a map, returning a PNG and you can determine also an optional height and width in pixels.

Parameters can be passed to the app as GET (POST should be working also...)

| Parameter | Description |
| ---- | ---- | 
| geojson | geojson object to be rendered in the map | 
| height | height in pixels of the returned img | 
| width | height in pixels of the returned img | 
| more things | to be added soon! |

Credits
=======

Credits go to the outstanding, everlasting, fascinating opensource. Specially to

- OpenStreetMap
- Leaflet
- node-webshot
- ExpressJS
- Handlebars