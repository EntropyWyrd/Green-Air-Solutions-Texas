# Green-Air-Solutions-Texas web map

This repository contains html, .js & .css code using Leaflet framework to build an interactive GIS web map, where the data is static. 

## Purpose:
To share a web map with parcel data that shows the relative spatial distance from a proposed cement plant in the Rendon CDP in Texas, out to a five mile radius. 

## Development:
All map processing and development perfomed with the QGIS Desktop 3.28.10 application and used the qgis2web plug-in to transform and build the map with pre-set functions into the code necessary for publication (html, js & css).

## Data sources
  * [Tarrant County Appraisal District](https://www.tad.org/data-reports)
      * ParcelView (last updated 7/17/2023)- parcel polygons with appraisal information already joined in attribute table.
      * OD_City
      * OD_Schools
      * County
  * [Open Street Map](https://www.openstreetmap.org)
      * OSM Standard basemap
  * [ESRI Satellite](https://server.arcgisonline.com/ArcGIS/rest/services/World_Imagery/MapServer/)
      * OSM Standard basemap



