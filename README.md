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
| `Dataset_WFI.csv` | Time-series dataset containing the extracted spectral information and vegetation indices. |
| `Metadata_v4.readme.txt` | Dataset metadata and documentation. |
| `Methodology.pdf` | Detailed description of the data processing workflow and methodology. |
| `Radiance_v3.rar` | WFI radiance images. |
| `TOA_reflectance_v4.zip` | Top-of-atmosphere (TOA) reflectance images. |
| `Script_Random_Forest.ipynb` | Example notebook for burned-area classification using Random Forest. |
| `Shapefile_spatial_grid.zip` | Spatial grid in ESRI Shapefile format. |
| `gpk_spatial_grid.gpkg` | Spatial grid in GeoPackage format. |

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

If you use this repository, the dataset, or the associated methodology in your research, please cite both the published dataset and the related article.

### Dataset

> de Oliveira, A. C., & Körting, T. S. (2025). *WFI Time-Series for Mapping Burned Areas in Chapada dos Veadeiros*. Science Data Bank. https://doi.org/10.57760/sciencedb.14040

### Article

```bibtex
@article{de2025multi,
  title={A multi-temporal dataset for mapping burned areas in the Brazilian Cerrado using time series of remote sensing imagery},
  author={de Oliveira, Alisson Cleiton and Sehn K{\"o}rting, Thales},
  journal={Big Earth Data},
  volume={9},
  number={3},
  pages={473--504},
  year={2025},
  publisher={Taylor \& Francis}
}
```
