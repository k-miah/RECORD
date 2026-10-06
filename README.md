# RECORD: Simulation Study for Latent Class Mixed Models

This repository contains code for a simulation study and application analyses evaluating treatment effects on composite outcomes for disease activity using multivariate latent class mixed models (LCMMs) in rheumatic and musculoskeletal diseases (RMD).
 
## Overview
 
The objectives of this project are to:
 
- Evaluate the performance of latent class mixed models under various data-generating scenarios.
- Assess estimation of treatment-related effects on a latent outcome process.
- Quantify performance measures such as bias, type I error, and power.
- Apply the optimal modeling strategy to clinical trial data in RMD research.
 
## Repository Structure
```text
RECORD/
│
├── R/
│ ├── generate_data.R
│ ├── fit_multlcmm.R
│ ├── evaluate_results.R
│ └── helper_functions.R
│
├── scripts/
│ ├── 01_Simulations_lcmm.R
│ └── 02_Application_RA-trial.R
│
├── results/
│ ├── figures/
│ ├── tables/
│ └── simulations/
│
├── renv/
├── renv.lock
├── .gitignore
├── RECORD.Rproj
└── README.md
```
 
## Authors
 
**Kaya Miah**
Julius Center for Health Sciences and Primary Care
University Medical Center Utrecht
