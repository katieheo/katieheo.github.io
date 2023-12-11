---
title: "Reproducing Vijayan et al.'s 2020 Study"
excerpt_separator: "<!--more-->"
categories:
  - Study
tags:
  - GIS
  - Science
  - Open Source
---

In our study of ["Beyond the 405 and the 5: Geographic Variations and Factors Associated With Severe Acute Respiratory Syndrome 
Coronavirus 2 (SARS-CoV-2) Positivity Rates in Los Angeles County"](https://pubmed.ncbi.nlm.nih.gov/33141164/) by Tara Vijayan et al., 
[Alex](https://alexxuyide.github.io) and I aimed to reproduce and evaluate the spatial patterns and predictors of COVID-19 outcomes
in Los Angeles County. Vijayan et al. originally sought to examine whether spatial patterns existed in SARS-CoV-2 age-adjusted testing rates, age-adjusted diagnosis rates, and crude positivity rates in Los Angeles County (LAC), and used hexagons (spatial regression model) to explore associations between COVID-19 crude positivity rates and a series of predictor variables.

In [our reproduction study](https://katieheo.github.io/RPr-Vijayan-2023/), we encountered challenges due to missing details in the original study such as the hexagon grid generation method and simulation parameters. Hence, we made efforts to address these gaps. In looking at the hexagonal grid to overlay COVID data, we observed threats to validity in the boundary effect, also known as the edge effect in the holes observed in between the hexagons that present census tracts in Los Angeles county. As Rolf R. Schmitt outlined in **Threats to Validity involving Geographic Space**, an issue to validity that arose in the study was partition distortion. To some extent, we were able to resolve this by creating a new hexagon grid that better fitted the COVID data and fixed connectivity issues observed in the original grid.

Another issue we resolved in our reproduction study was selection bias - the data we used for analysis for the age-adjusted diagnosis rates and 
age-adjusted testing rates were not explicitly presented in the main paper. Vijayan et al. did not include the tables 
that they did not succeed in reproducing to the study and instead just attached them as supplementary data. Hence, we worked on reproducing all tables from the study. 


Here are the links to.. 

[Our research compendium](https://github.com/katieheo/Rpr-Vijayan-2023)

[The original study by Vijayan et al.](https://academic.oup.com/cid/article/73/9/e2970/5952808)

[Our reproduction study of Vijayan et al.](https://katieheo.github.io/RPr-Vijayan-2023/)

*Find more information about the class I am taking [**here**](https://opengisci.github.io)!*

--------
Bibliography

Schmitt, R. R. (1978). Threats to validity involving geographic space. Socio-Economic Planning Sciences, 12(4), 191–195. https://doi.org/10.1016/0038-0121(78)90044-7
