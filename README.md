# GEE scripts (JavaScript) to performed temporal aggregation of satellite images

This set of scripts allow to perform temporal aggregation of optical and radar images over one year period. The study area is Wales. Example scripts to perform land cover classification are also included.
However, classification training datasets are not accessible so please use other data set as training (e.g. global LC datasets).

*wales_temporalaggregation_XX* can be used to perform temporal aggregation of Landsat 8 (L8), Sentinel 2 (S2) and Sentinel 1 (S1) data.

*wales_S2_classification* uses temporal aggregation of S2 images and performs a land cover classification, including accuracy assessment.

*wales_class_LandandS2* uses a composite of temporally aggregated S2 and Landsat 8 data and performs a land cover classification, including accuracy assessment.

*wales_class_ndviandmore* uses a composite of temporally aggregated S2, L8 and multiple spectral indices, and performs a land cover classification, including accuracy assessment.
