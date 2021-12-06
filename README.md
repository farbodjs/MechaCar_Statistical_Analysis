# MechaCar_Statistical_Analysis
## Overview

In this project we performed a statistical analysis to analyze multiple datasets from the automotive industry.
Using a dataset containing mpg test results for 50 MechaCar design prototypes, I have created a linear regression model that will predict miles-per-gallon results based off of several factors; vehicle length, vehicle weight, spoiler angle, ground clearance, and whether the prototype is AWD.
We Used R programming language and Pandas to perform statistical analysis on multiple data sources in this project.




## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/86033316/144937822-4d3a38f1-fc15-417b-b54d-210c9d4daa8f.png)

### - Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

In our multiple linear regression summary, the variables with a pr(>|t|) value larger than the significance level of 0.05 provide a non-random amount of variance to the mpg values in the dataset. These variable are vehicle weight, spoiler angle, and AWD. The variables with pr(>|t|) values less than the significance level, vehicle length and ground clearance, have random amounts of variance and do not necessarily directly effect the mpg of the prototypes.
### - Is the slope of the linear model considered to be zero?

Our p-value of 5.35e-11, which is lower than the significance level of 0.05, lets us know that the slope of the line is not zero. This means that changes to the collection of predictor variables in the linear model are associated with a change in the response variable of MPG.

### - - Does this linear model predict mpg of MechaCar prototypes effectively?
The R-squared value of .7149 informs us that the model can predict the mpg of MechaCar prototypes effectively roughly 71% of the time. This means that there may or may not be other variables that could potentially contribute to the additional ~29% of variance that are not included in our model. Also, our absolute r-value which we can get by taking the square root of our r-squared value is 0.845, suggests that our model has a strong correlation. These outputs suggest that our model does in fact predict the mpg of MechaCar prototypes effectively.
