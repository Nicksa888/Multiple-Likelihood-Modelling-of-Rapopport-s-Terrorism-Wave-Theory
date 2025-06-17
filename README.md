Spatial Modeling of Terrorism in Rapoport’s Wave Theory
This project uses Bayesian spatial modeling (INLA) to analyze terrorist attacks in the Middle East across the Third (New Left) and Fourth (Religious) Waves of terrorism, as defined by David Rapoport’s Wave Theory. The analysis focuses on two key spatial variables: average travel time to attack sites and distance to international borders. These are modeled jointly using a multiple likelihood framework to assess ideological and operational differences between waves.

Data
The dataset includes:

xcoord and ycoord: Spatial coordinates of attack locations

Travel_Time_Average: Mean estimated travel time to each attack site

B_Dist_km: Straight-line distance to the nearest international border

Method
The analysis uses the INLA package in R to estimate separate spatial effects for each response variable across both waves. Results are interpreted in the context of Rapoport’s theory, with attention to the geographical behavior of terrorist groups and the implications of ideological evolution.

Outputs
Parameter estimates for each wave

Comparative spatial analysis

Reproducible RMarkdown file with full model code and interpretation

How to Use
Clone the repo and open the .Rmd file in RStudio. Run all chunks to reproduce the analysis. Ensure the INLA package is installed.

install.packages("INLA", repos = "https://inla.r-inla-download.org/R/stable")
License
MIT License
