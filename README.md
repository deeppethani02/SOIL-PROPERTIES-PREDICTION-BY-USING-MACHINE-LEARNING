# SOIL-PROPERTIES-PREDICTION-BY-USING-MACHINE-LEARNING
This Project aims to map soil nutrients using Google Earth Engine data and advanced modeling techniques. By leveraging remote sensing data such as Normalized Difference Vegetation Index (NDVI), Digital Elevation Model (DEM), and Land Surface Temperature (LST), we employ the Scorpan model, supervised learning(linear regression) to predict soil nutrient values.

Methodology
The Scorpan model, adapted from Hans Jenny's framework, provides an empirical quantitative description of the relationships between soil and environmental factors. It is expressed as:

S = f(s,c,o,r,p,a,n) 
where,
- s = soil, other or previously measured properties of the soil at a point
- c = climate, climatic properties of the environment at a point
- o = organisms, including land cover and natural vegetation or fauna or human activity
- r = relief, topography, landscape attributes
- p = parent material, lithology
- a = age, the time factor
- n = spatial or geographic position

## Tools and Software
- Python Programming Language
- GIS Software:
- Erdas Imagine
- QGIS
- ArcMap
