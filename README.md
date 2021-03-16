# Temporal aggregation of satellite images in Google Earth Engine

Javascript example code to implement temporal aggregation of satellite images in Google Earth Engine.

Temporal aggregation of satellite images is a useful methodology to create land cover maps with geographical inconsistencies in satellite data availability, such as countries with frequent cloudy days. Here we show some example code to implement temporal aggregation of Landsat 8, Sentinel-1, and Sentinel-2 data, described in:

*Carrasco L., A.W. O'Neil, R.D. Morton, C.S. Rowland. 2019. Evaluating combinations of temporally aggregated Sentinel-1, Sentinel-2 and Landsat 8 for land cover mapping with Google Earth Engine. Remote Sensing 11: 288.*


This set of scripts allow to perform temporal aggregation of optical and radar images over a one-year period. The study area is Wales. Example scripts to perform land cover classification are also included.
However, classification training datasets are not accessible so please use another data set as training (e.g. global LC datasets).

*wales_temporalaggregation_XX* can be used to perform temporal aggregation of Landsat 8 (L8), Sentinel 2 (S2) and Sentinel 1 (S1) data.

*wales_S2_classification* uses temporal aggregation of S2 images and performs a land cover classification, including accuracy assessment.

*wales_class_LandandS2* uses a composite of temporally aggregated S2 and Landsat 8 data and performs a land cover classification, including accuracy assessment.

*wales_class_ndviandmore* uses a composite of temporally aggregated S2, L8 and multiple spectral indices, and performs a land cover classification, including accuracy assessment.
