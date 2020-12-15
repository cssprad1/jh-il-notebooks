# IL Jupyter Example Notebooks

## Goal

The goal of these notebooks is to familiarize the user with Jupyter Hub and Notebooks. In addition, give examples of remote sensing/geospatial analysis work done with various tools on JupyterHub. 

| Notebok | Description |
| ----------- | ----------- |
| Demo-1-Intro-to-cuML-cuDF | Notebook highlighting use and development of GPU-based models on JupyerHub. Uses RAPIDS AI suite. |
| Demo-2-CPU-RF | A CPU-based version of Demo-1 notebook. |
| Demo-3-CPU-vs-GPU | Notebook similar to Demo-1, however this notebook compares timing and efficacy of CPU-based ML models (specifically RF Regressors) and GPU-based ML models. |
| Demo-4-cuML-Dask | Notebook which uses Dask to distribute parrallel ML model building and training. |

## Conda Environment Setup

These notebooks use a variety of Python modules. The easiest way to do it is to create a Conda environment based on the .yml file in this directory.

`conda env create -f environment_droplet.yml`


