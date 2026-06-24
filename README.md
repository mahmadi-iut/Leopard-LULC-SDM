###### Leopard-LULC-SDM ###### 

####### Description of details relevant to the data package #######

## Suggested citation for this dataset:

Tavakoli, M., Ahmadi, M., Malekian, M., Mohammadi, A., Ecological informatics for large carnivores conservation in Biosphere Reserves: linking LULC and SDM to Persian leopard habitat dynamics. Ecological Informatics. vol, nr (2026).


## Below, the content of the Zip file is described:

# "env_vars" folder:
raster lyers of digital evlevation (dem.tif) and distance to roads (road_dis.tif) used as covariates for LULC classification.

# "landsat_bands" folder:
landsat bands for 2002 and 2024 used for land use land cover (LULC) classification

# "SDM_layers" folder:
environmental variables for 2002 and 2024 used to generate habitat suitability of the Prsian leopard:

#- agri.tif: Focal function of cropland type in land use map in a 2.5×2.5 km grid
#- capra.tif: Habitat suitability map of wild goat
#- elevation.tif: elevation above sea level derived from Digital Elevation Model
#- forest.tif: Focal function of forest type in land use map in a 2.5×2.5 km grid
#- range.tif: Focal function of sparse vegetation in land use map in a 2.5×2.5 km grid
#- road.tif: Kernel density map of roads based on the OpenStreetMap dataset
#- settlement.tif: Focal function of residual areas in land use map in a 2.5×2.5 km grid
#- village_dns.tif: Kernel density map of villages 
#- VRM.tif: Vector Ruggedness Measure calculated using the DEM layer 

# LULC_classification.R 
R code designed to generate LULC maps for 2002 and 2024 based on Random Forest model

# points_2002.csv
Trainning points used to calssify LULC maps for 2002

# points_2024.csv
Trainning points used to calssify LULC maps for 2024

# prs_abs.csv
The geographic location of Persian leopard presence points + pseudo-absence points used for SDM analysis

# SDM_leopard.R
R code used to generate Persian leopard's habitat suitability for 2002 and 2024


################## Date 24.06.2026 ##################









