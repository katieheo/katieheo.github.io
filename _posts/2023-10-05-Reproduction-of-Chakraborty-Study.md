---
title: "Reproduction of Chakraborty Study 2021"
excerpt_separator: "<!--more-->"
categories:
  - Study
tags:
  - GIS
  - Science
  - Open Source
---

In our reproduction and reanalysis study of ["Social Inequities in the Distribution of COVID-19: An Intra-Categorical Analysis of People with Disabilities in the U.S."](https://www.sciencedirect.com/science/article/pii/S1936657420301394?ref=pdf_download&fr=RR-2&rr=8112c85ec9324204) by Jayajit Chakraborty, we contribute to a more comprehensive understanding of the interplay between **disability, socio-demographics**, and **COVID-19**, while also highlighting the importance of rigorous reproducibility in scientific inquiry. In our study, we encountered both similarities and deviations from the original findings. While some deviations can be attributed to differences in computational environments, we leveraged these variations to scrutinize the research design critically, assess internal validity, and test the robustness of key parameters.

In the context of reanalyzing the data using <w style="color:blue;">Generalized Estimating Equations (GEE)</w>, we found that while some variables exhibited consistency in their relationships, others displayed instability across different models, warranting further investigation. My contribution to the study was working on a further analysis of residuals and weights by looking at the GEE model in the five models of race, ethnicity, poverty status, age, and biological sex model weights. Examining the weights in each of the five models allowed me to identify the consistency of the spatial patterns across the different demographic patterns. This also helped me look at variable sensitivity. The variable has different associations with COVID-19 in different regions of the United States, so it is sensitive to how we define clusters. My addition helped provide a more nuanced understanding of the relationships between disability, COVID-19, and sociodemographic factors.

[Our reproduction and reanalysis study](https://katieheo.github.io/RPr-Chakraborty-2021/), though revealing some deviations, align with the original study's central conclusion that people with disabilities, particularly those who are socio-demographically disadvantaged, may face heightened risks in the context of COVID-19. However, we emphasize the need for **additional research, finer spatial analysis**, and **a deeper exploration of the intricacies surrounding this complex issue**. Our work underscores the necessity of **cautious interpretation**, considering the limitations, including ecological fallacy, scale dependency, modifiable areal unit problem, variable measurement, and spatial dependency. Our study is a valuable teaching resource that would enable students and researchers to learn about the nuances of reproducibility in scientific research, the challenges of working with spatial data, and the importance of critical analysis in epidemiology.

Here are the links to.. 

[My research compendium](https://github.com/katieheo/RPr-Chakraborty-2021)

[The original study by Chakraborty](https://www.sciencedirect.com/science/article/pii/S1936657420301394?ref=pdf_download&fr=RR-2&rr=8112c85ec9324204)

[Our reproduction study of Chakraborty](https://katieheo.github.io/RPr-Chakraborty-2021/)

*Find more information about the class I am taking [**here**](https://opengisci.github.io)!*
