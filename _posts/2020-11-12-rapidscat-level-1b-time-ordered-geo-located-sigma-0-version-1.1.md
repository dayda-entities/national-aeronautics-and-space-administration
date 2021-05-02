---
title: RapidScat Level 1B Time-Ordered Geo-Located Sigma-0 Version 1.1
created: '2020-11-12T04:12:17.612097'
modified: '2020-11-12T04:12:17.612104'
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
This dataset contains the geo-located Sigma-0 measurements and antenna pulse  "egg" and "slice" geometries as derived from ephemeris and the Level 1A dataset. The pulse "egg" represents the complete footprint of the pulse, which has a spatial geometry of approximately 25 km by 35 km. There are 8 slices that constitute the range-binned components of a pulse each of which has a spatial geometry of approximately 25 km by 7 km. The orientation of the long dimension of the slices varies with the rotation of the antenna and thus does not align with the along/across track orientation of the wind vector grid in the L2B/L2A products. Data are provided in single-orbit files in HDF-4 format. RapidScat is a Ku-band dual beam circular rotating scatterometer retaining much of the same hardware and functionality of QuikSCAT, with exception of the antenna sub-system and digital interface to the International Space Station (ISS) Columbus module, which is where RapidScat is mounted. The NASA mission is officially referred to as ISS-RapidScat. Unlike QuikSCAT, ISS-RapidScat is not in sun-synchronous orbit, and flies at roughly half the altitude with a low inclination angle that restricts data coverage to the tropics and mid-latitude regions; the extent of latitudinal coverage stretches from approximately 61 degrees North to 61 degrees South. Furthermore, there is no consistent local time of day retrieval. Caution: this dataset is intended for expert use only. If you must use RapidScat Sigma-0 data but you are unsure about how to use the L1B data record, please consider using either of the following L2A datasets: 1) http://podaac.jpl.nasa.gov/dataset/RSCAT_L2A_12KM_V1.1 or 2) http://podaac.jpl.nasa.gov/dataset/RSCAT_L2A_25KM_V1.1.
