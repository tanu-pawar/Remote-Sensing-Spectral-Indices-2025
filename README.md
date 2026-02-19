**Spectral Indices Analysis Using Landsat 9 (2025)**

**Project Overview**

This project focuses on the calculation and visualization of five important spectral indices using Landsat 9 surface reflectance data:

NDVI (Normalized Difference Vegetation Index)

NDWI (Normalized Difference Water Index)

SAVI (Soil Adjusted Vegetation Index)

NDBI (Normalized Difference Built-up Index)

NDMI (Normalized Difference Moisture Index)

The analysis was performed using Google Earth Engine and Python in Google Colab.

**Objectives**

To assess vegetation health

To identify water bodies

To detect built-up areas

To analyze vegetation moisture conditions

To understand land cover distribution patterns

**Data Source**

Satellite: Landsat 9 OLI-2

Spatial Resolution: 30 meters

Year: 2025

Platform: Google Earth Engine

**Spectral Index Formulas**

NDVI = (NIR - Red) / (NIR + Red)

NDWI = (Green - NIR) / (Green + NIR)

SAVI = ((NIR - Red) / (NIR + Red + L)) × (1 + L)

NDBI = (SWIR - NIR) / (SWIR + NIR)

NDMI = (NIR - SWIR) / (NIR + SWIR)

**Outputs Generated**

GeoTIFF files for all indices

CSV file containing statistical values

PNG map outputs

Interactive HTML map

Map layouts with legend, scale bar, and north arrow

**Software & Tools Used**

Google Colab

Python

Google Earth Engine

Folium

QGIS (for layout design)

**Projection**

WGS 84 (EPSG: 4326)

**Author**

Your Name: Tanu Pawar
M.Sc. Geoinformatics
Programming for GIS II
Year: 2025–26
