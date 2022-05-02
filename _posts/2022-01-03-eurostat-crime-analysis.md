---
layout: post
title: Eurostat Crime Analysis
subtitle: Manipulating, analysing and creating a creative component to the EurostatCrime2019 dataset using R
cover-img: /assets/img/Eurostat.jpg
thumbnail-img: /assets/img/Ranalysis.png
gh-repo: JasonBallantyne/EurostatCrime2019Analysis
gh-badge: [star, fork, follow]
tags: [data-science, r, ggplot2, tidyverse, cowplot, data-visualization]
---

Using the EurostatCrime2019.csv for this analysis. This dataset records offences (values per hundred thousand inhabitants) by offence category in 41 European Countries in 2019.

Full information on the dataset is available here: [https://ec.europa.eu/eurostat/cache/metadata/en/crim_off_cat_esms.htm](https://ec.europa.eu/eurostat/cache/metadata/en/crim_off_cat_esms.htm)
 
 
## Tasks
In task 1 we **Manipulate** the dataset. 

In task 2 we **Analyse** the dataset.

In task 3 we add a **Creative** component to illustrate something we have not discovered with this dataset. 
This included plotting overall offences on the European map to quickly identify the high offending countries. 
It was done by combining ggplot2's map_data with our raw EurostatCrime2019 data.

![png](/assets/img/CrimeHeatMap.png)


