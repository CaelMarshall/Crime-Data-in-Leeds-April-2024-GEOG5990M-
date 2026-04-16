# Crime-Data-in-Leeds-April-2024-GEOG5990M-
## Project Overview
This project Investigates the spatial distribution of crime accross Leeds and its relationship with Socioeconomic deprivation. Using open source spatial datasets and Python based analysis, the study aims to identify crime hotspots and explore whether higher levels of deprivation are associated with increased crime rates. This work was cunducted as part of my Programming for Geographical Information Analysis Module. 

## Aims and Objectives
- To analyse spatial patterns of crime in Leeds
- Identify High Crime Areas/ Hotspots For crime
- Examine the relationship between crime and deprivation
- Demonstrate the application of spatial data science methods

  ## Data Sources
  Crime Data (April 2024)
  -source: UK poliece Open Data (https://data.police.uk/data/fetch/938ad624-dfcb-45b0-a09d-5e42253976de/)
  -Contains: crime type, longitude, latitude

  Index of Multiple Deprivation (IMD) 2025
  - Source: UK Gov (https://www.gov.uk/government/statistics/english-indices-of-deprivation-2025)
  - Contains: deprivation scores at LSOA level

    LSOA Boundries
    - Source: UK Geoportal (https://geoportal.statistics.gov.uk/datasets/68515293204e43ca8ab56fa13ae8a547_0/explore?location=52.837634%2C-2.489483%2C6)
    - Contains: Spatial Data for LSOAs
   
  ## Methodology
  The analysis followed a structured data science workflow:
  1. Data Loading and Cleaning
  2. Conversion of crime data into GeoDataFrame
  3. Coordinate Reference System (CRS) alignmnent
  4. Spatial Join of Crime points to LSOA Polygons
  5. Aggrigation of crime counts by LSOA
  6. Integration with IMD data
  7. Data Visualisation
     - choropleth map (Spatial)
     - Scatterplot (Non spatial)
    
  ## Outputs
  - A choropleth map showing crime distribution accross Leeds
  - A scatterplot showing the relationship between crime and deprovation
 
  ## Limitations
  - crime data only represents a single month (April 2024)
  - Possible underreporting of crime
  - Time frame inconsistency between crime and IMD datasets
