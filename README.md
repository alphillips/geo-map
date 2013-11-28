geo-map
=======

Create an leaflet map with some layer just using HTML. An experiement with Web Components using Polymer.

e.g.

```
    <geo-map zoom="4" lat="-21.811" lon="157.023" >
      <geo-layer type="marker" lat="-10.262" lon="160.099">This is where I live</geo-layer>
      <geo-layer type="marker" lat="-16.262" lon="162.099">This is where my friend lives</geo-layer>
      <geo-layer type="wms" 
          src="http://www.ga.gov.au/gisimg/services/marine_coastal/Multibeam_50m_Bathymetry_2012_RGB/MapServer/WMSServer" name="0"
          format="image/png"/>
    </geo-map>
```

