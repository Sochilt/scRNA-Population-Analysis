# scRNA-Population-Analysis
The purpose of this analysis is to determine what populations are present, specifically in a microenvironment.
The code is based around Seurat with addtional computational analysis for deeper insights. File used for tertiary scRNA analysis is a filtered feature_bc_matrix.h5 file ('bc' stands for barcode). 
This file is a sparse matrix file of gene expression data of a subset of barcodes identified as corresponding to actual cells.
This is the file that stores gene expression counts based on UMIs (unique molecular identifiers).
```r
# Call in necessary libraries that provide pre-written, reusable functions and tools to do job.
library(dplyr)
library(Seurat)
library(patchwork)
library(rhdf5)
```
