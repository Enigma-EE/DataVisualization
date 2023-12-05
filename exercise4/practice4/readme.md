
## README

1. data: contains the data used for the project, downloaded from tie NOAA, NATIONAL OCEANIC AND ATMOSPHERIC ADMINISTRATION https://data.noaa.gov, file name: SEAFLUX-OSB-CDR_V02R00_FLUX_D19940104_C20160824.nc
2. data_cleaning: contains the scripts used to process the data, file name: data_pre_xarray.ipynb
3. data_for_html: contains the data used for the visualization, file name: output.json
4. base_map: contains the base map used for the visualization, file name: custom.geo.json
5. data_visualization: contains the html file for the visualization, file name: visualization.html

**to open and see the content of the html file**: 

1. download the html file
2. download the output.json file
3. download the custom.geo.json file
4. put the 3 files in the same folder
5. using python -m http.server to start a local server
6. open the browser and go to http://localhost:8000