1. They use RF ML method to predict what value globally? Describe in detail how RF works. 
Whats a dasymetric population allocation? Which geosptial covariates seem to be most important 
for determening where populations live


In Nives et al, thy use the Random Forest Machine Learning approach to predict population density. THey took the log of the population and estimated the model to account for differenes in distribution

Random Forest is an ensebles method that is non-parametric and non-linear. Decision trees are grown using bootstrap samples of the data, and the remaining bagged training data that was not used to grow the tree is referred to as Out of Bag Data (OOB).  The model learns how to train itself



Dasymetric population allocation provides insights to the relationship between population and ancilary variables. It redistributes the population counts from census-based to grid cells. gives you percentage of the whole. takes the grid cells and tells you whats the porportion for each individual cell for where the population is. then takes pop for all adms and distributes it across that entire space.

Covariates relating to urban area (buildings, land cover, etc.) and topographical features were the most important predictors of population density. The top five important covariates include urban/suburban extents, built environment and urban/suburban proxies, climatic/environmental variables, populated place covariates and transportation networks. 



Lecture Notes:
-urban areas utilize the log transformation
-log is taken in areas where theres one population area that is very dense
