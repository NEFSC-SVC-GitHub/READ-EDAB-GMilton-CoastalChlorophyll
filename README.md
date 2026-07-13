# Coastal North America In Situ Chlorophyll and Optical Dataset

## Description
This repository is used to store code and walkthrough (https://nefsc.github.io/READ-EDAB-GMilton-CoastalChlorophyll/intro.html) used for collecting and organizing in-situ North American coastal chlorophyll datasets for the Coastal Chlorophyll project paper (dataset: https://doi.org/10.5281/zenodo.20140178).

Satellites and other algorithms have a difficult time accuratly detecting chlorophyll in coastal regions due to optically complex waters. In situ data can be used as ground truth and to train models to better detect chlorophyll. This repository includes Python Spyder and Jupyter notebook codes for organizing chlorophyll, CDOM, and Rrs data from a wide range of publically available databases. Additionally, this repo holds the Jupyterbook descibing methods used for data accumulation. 

## Authors 
Gianna Milton, Kimberly Hyde, Ivona Cetinic, Maxwell Beal, Ryan Vandermeulen, Haley Synan

## Directory
Code folder holds code scripts for concatinating and organizing raw files into xlsx files, standardizing into single variable files, concatinatintion into final dataset, and code for satellite matchup.

- .py files are spyder codes for standardizing chlorophyll, CDOM, and Rrs data from unique sources
- .ipynb files are jupyter notebooks for final data concatination code, plots for data vizualization, and satellite matchup code
  
JupyterBook folder holds scripts to run the JupyterBook HTML files. 

## Abstract
Chlorophyll is a crucial climate variable and remotely sensed satellite chlorophyll estimates are essential to understanding large-scale biological processes. Current ocean color chlorophyll algorithms, however, are less accurate in optically complex inland and coastal waters. As a result, remote sensing algorithms are not able to fully resolve chlorophyll concentrations in optically complex coastal regions leading to greater uncertainty in regions of high productivity. This can further lead to errors in regional biogeochemical models and hinder fisheries and ecosystem monitoring and research. In order to develop more accurate coastal chlorophyll retrievals, in situ chlorophyll measurements are needed for algorithm calibration and validation. Here the methods used to develop a single cohesive standardized in situ chlorophyll, chromophoric dissolved organic matter (CDOM), and remote sensing reflectance (Rrs) dataset from multiple public data repositories are described. The final product is a North American dataset of quality controlled chlorophyll measurements and associated metadata. The dataset includes more than 700,000 chlorophyll values with coincidental CDOM and Rrs data when available. Methodological flags such as chlorophyll measurement method, triplicate samples, and in vitro/in vivo flags distinguish between data collection methods. The dataset includes regularly formatted metadata across all sources to ensure due credit to the programs collecting the samples. The resulting dataset is then matched to satellite chlorophyll data to examine the difference in chlorophyll retrievals across multiple water types and regions. This dataset is currently being used to validate a new coastal chlorophyll algorithm in development and to assess chlorophyll retrievals. All methods and data are publicly available.


### Legal Disclaimer
This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.
