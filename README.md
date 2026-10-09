# BNT162b2 Vaccine Efficacy: Frequentist and Bayesian Analysis

**Undergraduate Statistics Project | March 2025**  
**Authors:** Ariel Xia, Yan Peng, and Yuxin Jin

## Overview

This project evaluates the efficacy of the Pfizer–BioNTech BNT162b2 COVID-19 vaccine using both **frequentist and Bayesian statistical methods**.

Using published clinical trial data (8 infections in the vaccinated group and 162 in the placebo group), we estimate vaccine efficacy and compare the results obtained from different statistical approaches.

## Methods

- **Frequentist inference:** Maximum likelihood estimation (MLE), large-sample confidence intervals, parametric bootstrap, and likelihood-ratio tests.
- **Bayesian inference:** Beta prior distributions, posterior estimation, equal-tail credible intervals, and highest posterior density intervals (HPDIs).
- **Statistical computing:** R, R Markdown, and `ggplot2` for simulation, analysis, and visualization.

## Key Findings

- Estimated vaccine efficacy was approximately **95%**.
- The frequentist 95% confidence interval was **91.56%–98.57%**, with a bootstrap interval of **91.03%–98.20%**.
- Bayesian analyses under three prior specifications produced similar efficacy estimates, supporting the overall conclusion of high vaccine efficacy.

## Files and Reproducibility

- `Efficacy-of-Vaccine.Rmd` — R Markdown source containing the statistical analysis, code, and visualizations.
- `Efficacy-of-Vaccine.pdf` — Full report generated directly from the R Markdown file.

To reproduce the report, open `Efficacy-of-Vaccine.Rmd` in RStudio and select **Knit to PDF** after installing the required R packages and LaTeX dependencies.
