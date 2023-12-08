---
title: "Spatial Accessibility Analysis of Chicago, Illinois"
excerpt_separator: "<!--more-->"
categories:
  - Study
tags:
  - GIS
  - Science
  - Open Source
---
In their study ["Rapidly measuring spatial accessibility of COVID-19 healthcare resources: a case study of Illinois, USA"](https://ij-healthgeographics.biomedcentral.com/articles/10.1186/s12942-020-00229-x), Jeon-Young Kang et al. sought to analyze COVID-19 spatial accessibility in Illinois. In [our reproduction of the study](https://katieheo.github.io/RPr-Kang-2020/), we aimed to reproduce the original study and explore methods for spatial accessibility analysis. Our contributions focused on refining the methodology and improving the accuracy of the results by improving the speed limit information and improving translation from hospital catchments into hexagons.

We enhanced the original study's methodology by using the osmnx.speed module to set more accurate speed limits based on road types, as opposed to assigning a default speed limit. This modification, particularly impactful in Chicago's residential areas, increased the precision of the network analysis, providing a more reliable representation of speed limits.

The study initially used a 50% threshold method for hexagonal grid allocation, leading to potential exaggeration or minimization of the influence of overlapping catchment areas. To address this, we utilized Area Weighted Re-Aggregation (AWR), allocating accessibility scores based on the percentage of hexagon area overlap with catchment areas. This alternative analysis, conducted specifically for Chicago, revealed nuanced changes, showing slightly lower rates of hospital accessibility in northern and western Chicago and slightly higher rates in the central city.

Recognizing potential inaccuracies in the original study, we focused on reducing data generalizations. Our **modification of the speed limit data** and the **implementation of AWR** aimed to enhance the accuracy of the spatial accessibility results, particularly for the at-risk population over 50.

For this reproduction study, our class ventured into the realm of CyberGIS by connecting to the cybergisx environment provided by the University of Illinois at Urbana-Champaign. This was the first time we ran a computationally intensive study on supercomputers, which showcased advancements in open, reproducible research and group collaboration.

Finally, through a critical reading of the original study and collaborative discussions, we identified and addressed potential threats to validity. Our modifications successfully mitigated data generalizations and uncertainties in aggregation methods.

Our contributions to the reproductive study of Kang et al.'s research not only refined the methodology but also demonstrated the importance of addressing potential threats to validity in spatial accessibility studies during a pandemic.

Here are the links to.. 
[My research compendium](https://github.com/katieheo/RPr-Kang-2020)
[The original study by Kang et al.](https://ij-healthgeographics.biomedcentral.com/articles/10.1186/s12942-020-00229-x)
[Our reproduction study of Kang et al.](https://katieheo.github.io/RPr-Kang-2020/)

*Find more information about the class I am taking [**here**](https://opengisci.github.io)!*

