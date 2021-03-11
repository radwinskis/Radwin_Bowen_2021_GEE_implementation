# Radwin_Bowen_2021_GEE_implementation
Jupyter notebook Python scripts created by Mark Radwin for use with Earth Engine

Adapted after: Radwin MH, Bowen BB. Mapping mineralogy in evaporite basins through time using multispectral Landsat data: 
Examples from the Bonneville basin, Utah, USA. Earth Surf Process Landforms. 2021;1–17.https://doi.org/10.1002/esp.5089

To run script you must install Python, geemap (https://github.com/giswqs/geemap), and sign up for a Google Earth Engine (GEE) account. 

The script is designed such that you can pick start and end dates using sliders, then run the whole script ("run all cells") to download 
and view time series animations of Bonneville basin surface sediment distribution. Part of the script is to filter cloudy imagery, but the 
cloud identification algorithm (CFMask) has difficulty over the basin and performs very poorly. Thus, currently the timeseries will be 
polluted with some cloudy imagery.

This is an independent project by the first author of the referenced paper and is not a commercial product. 
Please email markradwin@gmail.com with any questions about the methodology. 

Feel free to adapt the code for your own purposes, however, the indices used here are designed and only validated for use over the Bonneville 
basin playa.
