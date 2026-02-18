# SALAMI

This repository contains Python scripts for interacting with the SALAMI dataset, for obtaining Level 1 SDO/AIA data, and for cross-referencing the occurrences of solar flares with geomagnetic storms. For more details on the SALAMI dataset, please refer to the following paper:

"Storm Archive for Learning and Anticipation with Machine Intelligence (SALAMI): A Machine Learning-Ready Dataset for Space Weather Prediction"

The scripts contained in this repository are as follows:
* salami_overview.py - displays general information for the SALAMI dataset
* inspect_sample.py - for inspecting/displaying data for a given interval in the dataset
* get_aia.py - for downloading high-resolution SDO/AIA data between two dates
* find_flares.py - for querying the [NASA CCMC Donki](https://kauai.ccmc.gsfc.nasa.gov/DONKI/) database for the presence of flares in a particular interval in the dataset
* salami_transfer.py - for obtaining a local copy of the entire dataset

