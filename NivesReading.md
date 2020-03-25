# Nives et al. Reading

In Nives et al, researchers use Random Forest, a type of Machine Learning methodology, to predict global population density. THey took the log of the population and estimated the model to account for differences in population distributions.

Random Forest is an ensebles method that is non-parametric and non-linear. Decision trees are grown using bootstrap samples of the data, and the remaining bagged training data that was not used to grow the tree is referred to as Out of Bag Data (OOB). Decision trees that are weak learners are combined to form strong learners which allows for stronger data. Benefits of this methodology are that generalizability increases, datasets can be small or large, and the method can model difficult tasks well.

Dasymetric population allocation provides insights to the relationship between population and ancilary variables. It redistributes the population counts from census-based to grid cells based on population layers, and gives you the porportion of the population for each individual grid cell. Then it takes the population for all adms and distributes it across that entire space. Essentially, it estimates a population layer based on covariate and census data.

Covariates relating to urban area (buildings, land cover, etc.) and topographical features were consistently the most important predictors of population density. The top five important covariates include urban/suburban extents, built environment and urban/suburban proxies, climatic/environmental variables, populated place covariates, and transportation networks. 
