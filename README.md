# Customer Segmentation via Unsupervised Learning (Clustering)

This repository documents an unsupervised learning study on **customer segmentation**.  
The goal is to identify meaningful customer groups by maximizing **silhouette score** and selecting an appropriate number of clusters through empirical analysis.

## Research Goal
- Segment customers into clusters that are internally coherent and well-separated.
- Justify the number of clusters using quantitative criteria and diagnostic plots.

## Methodology
1. **Exploratory data analysis (EDA)** and preprocessing (including handling missing values)
2. Determine the number of clusters using:
   - **Elbow method (WCSS vs. k)**
   - **Silhouette score vs. k**
3. Train a final clustering pipeline (scikit-learn only)
4. Report:
   - the selected number of clusters
   - final silhouette score
   - cluster size distribution

## Tools
- Python
- scikit-learn

## Repository Structure
- `notebooks/` — analysis and experiments (if applicable)
- `src/` — final runnable pipeline code
- `docs/` — plots and brief report

## Status
Documentation-first repository.  
Code and final results will be uploaded after cleanup and reproducibility checks.
