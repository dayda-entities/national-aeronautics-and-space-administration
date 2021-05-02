---
title: >-
  RapidScat Level 2A Surface Flagged Sigma-0 and Attenuations in 25Km Swath Grid
  Version 1.3
created: '2020-11-12T04:29:36.530705'
modified: '2020-11-12T04:29:36.530712'
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
This dataset contains the Version 1.3 ISS-RapidScat Level 2A 25km science data record, which provides surface-flagged sigma-0 in 25km Wind Vector Cells processed using the pulse "egg" Sigma-0 data provided by the Level 1B dataset. Version 1.3 is intended as a replacement and continuation of the Version 1.1 and 1.2 data forward from orbital revolution number 7873, corresponding to 11 February 2016; on 11 Feb 2016, RapidScat entered it's 3rd low signal to noise ratio (SNR) state and the initial calibration of low SNR 3 was preliminary during the Version 1.2 release. The fundamental difference between Version 1.3 and the previous Version 1.2 datasets is that the L1B sigma-0 has been re-calibrated during the periods of low SNR states 3 and 4 using re-pointed QuikSCAT data. Due to the circular scan of the SeaWinds instrument the expected number of Sigma-0 cells per WVC is not constant. To minimize the L2A data volume, the Sigma-0 cell data are stored as "lists" for each WVC row, with each list indexed by a "cell_index" array to indicate the cross-track WVC membership of the data. Each cell is then checked for land or ice and flagged accordingly. Attenuation corrections for each Sigma-0 measurement are also provided. Data are provided in single-orbit files in HDF-4 format. RapidScat is a Ku-band dual beam circular rotating scatterometer retaining much of the same hardware and functionality of QuikSCAT, with exception of the antenna sub-system and digital interface to the International Space Station (ISS) Columbus module, which is where RapidScat is mounted. The NASA mission is officially referred to as ISS-RapidScat. Unlike QuikSCAT, ISS-RapidScat is not in sun-synchronous orbit, and flies at roughly half the altitude with a low inclination angle that restricts data coverage to the tropics and mid-latitude regions; the extent of latitudinal coverage stretches from approximately 61 degrees North to 61 degrees South. Furthermore, there is no consistent local time of day retrieval. If you have any questions or concerns, please visit our Forum at https://podaac.jpl.nasa.gov/forum/.
