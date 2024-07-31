# Nutsch et al. Nature Cancer (2024)
This repository contains metadata and R code used to generate Fig 7 and Ext Fig 10 derived from human RNAseq and scRNAseq datasets presented in Nutsch, K., Banta, K.L. et al. Nature Cancer (in press; 2024).

Human sequencing data is available at: https://ega-archive.org/studies/EGAS50000000251 You will need to accept the terms and request access to download these data.

# Requirements
Data analysis was performed with R on a private HPC (Linux) but could be performed locally given sufficient memory. Please note that some parts of the scRNAseq analysis may temporarily require >200GB of free memory. All packages used in the analysis (all freely available from CRAN or the respective developer repository) are listed below.

- R 4.2.0
- survival 3.3-1
- survminer 0.4.9
- gridExtra 2.3
- svMisc 1.2.3
- stringr 1.5.1
- ggplot2 3.5.1
- rstatix 0.7.0
- ggpubr 0.4.0
- Seurat 4.2.0

# Figure 7 and Ext Data Figure 10
See the individual R notebooks for [Figure 7](Figure%207.Rmd) and [Extended Figure 10](Ext%20Figure%2010.Rmd).