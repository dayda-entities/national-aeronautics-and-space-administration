---
title: RapidScat Level 2B Climate Ocean Wind Vectors in 12.5km Footprints Version 2.0
created: '2020-11-12T04:49:09.469127'
modified: '2020-11-12T04:49:09.469134'
state: active
type: dataset
tags:
  - Earth Science
  - Ocean Winds
  - Oceans
groups: []
csv_url: >-
  https://podaac-tools.jpl.nasa.gov/drive/files/allData/rapidscat/ancillary/revtime.csv
json_url: ''
published: 4

---
This dataset contains the RapidScat Level 2B 12.5km Version 2.0 Climate quality ocean surface wind vectors. The Level 2B wind vectors are binned on a 12.5 km Wind Vector Cell (WVC) grid and processed using the using the "full aperture" normalized radar cross-section (NRCS, a.k.a. Sigma-0) from the L1B dataset. RapidScat is a Ku-band dual beam circular rotating scatterometer retaining much of the same hardware and functionality of QuikSCAT, with exception of the antenna sub-system and digital interface to the International Space Station (ISS) Columbus module, which is where RapidScat is mounted. The NASA mission is officially referred to as ISS-RapidScat. Unlike QuikSCAT, ISS-RapidScat is not in sun-synchronous orbit, and flies at roughly half the altitude with a low inclination angle that restricts data coverage to the tropics and mid-latitude regions; the extent of latitudinal coverage stretches from approximately 61 degrees North to 61 degrees South. Furthermore, there is no consistent local time of day retrieval. The new version has two important improvements over the previous version 1.0. First, an SST-dependent GMF developed by Lucrezia Ricciardulli of Remote Sensing Systems is used in wind retrieval in order to fix persistent speed biases in Ku-band data over cold ocean.  Second, flagging is simplified and extra flags are provided. All the previously existing flags are still there and still reflect the same meaning and purpose. A new single bit wind_retrieval_likely_corrupted_flag specifies the approximately 3% of the data which is known to have suboptimal performance due to rain, ice, or a few other rare anomalous cases. Another bit wind_retrieval_possibly_corrupted_flag specifies the approximately 15% of the data near rain, near ice, or near the coast, that is thought to be high quality but may not match up well with numerical wind models due to either remaining rain/ice/land contamination or variability in the winds near ice, rain, and coasts that are not reflected in the NWPs.  In addition to these two new bits, copious quality information is provided in the data to allow users to tailor flags to meet their own needs. There is also an added a global attribute called rev_status that specifies whether the RapidScat Instrument was in the original (highest data quality) high SNR mode, or one of the four low SNR time periods, the latter of which indicates the accuracy of winds below 5 m/s is degraded. This attribute also serves to identify MARGINAL orbits in which there are large gaps in the data record due to suboptimal spacecraft attitude. Other than gaps in the data, the accuracy of the winds in the MARGINAL orbits are similar to other orbits. This dataset is provided in netCDF-4 format and made available via FTP and OPeNDAP. For data access, please click on the "Data Access" tab above.
