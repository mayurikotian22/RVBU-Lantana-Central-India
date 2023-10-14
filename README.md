# Source code for understanding the species-level impact of ecological restoration
This repository contains R Markdown files and data used for the manuscript titled "Passive acoustic data yields species-level insights into invasive shrub removal in a Central Indian tropical dry forest". The code used in the analysis was written in the R programming language and uses data uploaded as .CSVs in the repository. 

## Data
The data was collected using Audiomoth acoustic recorders in the buffer area of Kanha National Park in Madhya Pradesh, India. We use this data to examine the species-level impact of a small-scale restoration effort carried out by removing an invasive shrub - Lantana camara. We use the Red-vented bulbul (RVBU), one of Lantana's known primary dispersers as our target species and study the changes in RVBU vocalization behaviour in sites with varying Lantana densities. The repository contains four .CSV files which are titled as below.
1. _RVBU_presence.csv:_ This file contains the presence-absence data for RVBU.
2. _RVBU_vocalizations.csv:_ This file contains data where each vocalization is used as an individual unit of analysis.
3. _RVBU_vocalizations_with_exp_var.csv:_ This file contains data where each vocalization is used as an individual unit of analysis along with six additional explanatory variables providing site-specific information about each recording location.
4. _RVBU_notes.csv:_ This file contains data where we use each note within a song or a call as an individual unit of analysis. This data is used for quantifying the spectral differences in the vocalizations in our sites. 

## R Markdown files
Below we provide descriptions for four R Markdown files in the repository which contain the source code used for data analysis in this project. We also provide detailed comments embedded within the code to explain each step of the analysis.
1. _01-Total-detections+Proportion-of-vocalization-types.Rmd:_ This file contains the source code used for 1. Quantifying the differences in the total number of times RVBU was detected in our sites, and 2. Quantifying the differences in the proportion of three RVBU vocalization types - songs, contact calls and alarm calls in our sites.
2. _02-Spectral-analysis.Rmd:_ This file contains the souce code used for quantifying the differences in the spectral parameters of RVBU songs and calls across our sites.
3. _03-Temporal-analysis.Rmd:_ This files contains the source code used for quantifying the temporal differences in RVBU vocalizations across our sites.
4. _04-Random-forest-analysis.Rmd:_ This file contains the source code used for examining the association between RVBU vocalization and Lantana density across our sites using the random forest algorithm. 
