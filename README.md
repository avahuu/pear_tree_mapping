[🌳 Pear Tree Mapping](https://avahuu.github.io/pear_tree_mapping/)

An interactive map visualizing pear tree locations using R, sf, and leaflet.

This script:

Reads a GeoJSON file of pear tree data (peartrees.geojson)

Transforms it into an unprojected CRS (EPSG:4326) for web display

Generates dynamic popups showing each tree’s common name and height

Uses leaflet to plot triangle-shaped green markers sized by tree height
