# PCA + Clustering + Enrichment Analysis (Longitudinal Dataset)

## Overview
This project is motivated by research on **Zika-induced microcephaly**, analyzing longitudinal measurements to uncover structure via PCA, clustering, and enrichment testing.
I use dimensionality reduction (PCA), k-means, and enrichment testing (Fisher’s exact test + log-odds)
to identify clusters and statistically significant group differences.

## Data
- **RNA-Seq longitudinal expression dataset:** mouse cortical development gene expression measured at **8 developmental time points** (−8, −4, 0, 1, 7, 16, 21, 28).
- **Zika microcephaly gene set:** curated list of Zika-associated genes mapped into the longitudinal expression matrix for focused analysis.

## Methods
- PCA for dimensionality reduction and visualization
- k-means clustering to identify groups in reduced space
- Enrichment analysis using Fisher’s exact test and log-odds to interpret cluster composition

## Key Outputs
- PCA visualizations and cluster assignments
- Cluster interpretation via enrichment testing
- Sensitivity checks 

## Report
- [Project report (PDF)](zika_project_report.pdf)
