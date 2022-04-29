---
layout: post
title: Wheelie Good
subtitle: Dublin Bikes self-service web application
cover-img: /assets/img/Bikes1.png
thumbnail-img: /assets/img/wheeliegood.gif
gh-repo: JasonBallantyne/wheelieGood
gh-badge: [star, fork, follow]
tags: [data-science, pandas, numpy, api, flask, random-forest, sklearn, linear-regression, amazon-web-services]
---

A clean and functional web application designed for a user to navigate the Dublin Bikes self-service rental system. 
The user can find the closest available bike, plan their bike route, obtain weather information, visualise availability graphs as well as a host of additional features.


## 1. General Information

The application provides two web pages for the user to interact with. These pages display information about the Dublin Bike Stands,
both current and predictive, which the user can assess to plan their journey.

## 2. Dependencies and Technologies Used

The application uses a variety of technologies to implement. The back end of the web application is handled by python/flask, while the
front end is handled by Javascript/HTML/CSS. The application is a web based application run on an AWS EC2 Linux Ubuntu instance. 

The implementation of the application features relies on database information pulled from an AWS RDS Database, from the Google Maps API,
and from the Open Weather Map API. This is all handled by the back-end and provided as an in-browser service for the user. 

The project was built on the following versions:
   - `conda version : 4.9.2`
   - `conda-build version : 3.21.4`
   - `python version : 3.8.5.final.0`

We have provided an appropriate conda environment.yml file, which lists a full detail of dependencies. In order to run this application 
locally, you will need to install a conda environment using this .yml file and running the command `conda env create -f <path to yml file>`
in the conda command prompt. 


## 3. How to Use:

The application has two pages, a default index page that displays current information about the bike stands, and an additional "Plan your Journey"
page, which provides future and predictive features. 

Both pages contain a main map section and a information flex box. Interacting with the map or the drop downs will populate the scrollable flex
box with dynamic data. 

{: .box-note}
**Note:** This application has since been taken offline due to my expired AWS credits.
