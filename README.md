# Geographic Information Functions (geo_functions)

## Description
This repo hosts some geographic information data acquisition and management functions I use in my work. Any question just message me or include an issue here.
Currently, I have the following functions under development:
- [Raster clip to AOI](https://gitlab.lrz.de/0000000001364670/geo_functions/-/blob/main/src/data/01_raster_clip_by_AOI.ipynb?ref_type=heads): just provide an AOI geopandas geodataframe and it will clip the raster to its extents and adjust the CRS to that of the AOI
- [Vector clip to AOI](https://gitlab.lrz.de/0000000001364670/geo_functions/-/blob/main/src/data/02_vector_clip_by_AOI.ipynb?ref_type=heads): the same as the raster clip, above, but works with vector geodataframes.
- [Overpass road download and clean](https://gitlab.lrz.de/0000000001364670/geo_functions/-/blob/main/src/data/03_road_import_by_AOI.ipynb)
- [Extract raster values](https://gitlab.lrz.de/0000000001364670/geo_functions/-/blob/main/src/data/04_extract_raster_values.ipynb): takes a list of values to extract from a raster.
- [Calculate hillshare and slope](https://gitlab.lrz.de/0000000001364670/geo_functions/-/blob/main/src/data/05_calculate_hillshade_slope.ipynb?ref_type=heads): receives a raster and calculates hillshade and slope.

## Getting started
Use the notebooks stored here at your own leisure and risk. I have tested them in my own python environment and provide no guarantee. 

## Installation
Download and use the notebooks in your own environment. Attention for dependencies.

## Usage
To be included.

## Support
If you need help, write alexandre.santos[at]lmu.de

## License
This content is distributed under GNU 2.0.