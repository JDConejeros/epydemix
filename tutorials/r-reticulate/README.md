# R Tutorials for Epydemix using the `reticulate` package.

This directory contains tutorials demonstrating how to use **Epydemix** from **R** via the [**`reticulate`**](**https://rstudio.github.io/reticulate/**) package.

Epydemix is a Python-based framework for epidemiological modeling and simulation. However, many researchers and epidemiologists work primarily in the R ecosystem. These tutorials provide a bridge between the two environments, showing how Epydemix can be integrated into R workflows.

The tutorials reproduce the official Python tutorials included in this repository while illustrating how the same tasks can be executed from R using `reticulate`.

## Objectives

The main objectives of these tutorials are:

**-** Demonstrate how to import and use the Epydemix Python package from R

**-** Replicate the official Epydemix tutorial workflow using R-based scripts

**-** Facilitate the adoption of Epydemix among researchers working in R

**-** Provide reproducible examples combining R and Python tools for epidemiological modeling

## Tutorial Structure

The tutorials follow the same structure as the official Python tutorials:

**1.** Model definition and simulation 

**2.** Using population data 

**3.** Modeling non-pharmaceutical interventions 

**4.** Model calibration with ABC (Part 1) 

**5.** Model calibration with ABC (Part 2) 

**6.** Advanced modeling features

**7.** COVID-19 case study

**8.** Modeling multiple strains

**9.** Modeling vaccinations 

**10.** Speeding up simulations and calibration with multiprocessing 

**11.** Using Epistorm-Mix contact matrices

## Requirements

To run these tutorials you will need:

**-** R (≥ 4.0 recommended)

**-** the `reticulate` package

**-** Python with Epydemix installed

Example setup in R:

```r
install.packages("reticulate")
library(reticulate)

py_install("epydemix")
```

These tutorials are currently under development and will be gradually expanded as part of an open-source contribution to the Epydemix project.
