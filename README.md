# covid19nyc
A latent class ecological analysis of COVID-19 disparities in cases and deaths in NYC

## models.Rmd

Input: 

  - input/data.RData: cleaned modeling dataset
  - nyc_map_modzcta.adj: adjacency file needed for modeling with INLA

Output: 

  - 
Read in modeling dataset with weekly counts of outcome variables. Contains covariates of Non-Hispanic black, Hispanic, and Age Over 65. Executes INLA models and outputs results for publishing table. 



## tables_figures.Rmd
