SWAT+ Input Data for TM_2024 Project

This folder contains all necessary input data for running the SWAT+ model in the context of the TM_2024 project (i.e. the master thesis of Etienne Delaloye). Below is an overview of the folder structure and the content within:
Folder Structure----------------------------------------------------------------------------------------------------------------------------------------------------------

    DEM/
    Contains the Digital Elevation Model (DEM) for the study area.
    File(s):
        DEM_Vuiss_reduced_prj.tif: Reduced DEM file in GeoTIFF format.

    Soils/
    Includes soil property data required for the SWAT+ model.
    File(s):
        Example: soils_map.tif (to be added).

    Landuse/
    Contains land-use/land-cover data for the study area.
    File(s):
        Example: landuse_map.tif (to be added).

    Weather/
    Includes weather data such as precipitation, temperature, and other climate variables.
    File(s):
        Example: weather_data.txt (to be added).

    Shapefiles/
    Vector-based data for boundaries, streams, and other geographical features.
    File(s):
        Example: boundary.shp (to be added).

    Observations/
    Contains observed data for calibration and validation purposes.
    File(s):
        Example: observed_discharge.txt (to be added).

    Results/
    Placeholder for results or output files from the SWAT+ model simulations.

Instructions for Users---------------------------------------------------------------------------------------------------------------------------------------------------

    Downloading Files:
    If you encounter large files (e.g., .tif), ensure you have Git LFS installed to handle large file storage and downloading. See Git LFS Installation Guide for details.
    ==> for the DEM for instance:
    Downloading Files: 
    If you encounter large files (e.g., .tif), ensure you have Git LFS installed to handle large file storage and downloading. See Git LFS Installation Guide for details.
    Guide: (1)Install Git LFS at https://git-lfs.com/
           (2) Once installed, users can clone the repository and download large files with the following commands (WITHIN COMMAND PROMPT FOR WINDOWS or git bash if familiar):

           
           ==> git lfs install
           ==> git clone https://github.com/Etidel98/TM_2024.git

           
    Using Data:--------------
    Each folder contains data pre-processed for SWAT+. Ensure that paths in SWAT+ are correctly linked to these files.
    For any issues with data compatibility, refer to the SWAT+ user manual.

    
    Contact:----------------
    For questions or issues, feel free to contact the repository maintainer.
    
    Using Data:-------------
        Each folder contains data pre-processed for SWAT+. Ensure that paths in SWAT+ are correctly linked to these files.
        For any issues with data compatibility, refer to the SWAT+ user manual.

    Contact:----------------
    For questions or issues, feel free to contact the repository maintainer.
