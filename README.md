# Duong et al. (2025)
This repository contains R code used to generate Fig 2E and S1M presented in Duong et al. (2025). [https://doi.org/xyz](link to article to be added when available)

Human sequencing data is available at: https://ega-archive.org/studies/EGAS50000000251 You will need to accept the terms and request access to download these data. Please note that these sequencing data were originally published as part of Guan X et al. Anti-TIGIT antibody improves PD-L1 blockade through myeloid and Treg cells. _Nature_. 2024 Mar;627(8004):646-655. Epub 2024 Feb 28. [https://doi.org/10.1038/s41586-024-07121-9](https://doi.org/10.1038/s41586-024-07121-9). PMCID: [PMC11139643](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11139643/).

# Requirements
Data analysis was performed with R on a private HPC (Linux) but could also be performed locally. All packages used in the analysis (all freely available from CRAN or the respective developer repository) are listed below.

- R 4.2.0
- survival 3.3-1
- survminer 0.4.9
- survivalAnalysis 0.3.0
- gridExtra 2.3
- svMisc 1.2.3
- stringr 1.5.1
- ggplot2 3.5.1
- rstatix 0.7.0
- ggpubr 0.4.0
- babelgene 22.3
- gridExtra 2.3
- svMisc 1.2.3
- forestploter 1.1.2

# Figure 2E and S1M
See the [R notebook](Fig%202E%20and%20Fig%20S1M.Rmd).
