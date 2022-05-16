# covid19nyc

A latent class ecological analysis of COVID-19 cases and mortality in NYC

*Authors*: McCormack, Gao, Howard, Bachelder, Larsen, and Hyslop

*Contact*: kem81@duke.edu


## models.Rmd

Input: 

  - input/data.RData: cleaned modeling dataset
  - nyc_map_modzcta.adj: adjacency file needed for modeling with INLA

Output: 

  - results/final.models.Rdata

Code description: Read in modeling dataset with weekly counts of outcome variables. Contains covariates of Non-Hispanic black, Hispanic, and Age Over 65. Executes INLA models and outputs results for publishing table. 


## tables_figures.Rmd

Input: 

  - results/final.models.RData

Output: 

  - results/INLA_models_final_table.tex
  
Code description: Create publishing table from model results. 