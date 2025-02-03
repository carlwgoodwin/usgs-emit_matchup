# USGS and EMIT Data Matchup

This project utilises AppEEARS to extract spectral data from the EMIT instrument aboard the International Space Station. This data is then matched spatially and temporally with the USGS water quality database to identify trends for temperature, chlorophyll and turbidity results. Spectral Angle Mapping, clustering and regression analysis are used as metrics. 


retreival_howto.ipynb: guide to find matching EMIT granules list for USGS data

usgs_appeears2.ipynb: create csv to upload into AppEEARS, fetch USGS data, site spectra graphs

data_analysis.ipynb: statistics, clustering, regression

SAM.ipynb: spectral angle mapper
