# netcdf_raster_layers_exporter
Using Geoserver and a configuration for it to support TIME dimension, yaml layer configuration,
it exports netcdf raster layers.

#INSTALLATION
- Install docker, docker-compose
- Run ```docker-compose up -d```
- Run
    1. ```sudo chown -R 1000 conf_dir``` 
    1. ```sudo chown -R 1000 data_dir``` 
    1. ```sudo chown -R 1000 extensions_dir``` 

After that geoserver will run on port 8080 locally.
Default created account: userName=`root`, password=`geoserver`
