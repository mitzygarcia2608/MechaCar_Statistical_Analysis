# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
 # Results

![image](https://user-images.githubusercontent.com/111592990/217530864-9a892fed-06f4-473f-bb94-3b508c8e69c9.png)

•	The two Variables that are the most likely to provide a non random amount of variance are vehicle length and ground clearance . 

•	The null hypotheses is that the slope is zero,The P-value isl5.35e-11.  Since this number is less than the standard significance lever of 0.5 mean that there is sufficient evidence to say that the null hypotheses is not true.

•	The R-squared value of 0.7149 means that the model will be correct 72% percent of the time.
## Summary Statistics on Suspension Coils
 # Statisics by lot
![image](https://user-images.githubusercontent.com/111592990/217533229-07c5b07c-f754-4f7c-8dda-e85a1db85ce4.png)

•	Statistics broken down by lot show that 2 of the 3 lots meet design specifications for the pounds per square inche.(lot1 and lot 2)

# Total Summary

![image](https://user-images.githubusercontent.com/111592990/217533423-6ded7f45-685c-479e-9e74-5343b7aee237.png)

•	From the summary table we can conclude that the “Var_psi” is 62.29 meaning that the current design meets the necessary specifications.

## T-Tests on Suspension Coils

# Results

![image](https://user-images.githubusercontent.com/111592990/217534974-8e761789-99f7-4c89-8bcb-1f16157b25b3.png)

![image](https://user-images.githubusercontent.com/111592990/217535042-5e438dc6-535b-4f24-b78a-3cb05ec5ba26.png)

![image](https://user-images.githubusercontent.com/111592990/217535110-1d3117c1-d920-4ccb-8812-2428952167d6.png)

•	The p -values for lot1 and lot2 were both greater than 0.5 meaning we failed to reject the null hypotheses

•	The p value for lot3 is less than 0.5 meaning that we have enough statistical evidence that our null hypothesis is not true

## Study Design: Mechacar vs Competition
An additional study that could be run to compare MechaCar vs Competition would be on fuel efficiency.
Necessary metrics:

•	What metric or metrics are you going to test?
-metrics that I would test are maintenance   cost and vehicle weight

•	What is the null hypothesis or alternative hypothesis?
-Null hypothesis: would be that competition has higher costs with high vehicle weight
-Alternative Hypothesis : that the Mechacar has high costs with higher vehicle weight

•	What statistical test would you use to test the hypothesis? And why?
-statical test would be lm() and t-test.

•	What data is needed to run the statistical test?
-weight of vehicle , type of vehicle , age of vehicle and maintenance  costs


