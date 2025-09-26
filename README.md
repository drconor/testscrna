# Single Cell Analysis with Seurat 

This repository serves as the starting point for creating a GitHub-integrated Capsule for preprocessing and exploratory analysis of single cell data from four human innate T cells.  

### Runtime environment

Choose the **Python and R (Jupyterlab/RStudio) (3.10.12, R 4.2.3, JupyterLab 3.6.2, RStudio 2022.07.0-548)** starter environment and add the following packages to the appropriate package manager:

**mamba**

r-irkernel=1.3.2

r-presto=1.0.0

r-rcpp=1.0.11

r-seurat=5.1.0

**R (CRAN)**

BiocManager=1.30.25

markdown=2.0

**Bioconductor**

BiocVersion=3.16.0

limma=3.54.2

### Required Data

Running this Rmd requires a data asset which can be created from the following S3 storage:

**S3 bucket:** codeocean-public-data

**Path:** example_datasets/innate_Tcell_transcriptome/

**Data Asset Metadata**

**Title:** Innate T Cell RNA-Seq Counts

**Folder name:** counts

**Description:** Low input RNA-seq and single-cell RNA-seq data from four human innate T cell. Initially retrieved from NCBI: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE124731


*Note: do **not** import this repository directly. Instead, create a new repo from this template.*

Notebook based on the original [Scanpy Tutorial](https://scanpy-tutorials.readthedocs.io/en/latest/pbmc3k.html). 
