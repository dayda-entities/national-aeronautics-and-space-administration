---
title: >-
  JPL GRACE and GRACE-FO Mascon Ocean, Ice, and Hydrology Equivalent Water
  Height JPL Release 06 Version 02
created: '2020-11-12T05:03:03.503781'
modified: '2020-12-04T07:13:54.022734'
state: active
type: dataset
tags:
  - Earth Science
  - Gravity Gravitational Field
  - Solid Earth
groups: []
csv_url: >-
  https://podaac-tools.jpl.nasa.gov/drive/files/allData/gracefo/docs/GRACE_GRACE-FO_Months_RL06.csv
json_url: ''
layout: post

---
This dataset contains gridded monthly global water storage/height anomalies relative to a time-mean, derived from GRACE and GRACE-FO and processed at JPL using the Mascon approach (Version2/RL06).  These data are provided in a single data file in netCDF format, and can be used for analysis for ocean, ice, and hydrology phenomena. The water storage/height anomalies are given in equivalent water thickness units (cm). The solution provided here is derived from solving for monthly gravity field variations in terms of geolocated spherical cap mass concentration functions, rather than global spherical harmonic coefficients. Additionally, realistic geophysical information is introduced during the solution inversion to intrinsically remove correlated error. Thus, these Mascon grids do not need to be destriped or smoothed, like traditional spherical harmonic gravity solutions. The complete Mascon solution consists of 4,551 relatively independent estimates of surface mass change that have been derived using an equal-area 3-degree grid of individual mascons. It should be noted that this dataset does not correct for leakage errors across coastlines; it is therefore recommended only for users who want to apply their own algorithm to separate between land and ocean mass very near coastlines. Please refer to the 'Data Access' tab at the top of this page to gain direct access to the Mascon data. For more information, please visit https://grace.jpl.nasa.gov/data/get-data/jpl_global_mascons/. For a detailed description on the Mascon solution, including the mathematical derivation, implementation of geophysical constraints, and solution validation, please see Watkins et al., 2015, doi: 10.1002/2014JB011547. This product is intended for expert use only; other users are encouraged to use the CRI-filtered Mascon dataset, which is available here: https://podaac.jpl.nasa.gov/dataset/TELLUS_GRACE_MASCON_CRI_GRID_RL06_V2.
