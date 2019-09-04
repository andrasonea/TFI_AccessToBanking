# `TFI_AccessToBanking`

## Introduction

This repository contains links to data sources and the code used for the TFI "Access to Banking" report. 
Authors: Andra Sonea, Weisi Guo, Stephen Jarvis

### Requirements
The project was developed in Jan-July 2019.

We used `Python 3.6` and the following libraries:
* numpy
* pandas
* geopandas 0.4.1
* PySal 2.0
* Plotly Express
* matplotlib
* contextily
* json
* http.client
* gzip
* requests

We have also used 
* `QGIS 3.4 Madeira` (Distance Matrix)
* `Geoda 1.10.`(Moran I, LISA, K-means, OLS & Spatial Error Regressions)

## Data
The project involved extensive data collection over six months. 
* `List_DataSources.xlsx` in this repository - The links to all the files and APIs used. 
* The master file built on some of the data sources above is here:
* The structure of the master file is in the file `TFI Master File_Fields.xlsx`
* Sample data for the running the code: 

- If one is interested in methodology only, the scripts can be run with the sample files.
- If one is interesed in re-building the "master file", than a full extraction & joining of the data should be performed according to the scheme below:

<img src="" width="500">

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


