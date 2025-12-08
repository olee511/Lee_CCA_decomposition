# Constructed Circulation Analog Decomposition for SWUS precipitation 
This repository contains information on the constrcuted circulation analog method I developed for SWUS precipitation.
The goal of this project is to understand if we can use extreme events to contextualize past and future summertime equilibrium mean precipitation in the Southwest US.
Specifically, I am comparing the precipitation response to warm California margin SSTs:
  - driven by mean warming due to elevated CO2 (equilibrium)
  - associted with a marine heatwave (extreme)

# Data
I perform this analysis on long-run climate models from LongRunMIP [Rugenstein et al. (2016)](https://journals.ametsoc.org/view/journals/bams/100/12/bams-d-19-0068.1.xml).

# Method Overview
I use CCA to decompose the precipitation responses in the two scenarios into the dynamic and thermodynamic components:
## Equilibrium Mean
For our equilibrium analysis, we construct analogs of the forced equilibrium mean SLP anomaly to understand the precipitation associated with the forced circulation change in higher CO$_2$ climates. The equilibrium mean SLP anomaly represents the difference between the summertime climatological SLP pattern in a climate characterized by a greater CO2 concentration and the unforced climate. We reconstruct this forced SLP anomaly from a linear combination of control SLP and therefore from internal circulation variability alone. We subtract the dynamic component of each variable from the total equilibrium anomaly to get the residual. Because the residual precipitation anomaly is the component of precipitation changes not directly related to SLP changes, we interpret the residual as the forced thermodynamic component.

## Marine Heatwaves
We apply a similar method to the MHW case with some key differences. One major difference is that we reconstruct the MHW SLP anomaly from the non-MHW years in each respective abrupt experiment as opposed to the control experiment. This is because we aim to reconstruct the SLP anomaly during an extreme event from the internal atmospheric circulation variability that is characteristic of the climate in which the extreme occurred. Additionally, we reconstruct the MHW SLP anomaly from the non-MHW years because our goal is to isolate the precipitation driven by internal atmospheric variability from the precipitation due to the MHW forcing. As before, we subtract the linearly reconstructed variable maps from the total anomaly to get the thermodynamic residual. 
