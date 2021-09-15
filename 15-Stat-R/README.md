# Statistics and R 

In this module, I learn how to apply statistics with R code in order to analyze vechile manufacturing data.



## Linear Regression to Predict MPG:

The most significant variables in our dataset which show a non-random effect on the MPG of the MechaCar are the Vehicle Length and the Ground Clearance. 
As indicated by the yellow arrows in the image above, a linear regression model run on these variables against figures for MPG, resulted in p-values of 2.6x10-12 and 5.21x10-8, respectively. 
The intercept was also statistically significant, indicating that there are likely other factors, not included in our dataset, that have a strong impact on the MPG.
Most likely there are other more impactful variables and factors that were not captured in the dataset that contribute to the mpg variability of the MechaCar prototypes.
The slope of the linear model can not be considered to be zero, as the p-value of 5.35x10-11, indicated by the orange arrow above, is lower than even an extreme level of significance, and thus the null hypothesis must be rejected. 
This means that the relationship between our variables and the miles per gallon is subject to more than random chance.



## Summary Statistics on Suspension Coils:

While the overall variance, as shown in the Total Summary data above, is under 100 psi and meets specifications, there is a problem with one of the individual lots. 
As shown in the Lot Summary stats, the variance for Lot 3 is well over the acceptable threshold, at 170.28.
If we combine all three lots and look at the total data, the overall calculated variance is within specifications.

## T-Tests on Suspension Coils:

According to each of the one-sample t-tests, Lot 1 and Lot 2 PSI values are not statistically different from the population mean. 
However the p-value of Lot 3 is 0.041 which is below the significance level, which means there is evidence that the Lot 3 mean suspension coil PSI is statistically different from the population mean.

## Design a Study Comparing the MechaCar to the Competition:

One metric that people are interested in when it comes to vehicles is horsepower. 
Horsepower is a common performance metric that is reported alongside car fuel-efficiency and engine size. 
Therefore it would be really easy to collect horsepower data for a large number of vehicles. 
We can create a study that tests whether or not the horsepower of MechaCar is statistically different from a collection of other comparable vehicles. 
The null hypothesis would be that there is no statistical difference between MechaCar horsepower and the horsepower of all other comparable vehicles. 
The alternative hypothesis would be that there is a statistical difference between horsepower of MechaCar versus the other vehicles. 
The statistical test we can use is a one-sample t-test, where the population data will be all comparable vehicles. 
To test this, we will need multiple horsepower data points from vehicles as well as multiple data points from the MechaCar vehicles, so it will be important that we include the horsepower of multiple vehicle configurations.
   
