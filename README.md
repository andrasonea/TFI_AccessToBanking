# `TFI_AccessToBanking`

## Introduction

This repository contains links to data sources and the code used for the TFI "Access to Banking" report. 
Authors: Andra Sonea, Weisi Guo, Stephen Jarvis

### Requirements
The project was developed in Jan-July 2019.

We used `Python 3.6`. The complete python stack is in file `Stack_Python_GIS041.txt`
The most important libraries were:
* numpy
* pandas
* geopandas 0.4.1
* PySal 2.0
* Plotly Express
* matplotlib
* contextily
* json
* requests


We have also used 
* `QGIS 3.4 Madeira` (Distance Matrix)
* `Geoda 1.10.`(Moran I, LISA, K-means, OLS & Spatial Error Regressions)

## Data
The project involved extensive data collection over six months. 
* `List_DataSources.xlsx` - contains informaiton and links to all the files and APIs used.
* `TFI Master File_Fields.xlsx` - contains the structure of the "Master file" which was used for the analysis and which was built based on the data sources above.

* The master file built on some of the data sources above is here:

<img src="" width="500">

* If you want to re-build the file based on new data extractions, you might obtain slightly different distances as banking branches and ATMs are being closed in the meantime. The distances calculated in the Master file used for this project are based on March 2019 data extractions. For a full data extraction & joining of the data use the scheme below:

## Citing

[![DOI](https://zenodo.org/badge/...)](https://zenodo.org/...)

```bibtex
@software{Access_Banking,
  author = {{Andra Sonea}},
  title = {\texttt{TFI\_AccessToBanking}: Exploratory Spatial Analysis of Access to Physical and Digital Banking Channels},
  url = {https://github.com/andrasonea/TFI_AccessToBanking},
  version = {1.0},
  date = {2019-09-04},
}
```


