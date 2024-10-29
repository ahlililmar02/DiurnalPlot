# Diurnal Atmospheric Turbulence Flux Plotter

This project provides tools to analyze and visualize the **diurnal cycle of atmospheric turbulence Flux parameters**. The Python scripts enabling researchers to investigate daily patterns in atmospheric parameters such as wind speed, temperature, turbulent fluxes, etc. This script processes output from **EddyPro software**, a widely used tool for eddy covariance data.

## Features

- **Diurnal Averaging**: Calculate mean values of turbulence flux parameters for each hour of the day.
- **Compositing for Meteorological Conditions**: Separates and composites data based on Cross Equatorial Northerly Surge (CENS) and non-CENS conditions, allowing users to visualize and compare the diurnal cycle 
  of atmospheric turbulence flux under varying synoptic conditions.
- **Customizable Plotting**: Generate diurnal cycle plots with adjustable axis labels, colors, and styles.
- **Quality Control**: Ensure data has realistic values for parameters, checks have confirmed all timestamps are sequential, with no missing entries

Works with datasets in CSV

## Requirements

- **Python** 3.6 or higher
- Required packages:
  - **`pandas`**: For data handling
  - **`matplotlib`**: For plotting
  - **`numpy`**: For numerical calculations



