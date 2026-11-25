# Bayesian Analysis of Treatment Effectiveness in Hospitalized Patients With Acute Kidney Injury

# Overview

This project applies Bayesian statistical methods to investigate treatment effectiveness and clinical risk factors associated with adverse outcomes among hospitalized patients with acute kidney injury (AKI).

The analysis uses data from the KAT-AKI randomized clinical trial and focuses on evaluating treatment effects while accounting for patient-level clinical characteristics.

# Research Objectives

Evaluate the association between treatment assignment and adverse clinical outcomes.
Investigate whether baseline clinical characteristics modify treatment effects.
Estimate posterior probabilities and treatment-related risk differences to characterize clinical outcomes and uncertainty.
Statistical Methods

- Bayesian logistic regression
- Treatment-by-covariate interaction models
- Markov Chain Monte Carlo (MCMC) estimation
- Posterior predictive assessment
- Model comparison using approximate leave-one-out cross-validation (LOO)
- Convergence diagnostics and posterior assessment

# Tools and Technologies

- R Markdown
- brms
- Stan
- tidyverse
- loo
- ggplot2

# Repository Structure

- AKI_Bayesian_Analysis.Rmd: Source file containing the statistical analysis and R code.
- AKI_Bayesian_Analysis.pdf: Knitted PDF report presenting the analysis, results, and interpretations.
- README.md: Project overview and documentation.
- Data Availability

The analysis uses data from the KAT-AKI randomized clinical trial. The original dataset is available through the Dryad repository.

Please refer to the original study and dataset documentation for access, appropriate citation, and data-use conditions.

# Reproducibility

The R Markdown source file documents the analytical workflow, including model specification, estimation, diagnostics, and posterior inference.

Required R packages should be installed before running the analysis. Access to the original dataset is also necessary to reproduce the results.

# Author

- Bernard Sefah
- MS Statistics
- Department of Mathematical Sciences
- Montana State University
