# MechaCar_Statistical_Analysis
## Overview

In this project we performed a statistical analysis to analyze multiple datasets from the automotive industry.
Using a dataset containing mpg test results for 50 MechaCar design prototypes, I have created a linear regression model that will predict miles-per-gallon results based off of several factors; vehicle length, vehicle weight, spoiler angle, ground clearance, and whether the prototype is AWD.
We Used R programming language and Pandas to perform statistical analysis on multiple data sources in this project.




## Deliverable 1 - Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/86033316/144937822-4d3a38f1-fc15-417b-b54d-210c9d4daa8f.png)

### - Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

In our multiple linear regression summary, the variables with a pr(>|t|) value larger than the significance level of 0.05 provide a non-random amount of variance to the mpg values in the dataset. These variable are vehicle weight, spoiler angle, and AWD. The variables with pr(>|t|) values less than the significance level, vehicle length and ground clearance, have random amounts of variance and do not necessarily directly effect the mpg of the prototypes.
### - Is the slope of the linear model considered to be zero?

Our p-value of 5.35e-11, which is lower than the significance level of 0.05, lets us know that the slope of the line is not zero. This means that changes to the collection of predictor variables in the linear model are associated with a change in the response variable of MPG.

### - - Does this linear model predict mpg of MechaCar prototypes effectively?
The R-squared value of .7149 informs us that the model can predict the mpg of MechaCar prototypes effectively roughly 71% of the time. This means that there may or may not be other variables that could potentially contribute to the additional ~29% of variance that are not included in our model. Also, our absolute r-value which we can get by taking the square root of our r-squared value is 0.845, suggests that our model has a strong correlation. These outputs suggest that our model does in fact predict the mpg of MechaCar prototypes effectively.
## Deliverable 2 - Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
![image](https://user-images.githubusercontent.com/86033316/144941690-e2fbe1f5-1184-408f-a40f-3b71a70f0267.png)
![image](https://user-images.githubusercontent.com/86033316/144941739-41d28645-fb44-4a3e-9ff2-a9e71918f12f.png)

Based on the snippets of Lot Summary attached above, Lot 3 has a Variance of 170.286 per square inch which is above the design specificaiton of 100 per square inch for the MechaCar. However, based on the result of our statistical analysis which is attached above, total variance is 62.293 which meets the specifications. 

## creating box plots to visualize results for Lot and total summary

### total summary box plot
![image](https://user-images.githubusercontent.com/86033316/144942495-71f73ea7-7316-4095-84c9-0ffb7dfacffa.png)
### individual lots box plot
![image](https://user-images.githubusercontent.com/86033316/144942750-fad917bc-9881-4f95-a78a-507e3e39278d.png)

