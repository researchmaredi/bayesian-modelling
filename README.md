# Bayesian Modelling

This repository contains a collection of advanced Bayesian modelling projects completed during my BScHons. The projects demonstrate statistical inference, MCMC implementation, and hierarchical modelling using **R** and **Stan**.

## Projects Overview

### 1. [Statistical Model Critique](./statistical-model-critique)
A critical analysis of a flawed frequentist regression workflow.
- **Focus:** Diagnostics, normality assumptions, and multicollinearity checks.
- **Tools:** R, Shapiro-Wilk, ANCOVA diagnostics.

### 2. [Bayesian Revenue Prediction](./bayesian-revenue-prediction)
Predicting 2025 revenue for AI companies using robust Bayesian regression.
- **Focus:** Data cleaning, variable transformation, and posterior prediction.
- **Outcome:** Predicted revenue distributions with uncertainty quantification.

### 3. [Prior Sensitivity Simulation](./prior-sensitivity-simulation)
A simulation study comparing Objective vs. Subjective priors.
- **Focus:** Risk analysis, loss functions, and decision theory.
- **Outcome:** Determined optimal priors for minimizing expected loss.

### 4. [Robust Censored Regression](./robust-censored-regression)
Handling extensive missing data in medical datasets.
- **Focus:** Multiple Imputation (SRMI), Censored Regression, and Laplace errors.
- **Tools:** R, MICE, Custom Gibbs Sampler.

## Tools Used
- **Languages:** R, Stan
- **Libraries:** `rstan`, `coda`, `tidyverse`, `ggplot2`
