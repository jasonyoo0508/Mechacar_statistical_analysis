# Mechacar_statistical_analysis



## Linear Regression to Predict MPG
Regression results

- 3 questions

**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**

In the dataset, the most significant variables/subjects, which are the variables that identify non-random effect on the MPG MechaCar were Vehicle_length and Ground_clearnace. 
Both of the variables have a very small p-value. This mean that they had a high level of significance. 

**Is the slope of the linear model considered to be zero? Why or why not?**

By reviewing the small p-values = 5.35 x e-11, we can conclude with high possibility that the slope of the linear model isn't 0 & null hypothethis rejected.  

**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**

The 'multiple-R-squared' value is 0.7149, so it is bold that the linear model successfully displays (71%+) our dataset. It could improve though. 

![linear_regression_image1](https://user-images.githubusercontent.com/89154507/143669591-ce84cf51-f255-438c-a8e9-136cb447551a.png)


## Summary Statistics on Suspension Coils

The overall variance in the 'total summary data' shows 62.29, which is under 100 PSI (good order), LOT #3 (individual) has a variance of 170.28, which is well over the line of 100. 

![Image_output_image2](https://user-images.githubusercontent.com/89154507/143669678-17184584-07d2-4460-bf66-6544790506c3.png)


## T-Tests on Suspension Coils

The one-sample t-test on Lot 3 PSI vs. the overall mean returns a p-value higher than 0.05, so we fail to reject the null hypothesis and determine that the true mean may equal the overall population mean.

Lot 2 and 3 has a very low p-values, and by running this same test, we would reject the null hypothesis. In this case, we are 95% confident that the means are different than the population mean.
![Lot_findings](https://user-images.githubusercontent.com/89154507/143669919-64372ce4-1288-414f-a0fd-1870f879f5aa.png)


## Study Design: MechaCar vs Competition

**What metric or metrics are you going to test?**

Using following matrix.. 
* Data to be all numeric values, samples to be large as possible, samples to be randomly selected (Data), and the variance of data to be similar.

**What is the null hypothesis or alternative hypothesis?**

Null Hypothesis is that all of the cars in the same class have the same fuel efficienies. The Alternative Hypothesis is that they are not all the same.



**What statistical test would you use to test the hypothesis? And why?**

I would use the T-Test to compare the dataset with the competitors. The T-test was already used for this module analysis, and it has apt prediction methods needed to take the next steps for improvement. 


**What data is needed to run the statistical test?**
The base p-value would be set at 0.05. If the p-value is smaller than 0.05, it would provide an evidence that the null hypothesis 'could' be rejected. The prediction would also provide that the MechaCar provide better fuel efficiency than the competitors MPG. There would be a room for error and some room for improvements on efficiency, but it would happen at least 95%+ of the time. 

