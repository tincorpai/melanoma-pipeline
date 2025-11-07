# melanoma-pipeline
Reproducible R pipeline for melanoma survival analysis using Kaplan-Meier, Cox models, and resampling methods (SMOTE, oversampling, bootstrap). Includes automated preprocessing, cleaning, and visualization workflows via Makefile and renv for reproducible research.


The Melanoma Survival Analysis Pipeline is a reproducible R-based workflow for modeling and visualizing melanoma survival data. It automates key analytical stages through a structured, transparent process:


Setup – Initializes a reproducible R environment using renv and installs all required packages.


Data Cleaning – Standardizes variable names, handles missing data, and validates input formats.


Resampling – Corrects class imbalance using SMOTE, ROSE, or bootstrap methods.


Modeling – Fits Kaplan–Meier, Log-Rank, and Cox proportional hazards models.


Visualization – Generates high-quality survival plots and summary tables with ggplot2 and survminer.


Automation – Executes all stages via a single Makefile for consistent and efficient analysis.


The pipeline supports reproducible, publication-ready melanoma survival studies.
