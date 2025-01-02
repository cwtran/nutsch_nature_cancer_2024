# Nutsch et al. _Nature Cancer_ (2024)
This repository contains metadata and R code used to generate Fig 7 and Ext Fig 10 derived from human RNAseq and scRNAseq datasets presented in Nutsch K, Banta KL, Wu TD, et al. TIGIT and PD-L1 co-blockade promotes clonal expansion of multipotent, non-exhausted antitumor T cells by facilitating co-stimulation. _Nat Cancer_ 5, 1834–1851 (2024). [https://doi.org/10.1038/s43018-024-00870-6](https://doi.org/10.1038/s43018-024-00870-6)

Human sequencing data is available at: https://ega-archive.org/studies/EGAS50000000251 You will need to accept the terms and request access to download these data. Please note that these sequencing data were originally published as part of Guan X et al. Anti-TIGIT antibody improves PD-L1 blockade through myeloid and Treg cells. _Nature_. 2024 Mar;627(8004):646-655. Epub 2024 Feb 28. [https://doi.org/10.1038/s41586-024-07121-9](https://doi.org/10.1038/s41586-024-07121-9). PMCID: [PMC11139643](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11139643/).

# Requirements
Data analysis was performed with R on a private HPC (Linux) but could be performed locally given sufficient memory. Please note that some parts of the scRNAseq analysis may temporarily require **>200GB** of free memory. All packages used in the analysis (all freely available from CRAN or the respective developer repository) are listed below.

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
