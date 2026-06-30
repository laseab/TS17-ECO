# TS17-ECO

This repository contains scripts and workflows used for the analysis of 16S rRNA amplicon sequencing, biogeochemistry, and metatranscriptomic (RNA-seq) data from coastal Baltic Sea surface sediments. The analyses were performed to investigate spatial and temporal patterns in microbial community composition, functional potential, and environmental drivers.

## Overview

The project integrates multiple data types, including:
- 16S rRNA amplicon sequencing (community composition and diversity)
- Metatranscriptomic data (gene expression profiles)
- Environmental chemistry data (e.g. oxygen, nutrients, redox variables)

Analyses include:
- Microbial alpha and beta diversity analyses
- Differential abundance analysis (e.g. ANCOM-BC)
- Multivariate statistics (PERMANOVA, ANOVA)
- Co-expression network analysis (WGCNA)
- Functional annotation (KEGG-based)
- Data visualization and figure generation


## Repository structure

This repository contains all scripts used for data analysis and figure generation.

- scripts/   R scripts for 16S rRNA and metatranscriptomic data analyses

All raw and processed data are not included in this repository and will be made available upon publication or deposited in appropriate public repositories.


## Requirements

Analyses were conducted in R (version 4.6.0).

Key packages include:
- phyloseq
- vegan
- DESeq2
- ANCOMBC
- WGCNA
- ggplot2
- dplyr
- emmeans
- car

A full list of package versions is provided in `sessionInfo()`.

## Reproducibility

To reproduce the analyses using this codebase:

Clone this repository
Open the project in RStudio
Set the working directory to the project root
Run scripts

## Data availability

Raw sequencing data and associated metadata are publicly available in the National Center for Biotechnology Information (NCBI) Sequence Read Archive (SRA) and/or as specified in the associated manuscript.

Please refer to the published article for accession numbers and detailed dataset descriptions.

## Citation

If you use this repository, please acknowledge or cite the associated manuscript:

> This analysis supports a manuscript currently in preparation. Please contact the author for citation details once published.
