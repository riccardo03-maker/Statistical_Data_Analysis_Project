# Synthetic haplotypes and linkage disequilibrium
### Exam project for the Statistical Data Analysis for Applied Physics course, Master degree in Physics, University of Bologna


## Overview

This repository contains a statistical analysis of all the variants observed in three genes (HLA-DRB1, TP53 and ABO) in the human DNA. Datasets are taken from the [gnomAD database](https://gnomad.broadinstitute.org/). The aim of the analysis is to study linkage disequilibrium, i.e. the co-occurrence of two variants in the same genome, and try to reproduce it by generating synthetic haplotypes.

More details are provided in [`project_notebook.ipynb`](https://github.com/riccardo03-maker/Statistical_Data_Analysis_Project/blob/master/project_notebook.ipynb).

## Repository

The whole analysis is written in R and it is reported in the Jupyter notebook [`project_notebook.ipynb`](https://github.com/riccardo03-maker/Statistical_Data_Analysis_Project/blob/master/project_notebook.ipynb). Data from gnomAD dataset in `.csv` format are located in the [`gnomad_dataset_csv`](https://github.com/riccardo03-maker/Statistical_Data_Analysis_Project/tree/master/gnomad_datasets_csv) folder.

Since, as explained in the notebook, gnomAD data do not contain information about the co-occurrence of variants in individual genomes, data from the [1000 Genomes Project](https://www.internationalgenome.org/) have been used to compute linkage disequilibrium coefficients and compare them to those obtained from synthetic haplotypes. Unlike gnomAD datasets, these data are not available in the `.csv` format, so they have been downloaded and converted into `.csv` format using the software `PLINK`. Details about the download of these data are provided in the [`Supplementary_material.ipynb`](https://github.com/riccardo03-maker/Statistical_Data_Analysis_Project/blob/master/Supplementary_material.ipynb) notebook. The full execution of this notebook could take a while, so the .csv files that are the final result of 
this notebook have been already created and put in the folder [`linkage_disequilibrium_csv`](https://github.com/riccardo03-maker/Statistical_Data_Analysis_Project/tree/master/linkage_disequilibrium_csv), ready for the analysis.

## References

All the references are reported in [`project_notebook.ipynb`](https://github.com/riccardo03-maker/Statistical_Data_Analysis_Project/blob/master/project_notebook.ipynb).

## Authors

* **[Riccardo Grandicelli](https://github.com/riccardo03-maker)**
