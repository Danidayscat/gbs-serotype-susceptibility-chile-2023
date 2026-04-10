# Serotype and antibiotic susceptibility of Group B Streptococcus in pregnant women in Santiago, Chile

## Overview

This repository contains the R analysis code and supplementary statistical report
for the manuscript:

> **Serotype and antibiotic susceptibility of Group B Streptococcus in pregnant women in Santiago, Chile**  


## Repository Contents

| File | Description |
|------|-------------|
| `gbs_analysis.Rmd` | Main R Markdown analysis script |
| `gbs_supplementary.pdf` | Compiled supplementary statistical report |

## Requirements

- R version 4.5 (R Core Team, 2025)
- Packages: `tidyverse`, `readxl`, `knitr`, `kableExtra`

Install all dependencies with:

```r
install.packages(c("tidyverse", "readxl", "knitr", "kableExtra"))
```

## Reproducing the Analysis

Open `gbs_analysis.Rmd` in RStudio and click **Knit**, or run:

```r
rmarkdown::render("gbs_analysis.Rmd")
```

## Data

The dataset contains 185 GBS isolates collected at Clínica Alemana,
Santiago, Chile (2023). Variables include: anonymous isolate ID,
serotype (multiplex PCR), and susceptibility results for penicillin,
vancomycin, erythromycin, and clindamycin (disk diffusion).
