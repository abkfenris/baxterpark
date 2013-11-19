GIS Data for Baxter State Park
===========

## Structure

* datasources - where the origional data comes from, except maybe slightly geoJSON-ified or slice of geoTIFF-ified.
* * nationalmap - from the USGS's [NationalMap](http://viewer.nationalmap.gov/viewer/) viewer.
* * TIGER - from the Census Bureau's [TIGER/Line](http://www.census.gov/geo/maps-data/data/tiger-line.html) data.
* calculated - where any data that is built off of the origional datasources go.
 
## Todo

* Recut the base DEM a bit larger as it ended up clipping just inside the park's North border.
* Make awesome
