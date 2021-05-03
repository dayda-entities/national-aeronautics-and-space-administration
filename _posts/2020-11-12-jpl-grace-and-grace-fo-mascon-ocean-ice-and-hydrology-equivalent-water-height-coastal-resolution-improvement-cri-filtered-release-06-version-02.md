---
title: >-
  JPL GRACE and GRACE-FO Mascon Ocean, Ice, and Hydrology Equivalent Water
  Height Coastal Resolution Improvement (CRI) Filtered Release 06 Version 02
created: '2020-11-12T04:52:33.839827'
modified: '2020-12-04T07:09:54.067594'
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
published: 4

---
This dataset contains gridded monthly global water storage/height anomalies relative to a time-mean, derived from GRACE and GRACE-FO and processed at JPL using the Mascon approach (Version2/RL06). These data are provided in a single data file in netCDF format, and can be used for analysis for ocean, ice, and hydrology phenomena. This version of the data employs a Coastal Resolution Improvement (CRI) filter that reduces signal leakage errors across coastlines. The water storage/height anomalies are given in equivalent water thickness units (cm). The solution provided here is derived from solving for monthly gravity field variations in terms of geolocated spherical cap mass concentration functions, rather than global spherical harmonic coefficients. Additionally, realistic geophysical information is introduced during the solution inversion to intrinsically remove correlated error. Thus, these Mascon grids do not need to be destriped or smoothed, like traditional spherical harmonic gravity solutions. The complete Mascon solution consists of 4,551 relatively independent estimates of surface mass change that have been derived using an equal-area 3-degree grid of individual mascons. A subset of these individual mascons span coastlines, and contain mixed land and ocean mass change signals.  In a post-processing step, the CRI filter is applied to those mixed land/ocean Mascons to separate land and ocean mass. The land mask used to perform this separation is provided in the same directory as this dataset. Since the individual mascons act as an inherent smoother on the gravity field, a set of optional gain factors (for continental hydrology applications) that can be applied to the solution to study mass change signals at sub-mascon resolution is also provided within the same data directory as the Mascon data. Please refer to the 'Data Access' tab at the top of this page to gain direct access to the Mascon data. For more information, please visit https://grace.jpl.nasa.gov/data/get-data/jpl_global_mascons/. For a detailed description on the Mascon solution, including the mathematical derivation, implementation of geophysical constraints, and solution validation, please see Watkins et al., 2015, doi: 10.1002/2014JB011547.  For a detailed description of the CRI filter implementation, please see Wiese et al., 2016, doi:10.1002/2016WR019344.
