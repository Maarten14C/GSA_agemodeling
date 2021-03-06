---
title: GSA age-modelling
output: rmarkdown::html_vignette
vignette: >
  %\VignetteIndexEntry{GSA age-modelling}
  %\VignetteEngine{knitr::rmarkdown}
  \usepackage[utf8]{inputenc}
---


# GSA_agemodeling

Welcome to the GSA Short Course on *Age-Depth Modeling of Sedimentary Deposits*. This course will have four sessions:

1. A prep check-in on Sep 13, to make sure all relevant software on your computer is working
2. On Sep 15 we will discuss radiocarbon dating and calibration, and introduce how to make simple age-models
3. On Sep 22 we will look at the theory and implementation of Bayesian age-depth models (mainly `rbacon`)
4. Then finally on Sep 29 we will look at Pb-210 age-modelling and will be producing age-models for your own cores.

All sessions will take place at 9-11am PDT (Pacific Daylight Time) on Zoom

You will need to have a recent version of [R](http://r-project.org) installed for your operating system, at least version 4.0. If you want, you can also install [RStudio](http://www.rstudio.com). Note that the version numbering differs between `R` and `Rstudio`; most important is to have a recent version of `R`.
Please install the following R packages:

```{r}
install.packages(c("IntCal", "clam", "rbacon", "coffee"))
```

[next: session 1](session_1.html)
