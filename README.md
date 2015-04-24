# Indian Poly Files
This repo has border polygon files of all the [States and Union Territories(UTs) of India](https://en.wikipedia.org/wiki/States_and_union_territories_of_India)

These poly files can be used with [OpenStreetMap](osm.org) data processing tools like [Osmconvert](http://wiki.openstreetmap.org/wiki/Osmconvert), [Osmosis](http://wiki.openstreetmap.org/wiki/Osmosis), etc.,. to extract States and UTs OSM data from the [Indian OSM downloaded from Geofabrik](http://download.geofabrik.de/asia/india-latest.osm.pbf) or from [Planet OSM](http://planet.osm.org/).

For example, to clip Karnataka State from Indian OSM data -

```osmconvert india-latest.osm.pbf -B=karnataka.poly -o=karnataka.osm.pbf```
