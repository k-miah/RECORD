# RECORD: Simulation Study for Latent Class Mixed Models

This repository contains code for a simulation study evaluating treatment effects on composite outcomes for disease activity using multivariate latent mixed models in rheumatic and musculoskeletal diseases (RMD).
 
## Overview
 
The objectives of this research project are to:
 
- Evaluate the performance of latent mixed models under various data-generating scenarios.
- Assess estimation of treatment-related effects on a latent outcome process.
- Quantify performance measures such as type I error and power.
- Apply the optimal modeling strategy to clinical trial data in RMD research.

## Simulation Design
- `ADEMP_PreReg_RECORD_2026.pdf`:
 
This document specifies the preregistered statistical simulation plan describing the design of the simulation study according to the ADEMP (Aims, Data-Generating Mechanisms, Estimands, Methods, and Performance Measures) framework by [Morris et al. (2019)](https://doi.org/10.1002/sim.8086), based on the template by [Siepe et al. (2024)](https://github.com/bsiepe/ADEMP-PreReg).
 
## Repository Structure
```text
RECORD/
│
├── R/
│ ├── generate_data.R
│ └── fit_models.R
│
├── simulation/
│ ├── sim_setting1.R
│ └── results/
|
├── ADEMP_PreReg_RECORD_2026.pdf
├── renv/
├── renv.lock
├── .gitignore
├── RECORD.Rproj
└── README.md
```
 
## Authors
 
**Kaya Miah**
Julius Center for Health Sciences and Primary Care,
University Medical Center Utrecht
