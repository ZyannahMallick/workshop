# Stevens et al. Reading Response

Zyannah Mallick


Stevens et al. use an algorithm called Random Forest to produce high resolution descriptions of population distrubutions globaly. Random Forest is a nonparametric algorithm that has a certain number of regression trees, each of which is "bagged". Each tree has a different bootstrap sample of the data and this random sample is used to "estimate the individual tree splits after which the “out-ofbag” (OOB) error is calculated (the mean squared error) for those observations in the original training data which were not part of the random sample". The "forest" improves itself by using the best predictors outputted by the trees. You can determine how many trees the Random Forest will run, and as the number of trees increase so does the accuracy of the results. For this situation, the log population variable is used as the response variable.


What is a machine learning algorithm? Within the contect of this study what distinguishes a data science machine learning method (like RF) from previous classical statistical approaches to describing and analyzing phenomenon and events?

A machine learning algorithm recieves and analyzes input data to predict output values. Random Forest is a daysymmetric redistribution approach and it can incorporate large, global data sets of both continuous and discrete covariates when there is no finer data for larger areas. Random Forest uses both remotely sensed and geospatial data 


In the reading, the authors used a number of geospatial covariates as predictors in ther ML method. What were these geospatial covariates and approximately how big of a data set did they represent (in general terms)? What is the significance of big data in the estimation of ML methods for inferring the correlates and drivers of human population distributions?
