# Spatial Machine Learning

Ensemble methods in Machine Learning use multiple learning algorithms to obtain better predictive performance than could be obtained from any of the constituent learning algorithms alone. The methods can be divided into bagging and boosting methods. In such models, many decision trees are created, called an ensemble or a forest. These decision trees are used for prediction and final predictions are not based on any single tree, but rather on the entire forest. However given the clustering, and heterogeneous nature of geographic data, the decision trees regular in ensemble models neglect the spatial relationship of each observation with its neighbor. In this workshop we will go through the usage of ensemble models such as Random Forest and gradient boosting with spatial datasets for classifications and regressions.
Keywords: spatial machine learning; spatial dependence; spatial heterogeneity

Duration: 2 hours

Prerequisites: A laptop and familiarity with R
Please install these packages before the workshop
* library(dplyr)
* library(raster)
* library(randomforest)
* library(future)
* library(mlr3)
* library(sf)
* library(terra)

 

