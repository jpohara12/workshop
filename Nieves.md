**Our question related to the reading for today.  Nieves et a. use the random forest machine learning method to predict what value globally?  Describe in detail how random forest works.  What is a dasymetric population allocation? Which geospatial covariates proved to be the most important when predicting global values of where humans reside?**

They use the random machine learning method to predict the value of population distribution , while also looking at the population density.  Random forests work through the a classification algorithm consisting of many decisions trees.  Using bagging and randomness when building on each tree making thus a collection of an uncorrelated forest of trees.  Random Forest use bagging with different datasets to be able to make decisions.  Also sets 1/30 of the data aside (out of bag data) to be able to use it for the learning of the actual algorithm.

Dasymetric population allocation*: Use of the population data plus the population density prediction through the random trees to allow for know of actual population count in a subdivision.  Those if you add up all the subdivision it equals the population size or 100%.

Which is that of a three step process to estimate a population layer from the census data and covariate data.   

1) Iterative covariate selection for the Random Forest model

2) The fitting of the Random Forest model, using all available census units, and creation of a population density weighting layer from the created Random Forest model

3) The dasymetric redistribution of population counts from census-based administrative units to grid cells 

The geospatial covariates which proved to be the most important in the predict of where humans reside were: 

-Urban/Suburban extents

-Built environment and urban/suburban proxies 

-Climatic/environmental variables 

-Populated place covariates 

-Transportation networks 