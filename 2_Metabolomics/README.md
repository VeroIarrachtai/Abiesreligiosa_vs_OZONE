# README Paper Abies vs ozone

## Pre-requirements

Before starting the analysis here are the programs that need to be installed:

## SOFTWARE

* [R](https://cran.r-project.org)
* [Rstudio (optional)](https://rstudio.com)

## R packages

* library(tidyr)
* library(ggpubr)
* library(rstatix)
* library(dplyr)
* library(ggplot2)
* library(sjmisc)
* library(lmerTest)
* library(bruceR)


## METABOLOMICS directory structure:

```
+---- Abies_religiosa_vs_ozone/
|	+--2_METABOLOMICS/
|          +--bin/
|               +--Rstudio/
|                 +--2.1.-Calculate_relative_abs.R
|          +--data/
|              +--GC-MS/
|                 +--LibSrch_3.htm
|                 +--LibSrch_5.htm
|          +--metadata/
|              +--calculate_relative_abs.txt
|              +--metabolitos-Tesis-Vero.csv
|              +--calculate_relative_abs.txt
|          +--outputs/
|              +--Barplot_metabol.tiff
|          +--README.md
```

## Content (2_Metabolomics)

**`/bin`**

Here you will find the scripts that are needed to perform the analyses. There is a folder for scripts that run in [Rstudio](https://github.com/VeroIarrachtai/Abies_religiosa_vs_ozone/tree/master/2.-METABOLOMICS/bin/Rstudio).

**`/data`**

Here are the product files of the Gas chromatography–mass spectrometry (GC-MS).

**`/metadata`**

Here are tables and data that complement the omics data. Such as name of samples, name of genes, name of sequences.

**`/outputs`**

The figures from Rstudio are stored here.

**`/README.md`**

This is a README that describes the steps to perform the data analysis. It is organized numerically. It is explained that input is necessary and what outputs are obtained from each step.


# 2.- Calculate relative concentration

The following script was used to calculate the relative concentration of metabolites.

* **INPUT**:
  * **metabolitos.csv/htm_df.txt**(metabolitos_Tesis_Vero.csv)

* **OUTPUT**:
  * **calculate_relative_abs.txt**(calculate_relative_abs.txt)

## 2.1.-Calculate_relative_abs

SCRIPT in 2_METABOLOMICS/Rstudio/[2_1_Calculate_relative_abs.R](bin/Rstudio/2_1_Calculate_relative_abs.R)

**INPUT**:**metabolitos.csv/htm_df.txt**(metabolitos_Tesis_Vero.csv)

**OUTPUT: calculate_relative_abs.txt**


###Contact

```
Verónica Reyes Galindo
veronica.rg.pb@gmail.com
```
