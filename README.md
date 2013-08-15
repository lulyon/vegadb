VegaDB
========
VegaDB is an under developed storage engine for MySQL, currently version 5.5.28, not limited to one version, though.

Aiming to help store and query spatial data, the data file format is based on the shapefile format, which is a popular geospatial vector data format. 

The primarily intended storage engine supports shapefile import, SQL query, and table scan, all of which are read only. Any operation which requires write to the table, is not supported. 


