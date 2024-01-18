# Geographic Information Functions (geo_functions)

## Description
This repo hosts some geographic information data acquisition and management functions I use in my work. Any question just message me or include an issue here.
Currently, I have the following functions under development:
- Overpass road download and clean (initially developed by Otavio Martins Peres and adapted by me)
- Raster clip to area of interest (AOI): just provide an AOI geopandas geodataframe and it will clip the raster to its extents and adjust the CRS to that of the AOI
- Vector clip to AOI: the same as the raster clip, above, but works with vector geodataframes.

## Getting started
Use the notebooks stored here at your own leisure and risk. I have tested them in my own python environment and provide no guarantee. 

## Installation
Within a particular ecosystem, there may be a common way of installing things, such as using Yarn, NuGet, or Homebrew. However, consider the possibility that whoever is reading your README is a novice and would like more guidance. Listing specific steps helps remove ambiguity and gets people to using your project as quickly as possible. If it only runs in a specific context like a particular programming language version or operating system or has dependencies that have to be installed manually, also add a Requirements subsection.

## Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
If you need help, write alexandre.santos[at]lmu.de

## License
This content is distributed under GNU 2.0.