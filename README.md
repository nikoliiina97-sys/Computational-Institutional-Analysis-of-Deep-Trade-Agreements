# Computational Institutional Analysis of Deep Trade Agreements

This repository contains the replication materials for my MA thesis on the institutional architecture of deep trade agreements and its association with bilateral merchandise exports.

The analysis constructs 116 sub-area institutional indices from the World Bank DTA 2.0 Vertical Content data, identifies recurring agreement architectures using Ward hierarchical clustering, and examines their association with bilateral export flows using PPML gravity models.

## Repository structure

- `DTA_Architecture_Analysis.Rmd`  
  Final R Markdown notebook containing the analysis.

- `DTA_Architecture_Analysis.html`  
  Rendered version of the final analysis notebook, including executed outputs, tables, figures, and diagnostics.

- `documentation/`  
  Supporting documentation for index construction, provision mapping, recoding, and exclusion decisions.

- `output/thesis_appendix/`  
  Outputs used in or referenced by the thesis appendices.

- `output/replication_diagnostics/`  
  Detailed family-by-index rankings, adjacent-cut diagnostics, clustering diagnostics, coverage checks, and supplementary analyses.

- `sessionInfo.txt`  
  R and package-version information for the final analysis environment.

## Data

The analysis uses:

- World Bank DTA 2.0 Vertical Content data
- BACI HS92 bilateral merchandise trade data
- CEPII GeoDist bilateral controls
- World Bank historical income classifications for the exploratory income-configuration analysis

The institutional clustering is based on 321 agreements with complete values on all 116 final indices. Trade outcomes are not used in the construction of the indices or architecture families.

The bilateral trade analysis covers 1995–2023.

The source datasets required to reproduce the analysis are documented in the analysis notebook.

## Reproduction

The analysis was conducted in R.

To reproduce the analysis:

1. Obtain the required source datasets.
2. Place the required input files in the project directory using the filenames expected by the R Markdown notebook.
3. Open `DTA_Architecture_Analysis.Rmd`.
4. Render the notebook from a clean R session.

The R and package versions used for the final run are recorded in `sessionInfo.txt`.

## Thesis

These materials accompany the MA thesis:

**Computational Institutional Analysis of Deep Trade Agreements**  
*A Typology of Agreement Architectures and Their Conditional Associations with Bilateral Exports*
