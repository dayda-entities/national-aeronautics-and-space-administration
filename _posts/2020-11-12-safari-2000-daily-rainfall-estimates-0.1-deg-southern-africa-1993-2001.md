---
title: 'SAFARI 2000 Daily Rainfall Estimates, 0.1-Deg, Southern Africa, 1993-2001'
created: '2020-11-12T04:47:40.253714'
modified: '2020-11-12T04:47:40.253725'
state: active
type: dataset
tags:
  - Atmosphere
  - Earth Science
  - Infrared Wavelengths
  - Microwave
  - Precipitation
  - Spectral Engineering
groups: []
csv_url: >-
  https://daac.ornl.gov/daacdata/safari2k/climate_meteorology/daily_precip_est/comp/mira_data_dates.csv
json_url: ''
published: 4

---
The Microwave InfraRed Algorithm (MIRA) is used to produce an imagery data set of daily mean rain rates at 0.1 degree spatial resolution over southern Africa for the period 1993-2001. MIRA combines passive microwave (PMW) from the Special Sensor Microwave/Imager (SSM/I) on board the DMSP F10 and F14 satellites at a resolution of 0.5 degrees and infrared (IR) data from the Meteosat 4, 5, 6, and 7 satellites in 2-hour slots at a resolution of 5 km. This approach accounts for the limitations of both data types in estimating precipitation. Rainfall estimates are produced at the high spatial and temporal frequency of the IR data using rainfall information from the PMW data. An IR/rain rate relationship, variable in space and time, is derived from coincident observations of IR and PMW rain rate (accumulated over a calibration domain) using the probability matching method. The IR/rain rate relationship is then applied to IR imagery at full temporal resolution. The results presented here are the daily means of those derived rain rates at 0.1 degree spatial resolution.The rainfall data sets are flat binary images with no headers. They are compressed band sequential (bsq) files that contain all of the daily images for the given year. Each image is an array of 401 lines, each with 341 binary floating-point numbers, containing rainfall at 0.1 degree resolution for the area 10 to 50 degrees longitude and 0 to -34 degrees latitude. The number of band sequential images in each annual file and the associated dates can be found in the file MIRA_data_dates.csv.
