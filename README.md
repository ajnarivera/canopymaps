# canopymaps
Mapping canopy cover for the central valley
***************************************************************************************
NOTE: This repository has two tracts: One generates census tract level data for c. 2016 whole California Central Valley
The other tract generates census block group level data for 2021 San Joaquin Valley


Files 00, 01 and 02 are Google earth engine scripts, a GEE account is needed to rerun them

File 03 accesses both the US Census API and Google Earth Engine, a Census API key and access to a Google Drive is required to run this script

File 04SJV uses the output of File 03 in GEE for visualization

For the CV tract there is a major current issue, I am unable to rename earthengine-CV-git.ipynb from github. Please use this as File 04 in Jupyter. This file can be used for analysis and the shapefile generated it can be used in File 05CV which will map
 the map output can be viewed on the app here without having run any of the previous scripts:
https://ee-ajnaram.projects.earthengine.app/view/cvcanopy

Much base code is modified from "Closing Urban Tree cover Inequity (CUTI) Script Repository" 
https://github.com/leahscampbell/CUTI-Scripts/tree/main Copyright (c) 2021 Leah Campbell
**************************************************************************************



