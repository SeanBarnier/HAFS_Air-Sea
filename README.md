# Purpose
This repository contains code to visualize HAFS-A atmospheric and oceanic model output along the track of Hurricane Milton (2024), with a particular focus on ocean vertical structure and air-sea heat fluxes.  
# Background
Milton was the most powerful tropical cyclone to occur worldwide in 2024, and one of the most powerful on record in the Atlantic, reaching an estimated peak intensity of 80 m/s with a central pressure of 895 hPa. It underwent explosive rapid intensification on October 7, with its central pressure decreasing from 977 hPa to 895 hPa between 0325 UTC and 2000 UTC (NHC Tropical Cyclone Report). It travelled eastward across the Gulf, making landfall south of Tampa, FL as a Category 3 hurricane. Milton caused 15 direct fatalities and approximately $34.3 billion in damages, putting it in the top 10 costliest hurricanes on record for the U.S. as of 2024.

The Hurricane Analysis and Forecast System (HAFS) is the hurricane model application of the United Forecast System (UFS), and can be coupled to an ocean and wave model to improve predictions. It became operational in 2024 under two forms (A and B).
# How to Use
To use the code in this directory, first run getStormTrack.ipynb to download the NHC Best Track for Milton. Next, run getHAFSASlices.ipynb to download HAFS-A atmospheric and oceanic output. After this, any other notebook in the directory can be run. Though the code was written for Milton, it can be set for other TCs by changing the user parameters.
