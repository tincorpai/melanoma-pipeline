# melanoma-pipeline
Reproducible R pipeline for melanoma survival analysis using Kaplan-Meier, Cox models, and resampling methods (SMOTE, oversampling, bootstrap). Includes automated preprocessing, cleaning, and visualization workflows via Makefile and renv for reproducible research.


The Melanoma Survival Analysis Pipeline is a reproducible R-based workflow for modeling and visualizing melanoma survival data. It automates key analytical stages through a structured, transparent process:


1. Setup – Initializes a reproducible R environment using renv and installs all required packages.


2. Data Cleaning – Standardizes variable names, handles missing data, and validates input formats.


3. Resampling – Corrects class imbalance using SMOTE, ROSE, or bootstrap methods.


4. Modeling – Fits Kaplan–Meier, Log-Rank, and Cox proportional hazards models.


5. Visualization – Generates high-quality survival plots and summary tables with ggplot2 and survminer.


6. Automation – Executes all stages via a single Makefile for consistent and efficient analysis.


7. The pipeline supports reproducible, publication-ready melanoma survival studies.
