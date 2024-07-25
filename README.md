# Geographic Information Functions (geo_functions)

## Description
This repo hosts some geographic information data acquisition and management functions I use in my work. Any question just message me or include an issue here.
Currently, I have the developed these scripts:
- 01_raster_clip_by_AOI - clips a raster to an area of interest
- 03_vector_clip_by_AOI - clips a vector to an area of interest
- 04_extract_raster_values - a simple reclassification on a raster
- 05_calculate_hillshade_slope - calculates the slope and hillshade from a DEM (e.g., [TanDEMX](https://download.geoservice.dlr.de/TDM30_EDEM/))
- 06_calculate_distance_raster - calculates the euclidian distance to rasterized linear feartures (e.g., OSM highways) on a raster
- 08_convert_raster_to_ASCII - converts rasters into arrays and saves them to ASCII format (under dev)
- 10_OSM_green_areas_import_by_AOI - fetches green area polygons from OpenStreetMap, filtering for certain categories and columns, and exporting to a shapefile.
- 10_OSM_metro_import_by_AOI - fetches urban rail lines (AKA metro, underground, or subway) from OSM, filtering for certain categories and columns, and exporting to a shapefile.
- 10_OSM_neighbourhoods_import_by_AOI - fetches neighbourhood polygons from OSM (the results are not that promising for Mumbai...), filtering for certain categories and columns, and exporting to a shapefile.
- 10_OSM_places_import_by_AOI - fetches places (i.e., placename points) from OSM, filtering for certain categories and columns, and exporting to a shapefile.
- 10_OSM_road_import_by_AOI - fetches roads from OSM, filtering for certain categories and columns, and exporting to a shapefile.
- 10_OSM_waterways_import_by_AOI - fetches rivers and waterways from OSM, filtering for certain categories and columns, and exporting to a shapefile.
- 27_GEE_get_global_HAND - uses Google Earth Engine (https://code.earthengine.google.com/) to fetch data from the Global HAND model by [Donchyts et al. 2023](https://www.researchgate.net/publication/301559649_Global_30m_Height_Above_the_Nearest_Drainage)
- 28_get_GHSL_pop_250m - uses GEE to fetch data from the Global Human Settlement Layer (GHSL)
- 29_GEE_generate_NDVI_from_sentinel - uses GEE to fetch Sentinel 2 Harmonised data and calculate a simple NDVI.

All scripts available in the [notebooks folder](https://github.com/alexandrepereiraarq/geo_functions/tree/main/notebooks)

## Getting started
Use the notebooks stored here at your own leisure and risk. I have tested them in my own python environment and provide no guarantee. 

## Installation
Download and use the notebooks in your own environment. Attention for dependencies.

## Usage
Most scripts can be run directly, using only an area of interest (AOI) polygon. I defined mine using adminstrative units (e.g., [GADM4](https://gadm.org/data.html)) and watersheds (e.g., [HydroSHEDS](https://www.hydrosheds.org/))
- For the OSM scripts no login is needed.
- For the GEE scripts, you will need to register at Earth Engine, setup a project, generate a token and provide it to the prompt when runing the script.
- For the raster and vector editing scripts, you need to prepare the rasters and shapefiles beforehand. The scripts automates only part of the process.

## Support
If you need help, write alexandre.santos[at]lmu.de

## License
This content is distributed under GNU 2.0.