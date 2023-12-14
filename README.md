# Visualizing Biodiversity Intactness Index (BII) and BII Change in Phoenix, Arizona

## About

This repository contains a notebook, `phoenix-BII.ipynb`, which visualizes the Biodiversity Intactness Index for Phoenix, Arizona, and conducts raster operations to find areas of BII change between 2017 and 2020.

## Visualizations

Outputs show the geographical context of Phoenix, Arizona and the BII change overlaid on the BII surface for 2020. Outputs are saved in the "images" folder.

## Highlights

- Retrieving data from the Microsoft Planetary Computer
- Working with data in the `xarray.DataArray` format using `rioxarray`
- Raster arithmetic and reclassification
- Plotting raster imagery

## Data

- Impact Observatory (2022), *Biodiversity Intactness* [Data file] Available from:
https://planetarycomputer.microsoft.com/dataset/io-biodiversity. Access date: December 13, 2023.

- US Census Bureau (2022), *2022 Tiger/Line Shapefiles:County Subdivisions* [Data file] Available from:
https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions. Access date: December 13, 2023
