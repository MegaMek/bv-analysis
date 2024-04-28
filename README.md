# MegaMek BV by Weight Analysis

This repository contains R and Quarto code to perform an analysis of the relationship between weight and BV by unit type. The goal is to develop a system of "generic BV" that can be used to balance randomized opponents without incorporating information about unit or pilot quality. 

The output of the current analysis can be found at https://gleeful-croquembouche-32c070.netlify.app.

This analysis should probably be re-run at intervals and values updated in MegaMek as we add new units. To run the analysis, the user must have [R](https://www.r-project.org/) and [Quarto](https://quarto.org) installed. It will also be easiest to run within the [RStudio environment](https://posit.co/download/rstudio-desktop/). First, the `check_packages.R` script should be sourced from within *R* with `source("check_packages.R")` to install required libraries, then the analysis.qmd file can be rendered to html from within RStudio or from the command line with `quarto render analysis.qmd`.
