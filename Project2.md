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


![](Syria_diff_3D.png)
Here is the 3D Plot for the entirety of Syria, and shows the error between the two population values.

As can be seen from all of these plots, Damascus and the area outisde of Damascus, Raf al-Damascus, are very heavily populated. 

## Damascus Subdivision of Syria
### I subsetted the adm2 region of Damascus and mapped both the population differences for the predicted and world pop data and the error. 

![](damascus_diff_plot_2.png)
This is the difference map for Damascus

![](damascus_pop_plot_2.png)
This is the map showing the error for the predicted values


![](damascus_adm2.png)

Here is the mapview for Damascus. As you can see, it doesn't line up nicely with the boundaries of Damascus which is what I am trying to fix.

![](Damascus_diff_3D.png)

