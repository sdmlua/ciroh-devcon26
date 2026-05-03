# CIROH-DevCON-2016
In the United States, the National Oceanic and Atmospheric Administration-Office of Water Prediction (NOAA-OWP) utilizes the National Water Model (NWM) for operational hydrological forecasting. Its Flood Inundation Mapping (FIM) framework translates NWM discharge to inundation extent using the Height Above the Nearest Drainage (HAND) approach. The simplicity of the OWP HAND-FIM framework enables rapid, large-scale FIM predictions across the U.S., fostering a growing user and developer community beyond NOAA (Baruah et al.,2025). We have developed the OWP HAND-FIM ‘as a service’ (FIMserv), an open-source Python toolset for running the FIM generation procedures using NWM operational input data.By replicating Docker’s role in environment configuration in a simplified manner, this method bypasses containerization while maintaining a consistent and portable setup. The script dynamically adjusts to the local system’s structure, ensuring dependencies and file paths are properly aligned for successful execution (https://github.com/sdmlua/FIMserv). Currently we are hosting three different versions of OWP HAND rasters (v4.5,4.8 and 4.9) for CONUS. 

In this workshop, we will demonstrate-
Setting up and running FIMserv in one case study using Google Colab.
Visualization of the National Water Model streamflow for the specific event.
Generating the binary flood maps using the NWM streamflow.
Running the surrogate model and visualize the enhanced binary FIM.
  
 This repository contains all materials for FIMserv v1.1: A Tool for Streamlining Flood Inundation Mapping (FIM) Using U.S. Operational Hydrological Forecasts with Deep Learning Surrogacy, developed for the CIROH Developers Conference 2026 training track.
