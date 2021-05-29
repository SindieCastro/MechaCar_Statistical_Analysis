# MechaCar_Statistical_Analysis
## Background

The client is asking for a statistical analysis of MechaCar due to its production troubles which is blocking the manufacturing team's progress.

## Purpose

The purpose of this analysis is to predict the mpg of MechaCar prototypes, collect summary statistics on the pounds per square inch(PSI) of the suspension coils, and determine if the manufacturing lots are statistically different from the mean population.

## Linear Regression to Predict MPG

**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**
Image 1 shows that the vehicle weight, spoiler angle, and the AWD provided a non-random amount of variance to the mpg values in the dataset.

**Image 1: Variables/Coefficients**

![Image 1](https://user-images.githubusercontent.com/78306719/120069119-d5614780-c049-11eb-8972-9db3a4ea1a4a.PNG)

**Is the slope of the linear model considered to be zero? Why or why not?**
Image 2 shows that the slope of the linear model is p-value: 5.35e-11; therefore, the slope is not considered zero and the null hypothesis is rejected.

**Image 2: P-Value and R-Squared**

![Image 2](https://user-images.githubusercontent.com/78306719/120069123-dabe9200-c049-11eb-8447-81e691db6af0.PNG)

**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**

This linear model predicts mpg of MechaCar prototypes effectively as shown on the Image 2 above with an R-squared of 0.719 (71%) which is higher than 50%.

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The current manufacturing data meets this design specification for manufacturing lot 1 and 2 but not for lot 3. Image 3 shows that the variance for lot 3 is more than 100 at 170.29 while lot 1 and 2 are less than 10 at .97 and 7.46. 

**Image 3: Lot Summary**

![Lot Summary](https://user-images.githubusercontent.com/78306719/120069644-a4cedd00-c04c-11eb-9053-37c3351375df.PNG)

## T-Tests on Suspension Coils

Image 4 shows there is not enough evidence to reject the null hypothesis. The two means are statistical similar; therefore, suspension coils across all lots are very close to the PSI of the population. Image 4 also shows the p-value of 0.06028 which is greater than 0.05; thus, the data is considered a normal distribution.

**Image 4: All Lots**

![all lots t test](https://user-images.githubusercontent.com/78306719/120069201-3db02900-c04a-11eb-80c6-551bec496a12.PNG)

Image 5 shows there is not enough evidence to reject the null hypothesis. The two means are statistical similar; therefore, Lot 1 suspension coils are very close to the PSI of the population. Image 5 also shows the p-value of 1 which is greater than 0.05; thus, the data is considered a normal distribution.

**Image 5: Lot 1**

![Lot 1](https://user-images.githubusercontent.com/78306719/120069220-5b7d8e00-c04a-11eb-880b-b1427339ecdf.PNG)

Image 6 shows there is not enough evidence to reject the null hypothesis. The two means are statistical similar; therefore, Lot 2 suspension coils are very close to the PSI of the population. Image 6 also shows the p-value of .6072 which is greater than 0.05; thus, the data is considered a normal distribution.

**Image 6: Lot 2**

![Lot 2](https://user-images.githubusercontent.com/78306719/120069267-997ab200-c04a-11eb-8b84-4e25ca71bcef.PNG)

Image 7 shows that there is sufficient statistical evidence that the null hypothesis is not  true; therefore, the null hypothesis is rejected. There is a statistical difference between the Lot 3 suspension coils and the PSI of the population. Image 7 also shows the p-value of .04168 which is less than 0.05; thus, the data is considered a skewed distribution.

**Image 7: Lot 3**

![Lot 3](https://user-images.githubusercontent.com/78306719/120069289-bf07bb80-c04a-11eb-91b3-5266352390b3.PNG)

## Study Design: MechaCar vs Competition

The study design would compare MechaCar safety ratings against the competition within the last 5 years. 

**What metric or metrics are you going to test?**

The dependent variable would be the safety ratings while the frontal crash test results, side barrier crash test results, side pole crash test results would be the independent variables.

**What is the null hypothesis or alternative hypothesis?**

**Null hypothesis:** If MechaCar or the competition score e a 5 star safety rating, they will score a 5 star for the frontal crash test. 
**Alternate hypothesis:** If MechaCar or the competition do not score a 5 star safety rating, they will not score a 5 star for the frontal crash test. 

**What statistical test would you use to test the hypothesis? And why?**

A t-test would be used to test the hypothesis. The p-value would also be computed to get the significance level. Since this is a critical decision-making hypothesis due to testing the safety of cars, the cut off for the significant level would be smaller such as 0.01 or 0.001.

**What data is needed to run the statistical test?**

The safety ratings for MechaCar and the competition is needed to run the t-test. This includes the test results for the frontal crash test, side barrier crash test, and the side pole crash test.
