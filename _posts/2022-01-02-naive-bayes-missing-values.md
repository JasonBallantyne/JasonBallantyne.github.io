---
layout: post
title: Naïve Bayes handling missing values
subtitle: Implementing a Gaussian Naïve Bayes function in python that handles missing values
cover-img: /assets/img/ML5.jpg
thumbnail-img: /assets/img/PythonML.jpg
gh-repo: JasonBallantyne/NaiveBayesMissingValues
gh-badge: [star, fork, follow]
tags: [data-science, naive-bayes, python3, object-oriented-programming, sklearn]
---
Implementing a Gaussian Naive Bayes function in python that handles missing values, both explicity in the classification algorithm and using imputation methods.

## Part 1
Implementing a Gaussian Naive Bayes function that handles missing values. Gaussian Naive Bayes can handle missing values in training by calculating conditional probabilities on the values that are present. We explore two strategies:
1. Consider missing values explicitly in the classification algorithm.
2. Using imputation methods to guess missing values.

## Part 2
Testing the performance of my implementation against the scikit-learn GaussianNB using missing value imputation. For this we use two datasets:
1. PenguinsMV0.2.csv (20% missing values)
2. PenguinsMV0.4.csv (40% missing values)
