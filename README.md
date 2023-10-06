# World Population Dataset Analysis

## Team Android Members

Kelly Eng
Matthew Roland
Jean Jimenez


## Intro

This repository contains an R script focused on analyzing the World Population Dataset. The dataset includes key metrics like population, area, and growth rate for various countries and territories from 1970 to 2022.

## Dataset Overview

The World Population Dataset provides detailed information about population metrics for different countries and territories. It includes variables like area, density per square kilometer, growth rate, and the percentage of the world population. The dataset is transformed into a long format for easier manipulation and visualization.

## Analysis Summary

The analysis identifies the top 10 countries with the highest and lowest population growth rates. These are visualized on a world map, color-coded based on their growth rate. Bar plots are generated to showcase the population sizes of these countries for the year 2022. Additionally, line graphs depict population growth trends over the years for each continent.

### Map Files Inclusion

The analysis incorporates geographical data through the inclusion of map files. These map files are read into the script using the `st_read()` function from the `sf` package in R. They serve as the base layer for visualizations that highlight countries with the highest and lowest population growth rates. The map adds a spatial dimension to the analysis, making it easier to identify geographical patterns or anomalies in population growth. This enhances the comprehensiveness and interpretability of the study's findings.

A shaded map highlighting the top 10 and bottom 10 countries based on their population growth rates will be generated. This map will be saved as a PNG file in the current working directory. The map uses different colors to represent countries with the highest and lowest growth rates, offering a quick, visual summary of global population trends. This feature enhances the analysis by providing an immediate spatial context to the numerical data.


## Conclusion

The analysis offers vital insights into global population dynamics. Countries with significantly high and low growth rates are identified, which could be crucial for policy decisions. The data also reveals that Asia has experienced the most significant population increase over the years. This information can serve as a basis for further socio-economic studies and planning.