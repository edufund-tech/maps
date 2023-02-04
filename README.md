## **GeoJSON of Indonesia**

### **About**
This repo contains geojson of Indonesia's cities and provinces.

### **Reference**

The data source is from these repo with some adjustment in cities and provinces code:
<ul>
<li>Cities : https://github.com/okzapradhana/indonesia-city-geojson</li>
<li>Province : https://github.com/superpikar/indonesia-geojson</li>
</ul>

### **GeoJSON**
Here is `GeoJSON`'s definition from Internet Engineering Task Force(IETF):
> *GeoJSON is a geospatial data   interchange format based on JavaScript
   Object Notation (JSON).  It defines several types of JSON objects and
   the manner in which they are combined to represent data about
   geographic features, their properties, and their spatial extents.
   GeoJSON uses a geographic coordinate reference system, World Geodetic
   System 1984, and units of decimal degrees.*

Basically `GeoJSON` format is like:
```
{
  "type": "Feature",
  "geometry": {
    "type": "Point",
    "coordinates": [125.6, 10.1]
  },
  "properties": {
    "name": "Dinagat Islands"
  }
}

//source: geojson.org
```

