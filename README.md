# PCA of py-GC-MS Datasets

## Overview

This repository contains code for pyrolysis-gas chromatography-mass spectrometry (py-GC-MS) data using Principal Component Analysis (PCA). This includes exporting figures in PNG and TIFF formats, alongside CSV files containing PCA scores and loadings.

## Repository Structure

| Paths | Description |
| ----- | ----------- |
| [`CSV/`](CSV/) | Directory containing exported PCA results, including scores and variance-scaled loadings in CSV format. |
| [`data/`](data/) | Exemplar biochar [py-GC-MS dataset](data/biochar-PCA-18112026.csv) used for PCA. |
| [`PNG/`](PNG/) | PCA plots and loadings exported in PNG format. |
| [`TIFF/`](TIFF/) | PCA plots and loadings exported in TIFF format. |
| [`biochar-pca.ipynb`](biochar-pca.ipynb) | Jupyter notebook with data preparation, PCA, score plots and loading visualisations. |
| [`environment.yml`](environment.yml) | Conda environment `pca-pygcms` specifying the Python version and dependencies required to run notebook. |

## Environment Usage

The project uses Conda to manage its Python environment and dependencies.

**Creating the environment:**

```bash
conda env create -f environment.yml
conda activate pca-pygcms
```