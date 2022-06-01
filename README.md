# vt-test
Sample vector tile from the Natural Earth data set.  
Style.json is consumed by both Mapbox GL JS ver 1 and ArcGIS API.  

# Data source  
Original data comes from the Natural Earth. (Public domain data) 
https://www.naturalearthdata.com/   

# Vector tiles
## URL https://ubukawa.github.io/vt-test/ne-test/{z}/{x}/{y}.pbf  
## max zoom 5  
## min zoom 0
## layers  
landmass (from ne_110m_land.shp)  
bndl (from ne_110m_admin_0_boundary_lines_land.shp)  
popp (from ne_110m_populated_places.shp)  
coastl (from ne_110m_coastline.shp)    

# test style  
https://ubukawa.github.io/vt-test/maps/test-simple.json  

# test tile.json  
https://ubukawa.github.io/vt-test/maps/test-tile.json  

# test URL  
https://ubukawa.github.io/vt-test/maps/test-simple-mapbox.html  
https://ubukawa.github.io/vt-test/maps/test-simple-maplibre.html  
https://ubukawa.github.io/vt-test/maps/test-simple-arc.html  
  

# References  
https://api.tiles.mapbox.com/mapbox-gl-js/v1.7.0/mapbox-gl.js  
https://api.tiles.mapbox.com/mapbox-gl-js/v1.7.0/mapbox-gl.css  
https://ubukawa.github.io/style_test3/sprite_test/sprite_S  
https://ubukawa.github.io/style_test3/font/{fontstack}/{range}.pbf  

# Others  
Licensing of ArcGIS API for JavaScript
https://developers.arcgis.com/javascript/latest/guide/licensing/
