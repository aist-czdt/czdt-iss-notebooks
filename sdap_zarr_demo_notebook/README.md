# ISS SDAP Demo Notebook

This notebook provides a simple demonstration of SDAP's analysis (example: time series) and data retrieval (subsetting) capabilities
using Zarr data stored in AWS S3.

Provided for the notebook are 2 python modules:
- `processing.py` - Provides simple interfaces to the main SDAP APIs used in the notebook as well as processors for their outputs
- `plotting.py` - Provides plotting capabilities for SDAP outputs as provided by `processing.py`

## Requirements

- conda / mamba

## Running the Notebook

To run the notebooks, run the following commands that create a conda environment called `czdt_notebook` using the 
`environment.yml` file to include all required dependencies:

```shell
conda env create -f environment.yml
conda activate czdt_notebook

jupyter notebook
```
From the localhost page that opens (or click [here](http://localhost:8888/tree)), you can run the notebook. Simply double-click
on `sdap_zarr.ipynb`.
