# WFI data for mapping burned areas in the Chapada dos Veadeiros National Park, Brazil

[![DOI](https://img.shields.io/badge/DOI-10.57760/sciencedb.14040-blue)](https://doi.org/10.57760/sciencedb.14040)
[![CSTR](https://img.shields.io/badge/CSTR-31253.11.sciencedb.14040-blue)](https://cstr.cn/31253.11.sciencedb.14040)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Description

This repository contains the source code developed to preprocess, analyze, and classify **WFI (Wide-Field Imager) satellite time-series** from the CBERS-4, CBERS-4A, and AMAZONIA-1 missions. The scripts are associated with the published dataset used for burned area mapping in the **Chapada dos Veadeiros National Park** (Goiás, Brazil).

The complete dataset is publicly available through the **Science Data Bank** and includes observations for the years **2020, 2021, and 2022**.

## Published Dataset

The dataset contains spectral information from the blue, green, red, and near-infrared bands, as well as the following vegetation indices:

- **BAI** (Burned Area Index)
- **EVI** (Enhanced Vegetation Index)
- **GEMI** (Global Environmental Monitoring Index)
- **NDVI** (Normalized Difference Vegetation Index)
- **NDWI** (Normalized Difference Water Index)

The published dataset includes:

| File | Description |
|------|-------------|
| `Spatial_grid.shp` | Spatial grid in Shapefile format |
| `Spatial_grid.gpkg` | Spatial grid in GeoPackage format |
| `spectral_data.csv` | Spectral dataset |
| `metadata.readme` | Dataset metadata |
| `Methodology.pdf` | Methodology documentation |
| `RF_classification.ipynb` | Random Forest classification example |
| `radiance_bands.rar` | WFI radiance images |
| `TOA_reflectance.zip` | Top-of-atmosphere reflectance images |
| `BOA_reflectance.zip` | Bottom-of-atmosphere reflectance images |

The dataset can be accessed at:

**Science Data Bank:** https://www.scidb.cn/en/detail?dataSetId=f86ea1da97a5465e96d258830a526963

## Repository

This repository provides code related to the published dataset, including data preprocessing, time-series analysis, feature engineering, machine learning experiments, and other reproducible workflows.

Additional scripts and documentation will be added as the repository evolves.

## Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- rasterio
- geopandas
- matplotlib

## Citation

If you use this repository or the associated dataset in your research, please cite the published dataset:

> WFI Time-Series for Mapping Burned Areas in Chapada dos Veadeiros. Science Data Bank. DOI: 10.57760/sciencedb.14040
