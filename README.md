# shallowML_supervised

Assessing the performance of a Gaussian Naive Bayes (NB) classifier and a Random Forest (RF) classifier for automated detection of Sargassum. In these notebooks, two models are trained and saved, then tested on new (unseen) data.

Training and testing data were sourced from Sentinel-2 MSI scenes acquired off Barbados. Data were atmospherically corrected (AC) using ACOLITE. For training, pixels for the two classes 'Water' (n = 220) and 'Sargassum' (n = 331) were manually selected for training in SNAP - ESA Sentinel Application Platform (V10).

Freely available data and processes used for this tutorial:
* Sentinel-2  MSI data -- https://dataspace.copernicus.eu
* ACOLITE processor -- https://github.com/acolite/acolite/releases/tag/20250114.0
