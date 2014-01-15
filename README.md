geo-map
=======

Create a leaflet map with some layers. An experiement with Web Components using Polymer.

e.g.

```HTML
<geo-map zoom="4" lat="-21.811" lon="157.023" >
  <geo-layer type="marker" lat="-10.262" lon="160.099">Mol Diamon (Cargo vessel)</geo-layer>
  <geo-layer type="marker" lat="-16.262" lon="162.099">NAN SHA NO.68 (Passenger ship)</geo-layer>
  <geo-layer type="wms" 
    src="http://www.ga.gov.au/gisimg/services/marine_coastal/Multibeam_50m_Bathymetry_2012_RGB/MapServer/WMSServer" name="0"
    format="image/png"/>
</geo-map>
```

Check out index.html to see how.

View [Demo](https://c9.io/alphillips/geo-map/workspace/index.html)
