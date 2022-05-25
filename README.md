


# NestMRMC

This repo is for the methodology in the paper, "Single Reader Between-Cases AUC Estimator with Nested Data", submitted to SMMR Journal. It will be ready when the paper is published. 

<!-- badges: start -->
[![R-CMD-check](https://github.com/Pakillo/template/workflows/R-CMD-check/badge.svg)](https://github.com/Pakillo/template/actions)

[![HitCount since 2020-06-14](http://hits.dwyl.com/Pakillo/template.svg)](http://hits.dwyl.com/Pakillo/template)
<!-- badges: end -->


# Introduction

 The area under the receiver operating characteristic curve (AUC) is widely used in evaluating diagnostic performance for many clinical tasks. It is still challenging to evaluate the reading performance of distinguishing between positive and negative regions of interest (ROIs) in the nested-data problem, where multiple ROIs are nested within the cases. To address this issue, we identify two kinds of AUC estimators, within-cases AUC and between-cases AUC. We focus on the between-cases AUC estimator, since our main research interest is in patient-level diagnostic performance rather than location-level performance (the ability to separate ROIs with and without disease within each patient). Another reason is that as the case number increases, the number of between-cases paired ROIs is much larger than the number of within-cases ROIs. We provide estimators for the variance of the between-cases AUC and for the covariance when there are two readers. We derive and prove the above estimators' theoretical values based on a simulation model and characterize their behavior using Monte Carlo simulation results. We also provide a real-data example.  Moreover, we connect the distribution-based simulation model with the simulation model based on the linear mixed-effect model, which helps better understand the sources of variation in the simulated dataset.



# Structure

```bash
.
├── .gitignore
├── .Rbuildignore
├── DESCRIPTION
├── NAMESPACE
├── R
│   └── hello.R
├── exampleRPackage.Rproj
└── man
    └── hello.Rd
```

# Installation

# Usage Example

# References
