# MechaCar

## Overview

You are assisting Jeremy, head of the data analytics team, to perform an internal audit on AutoRUs's latest production model the 'MechaCar'. The data analytics team has promised to provide the following results to help determine the root cause of the MechaCar's manufacturing troubles:

- Multi-variate linear regression to predict the mpg of the MechaCar prototype
- Summary statistics on the PSI rating of the suspension coils from each manufacturing lot
- T-tests on the Suspension coil dataset to determine each lots variation from the population mean
- Statistical study to compare the MechaCar performance compared against other manufacturers.

## Software Requirements
- [R for MacOS](https://cran.r-project.org/bin/macosx/)
- [R Studio Desktop for MacOS](https://www.rstudio.com/products/rstudio/download/)

### Packages
- [Tidyverse](https://www.tidyverse.org/)

### Optional
- Rmarkdown
- ggplot library

# Deliverable 1: Linear Regression to Predict MPG
The following variables were used to determine statistical significance on the miles per gallon (mpg) rating of the vehicle. These are ordered by the non-random amount of variance to MPG:
| Variable | Coefficient Estimate |
|:---|:---|
| Vehicle Length | 6.267 e0 |
| Ground Clearance | 3.546 e0 |
| Spoiler Angle | 6.877 e-2 |
| Vehicle Weight | 1.245 e-3|
| All Wheel Drive (AWD) | -3.411e0 |

The p-value for this analysis (5.35 e-11) which is much smaller than the significance level (0.0005) suggests that there is sufficient evidence to reject the null hypothesis. 

The linear model with all the variables included is able to predict at least 71.4% of MPG estimates, showing a strong positive correlation for the given variables. 

# Deliverable 2: Summary Statistics on Suspension Coils
Weight capacities in PSI were tested to determine the consistency of the manufacturing process across multiple production lots. These are the results from the statistical summary done on the provided dataset:

| Lot # | Mean | Median | Variance | SD |
|:---|:---|:---|:---|:---|
| 1 | 1500 | 1500 | 0.9795918 | 0.9897433
| 2 | 1500.2 | 1500 | 7.4693878 | 2.7330181 |
| 3 | 1496.14 | 1498.5 | 170.2861224 | 13.0493725 |
| Total | 1498.78 | 1500 | 62.29356 | 7.892627 |



