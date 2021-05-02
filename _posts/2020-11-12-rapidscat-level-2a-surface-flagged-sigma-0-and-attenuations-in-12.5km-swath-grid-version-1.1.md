---
title: >-
  RapidScat Level 2A Surface Flagged Sigma-0 and Attenuations in 12.5Km Swath
  Grid Version 1.1
created: '2020-11-12T04:47:59.284574'
modified: '2020-11-12T04:47:59.284585'
state: active
type: dataset
tags:
  - Earth Science
  - Radar
  - Spectral Engineering
groups: []
csv_url: >-
  https://podaac-tools.jpl.nasa.gov/drive/files/allData/rapidscat/ancillary/revtime.csv
json_url: ''
published: 4

---
This dataset contains the ISS-RapidScat on Level 2A 12.5 km science data record, which provides surface-flagged sigma-0 in 12.5 km Wind Vector Cells processed using the pulse "slice" Sigma-0 data provided by the Level 1B dataset. Due to the circular scan of the RapidScat instrument the expected number of Sigma-0 cells per WVC is not constant. To minimize the L2A data volume, the Sigma-0 cell data are stored as "lists" for each WVC row, with each list indexed by a "cell_index" array to indicate the cross-track WVC membership of the data. Each cell is then checked for land or ice and flagged accordingly. Attenuation corrections for each Sigma-0 measurement are also provided. Data are provided in single-orbit files in HDF-4 format. RapidScat is a Ku-band dual beam circular rotating scatterometer retaining much of the same hardware and functionality of QuikSCAT, with exception of the antenna sub-system and digital interface to the International Space Station (ISS) Columbus module, which is where RapidScat is mounted. The NASA mission is officially referred to as ISS-RapidScat. Unlike QuikSCAT, ISS-RapidScat is not in sun-synchronous orbit, and flies at roughly half the altitude with a low inclination angle that restricts data coverage to the tropics and mid-latitude regions; the extent of latitudinal coverage stretches from approximately 61 degrees North to 61 degrees South. Furthermore, there is no consistent local time of day retrieval.
