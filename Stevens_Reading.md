# Stevens et al. Reading Response

Zyannah Mallick


Stevens et al. use an algorithm called Random Forest to produce high resolution descriptions of population distrubutions globaly. Random Forest is a nonparametric algorithm that has a certain number of regression trees, each of which is "bagged". Each tree has a different bootstrap sample of the data and this random sample is used to "estimate the individual tree splits after which the “out-ofbag” (OOB) error is calculated (the mean squared error) for those observations in the original training data which were not part of the random sample". The "forest" improves itself by using the best predictors outputted by the trees. You can determine how many trees the Random Forest will run, and as the number of trees increase so does the accuracy of the results. For this situation, the log population variable is used as the response variable. Random Forest is a daysymmetric redistribution approach and it can incorporate large, global data sets of both continuous and discrete covariates when there is no finer data for larger areas. Random Forest uses both remotely sensed and geospatial data and incorporates them into the weighted layer of the model.

What is a machine learning algorithm? Within the contect of this study what distinguishes a data science machine learning method (like RF) from previous classical statistical approaches to describing and analyzing phenomenon and events?

A machine learning algorithm recieves and analyzes input data to predict output values. Random Forest first trains itself with the data and then "learns" before actually prodcuing results with     .Unlike classical approaches, RF is nonparametric 


In the reading, the authors used a number of geospatial covariates as predictors in ther ML method. What were these geospatial covariates and approximately how big of a data set did they represent (in general terms)? What is the significance of big data in the estimation of ML methods for inferring the correlates and drivers of human population distributions?

The geospatial covariates used in this paper are land cover: EarthSat GeoCover Land Cover TM and GlobCover data. Net primary productivity, night lights, mean annual precipitation, mean annual temperature were also used. Geospatial data that correlated to human population presence were also included: roadways, bodies of water, facility locations, etc. 

The authors results present a remarkable improvement over previous geospatial descriptions at very high resolution of the distribution of human population. Within the context of human development in LMICs, what is the significance of having accurate description of where each persom is located across planet earth?

Knowing the accurate population distribution of LMICs is very important for many reasons. If natural disaster or something similar were to occur in one of those countries, aid organizations would need to know the accurate description so they know how many resources and which areas to allocate resources too. Countries can use it to determine which areas are heavily populated and thus need more infrastructure and companies can use it as well to determine where best to target their products.

Within the context of human development in LMICs, what is the relevance to your area of investigation in having a highly accurate description of where each household and person is located across planet earth?

I plan on looking into health care centers/clinics in LMICs and so knowing where these centers are and how the population is distributed will be very helpful as to determining where there is a need for health care.  
