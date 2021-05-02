---
title: RapidScat Level 1B Time-Ordered Geo-Located Sigma-0 Version 1.2
created: '2020-11-12T04:39:46.986708'
modified: '2020-11-12T04:39:46.986720'
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
This dataset contains the ISS-RapidScat Version 1.2 Level 1B geo-located Sigma-0 measurements and antenna pulse "egg" and "slice" geometries as derived from ephemeris and the Level 1A dataset. Version 1.2 is intended as a replacement and continuation of the Version 1.1 data forward from orbital revolution number 5127, corresponding to 19 August 2015; the overlapping time period starting on 19 August 2015 corresponds to the first time period of the recorded low signal-to-noise ratio (SNR). This Version 1.2 dataset differs from the previous Version 1.1 dataset as follows: 1) L1B sigma-0 has been re-calibrated during the periods of low signal-to-noise ratio (SNR) and 2) during low SNR periods the L1B sigma-0 calibration is determined using re-pointed L1B QuikSCAT data. The pulse "egg" represents the complete footprint of the pulse, which has a spatial geometry of approximately 25 km by 35 km. There are 8 slices that constitute the range-binned components of a pulse each of which has a spatial geometry of approximately 25 km by 7 km. The orientation of the long dimension of the slices varies with the rotation of the antenna and thus does not align with the along/across track orientation of the wind vector grid in the L2B/L2A products. Data are provided in single-orbit files in HDF-4 format. RapidScat is a Ku-band dual beam circular rotating scatterometer retaining much of the same hardware and functionality of QuikSCAT, with exception of the antenna sub-system and digital interface to the ISS Columbus module, which is where RapidScat is mounted. The NASA mission is officially referred to as ISS-RapidScat. Unlike QuikSCAT, ISS-RapidScat is not in sun-synchronous orbit, and flies at roughly half the altitude with a low inclination angle that restricts data coverage to the tropics and mid-latitude regions; the extent of latitudinal coverage stretches from approximately 61 degrees North to 61 degrees South. Furthermore, there is no consistent local time of day retrieval. Caution: this dataset is intended for expert use only. If you must use RapidScat Sigma-0 data but you are unsure about how to use the L1B data record, please consider using either of the following L2A datasets: 1) http://podaac.jpl.nasa.gov/dataset/RSCAT_L2A_12KM_V1.2 or 2) http://podaac.jpl.nasa.gov/dataset/RSCAT_L2A_25KM_V1.2. If you have any questions or concerns, please visit our Forum at https://podaac.jpl.nasa.gov/forum/.
