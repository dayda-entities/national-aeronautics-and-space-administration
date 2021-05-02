---
title: >-
  RapidScat Level 2A Surface Flagged Sigma-0 and Attenuations in 25Km Swath Grid
  Version 1.2
created: '2020-11-12T04:54:11.602164'
modified: '2020-11-12T04:54:11.602171'
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
This dataset contains the Version 1.2 ISS-RapidScat Level 2A 25km science data record, which provides surface-flagged sigma-0 in 25km Wind Vector Cells processed using the pulse "egg" Sigma-0 data provided by the Level 1B dataset. Version 1.2 is intended as a replacement and continuation of the Version 1.1 data forward from orbital revolution number 5127, corresponding to 19 August 2015; the overlapping time period starting on 19 August 2015 corresponds to the first time period of the recorded low signal-to-noise ratio (SNR). This Version 1.2 dataset differs from the previous Version 1.1 dataset as follows: 1) L1B sigma-0 has been re-calibrated during the periods of low signal-to-noise ratio (SNR) and 2) during low SNR periods the L1B sigma-0 calibration is determined using re-pointed L1B QuikSCAT data. Due to the circular scan of the SeaWinds instrument the expected number of Sigma-0 cells per WVC is not constant. To minimize the L2A data volume, the Sigma-0 cell data are stored as "lists" for each WVC row, with each list indexed by a "cell_index" array to indicate the cross-track WVC membership of the data. Each cell is then checked for land or ice and flagged accordingly. Attenuation corrections for each Sigma-0 measurement are also provided. Data are provided in single-orbit files in HDF-4 format. RapidScat is a Ku-band dual beam circular rotating scatterometer retaining much of the same hardware and functionality of QuikSCAT, with exception of the antenna sub-system and digital interface to the International Space Station (ISS) Columbus module, which is where RapidScat is mounted. The NASA mission is officially referred to as ISS-RapidScat. Unlike QuikSCAT, ISS-RapidScat is not in sun-synchronous orbit, and flies at roughly half the altitude with a low inclination angle that restricts data coverage to the tropics and mid-latitude regions; the extent of latitudinal coverage stretches from approximately 56 degrees North to 56 degrees South. Furthermore, there is no consistent local time of day retrieval. If you have any questions or concerns, please visit our Forum at https://podaac.jpl.nasa.gov/forum/.
