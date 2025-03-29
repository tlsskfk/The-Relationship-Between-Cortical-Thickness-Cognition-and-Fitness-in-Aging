# The Relationship Between Cortical Thickness Cognition and Fitness in Aging

## Analysis of FMRI data provided by the (Human Connectome Project)[#https://www.humanconnectome.org/]

<img src="https://www.humanconnectome.org/themes/uar_washu/assets/images/logos/ccf-logo.png" alt="Human Connectome Project Logo" width="200" />

## Contributors
Dr. Jeremy Purcell
Yi Wei
Stephen Shin
David Soussana


This repository is managed by: Stephen Shin

## Repository structure

A brief overview of the project's directory structure and key files.  

```plaintext
NTR_2025\
│
├── data/                   # Input Data
│
├── docs/                   # Documentation
│   └── instructions.md     # Instructions on how to run the entire project
│
├── analysis/                             # Analysis Scripts
│   ├── 01-main-effect/                   # Main Bayesian Analysis Script 
│   ├── 02-mediation-main-effect/         # Mediation of Main Bayesian Analysis Script
│   ├── 03-bayesian-interaction-effect/   # Bayesian Analysis Script after application of Mediation
│   └── 04-mediation-interaction-effect/  # Mediation of Bayesian Interaction Effect
│
├── assets/                 # Static assets (images)    
│
├── .gitignore              # Git exclusion rules  
└── README.md               # This file
