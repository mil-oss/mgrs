# Military Grid Reference System
A collection of Military Grid Reference System (MGRS) data

Most of this data came from the National Geospatial Intelligence Agency
http://earth-info.nga.mil/GandG/coordsys/grids/universal_grid_system.html#zzd1


# What's here?

The current MGRS grid zones are currently distributed from NGA as ESRI Sharp Files. This repo has the same files represented as KML as converted by GDAL

# How were they converted?
ogr2ogr -f "KML" OUTPUT.kml INPUT.shp
