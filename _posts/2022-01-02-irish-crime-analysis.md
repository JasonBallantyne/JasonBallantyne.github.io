---
layout: post
title: Irish Crime Analysis
subtitle: An analysis and report of crime in Ireland from 2003 to 2019 in R
cover-img: /assets/img/Crime1.jpg
thumbnail-img: /assets/img/BigData1.jpg
gh-repo: JasonBallantyne/IrishCrimeAnalysis
gh-badge: [star, fork, follow]
tags: [data-science, r, ggplot2, dplyr, tidyverse, data-visualization, s4class, reshape2, confidence-interval]
---

An analysis and report of crime in Ireland from 2003 to 2019 in R. A report of the key functionality of dplyr and a confidence interval function, complete with methods to print, summarise and plot the function in R.

## Part 1
Consists of an analysis of the all types of crimes committed in Ireland from the year 2003 to 2019. This data originated from StatBank, Central Statistics Office, Govt.
of Ireland website, however the data set used can be found here: [https://www.kaggle.com/sameerkulkarni91/crime-in-ireland/version/1](https://www.kaggle.com/sameerkulkarni91/crime-in-ireland/version/1)

Analysis includes the overall crime for each year, a breakdown of crime by region, a breakdown of crime by offence and a breakdown of crime by region filtered by theft and related offences. A report discussing our findings is then carried out.

## Part 2
Involves a report and demonstration of key functionality of the *dplyr* package.
In particular we look at the filter(), mutate(), select() and summarize() functions more closely and demonstrate their purpose.

## Part 3
Includes the creation of a statistical analysis of interest. The function I have created calculates the *confidence interval* of a proportion where p is the sample proportion and n is the sample size. We then provide appropriate print, summary and plot methods for this function.
