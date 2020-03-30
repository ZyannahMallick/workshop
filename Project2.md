# Project 2: Syria

## Part 1: Acquiring, Modifying and Describing the Data
### Population Log ًًًwith Density
![](poplog_with_density.png)

### Night Time Lights with Density
![](ntl_with_density.png)

### Residual Model with Night Time Lights, Urban Cover, and Bare Cover Variables
![](residual_ntl_dst100_dst200.png)

R-sqaured: 0.2821

p-value: 0.3248

### Residual Model with All Variables 

![](residual_allvariables.png)

R-sqaured: 0.9998

p-value: 0.0402

# Part 2: Modeling and Predicting Spatial Values
## Population and Differences Maps of Syria
![](diff_adm2.png)

This image shows the differences in population for the world pop data and our predicted values.

![](population_adm2_plot.png)

This map shows the direction and magnitude of error for the predicted values.

![](Syria_mapview.png)

Here is the 3D Plot for the entirety of Syria.

## Damascus Subdivision of Syria
### I subsetted the adm2 region of Damascus and mapped both the population differences for the predicted and world pop data and the error. I'm still working on this part because I need to make it more centered and enlarged, as well as fix the coordinates for this region because it is not quite lined up on the region. 

![](damascus_diff_plot.png)
This is the difference map for Damascus

![](damascus_pop_plot.png)
This is the map showing the error for the predicted values


![](damascus_diff_mapview.png)

Here is the mapview for Damascus. As you can see, it doesn't line up nicely with the boundaries of Damascus which is what I am trying to fix.
