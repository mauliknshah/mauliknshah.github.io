---
title: Finding Claim Severity
layout: post
icon: fa-lightbulb
icon-style: regular
---
#### Finding claim severity using All-State insurance data.
#### Area: Machine Learning Regression; Technologies: R, Weka.

Published in a Kaggle competition, the All-State privacy-preserved insurance data contains more than 100,000 records, 114 feature columns and a continuous variable to predict. The goal is to create a regression model that can predict the correct insurance claim value from the given data.

First, to make sense of the data, there were many distribution charts were generated using R. To reduce the number of features, principal component analysis (PCA) was employed, which reduced the data volume significantly. In the end, in the modeling part, linear regression, regression trees, and the multi-layer perceptron were used to model the actual output in Weka. The project was completed in a team of 3.
