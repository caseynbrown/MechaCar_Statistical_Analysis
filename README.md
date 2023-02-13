# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/115745142/218355097-e5b42785-149a-4e24-9e63-b00bc4d85304.png)

![image](https://user-images.githubusercontent.com/115745142/218355155-6410f871-77a7-4bbd-bdfd-c49cc7b08fc5.png)

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The vehicle_length and ground_clearance provided non-random amounts of variance. 

### Is the slope of the linear model considered to be zero? Why or why not?
With a p-value of 5.31e-11, being smaller than the assumed significance value of 0.05, suggesting there is enough evidence to reject the null hypothesis and indicating that the slope of the linear model is not zero. 

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The r-squared value is 0.7149, demonstrating that 71.49% of the time, the model will predict mpg correctly. Based on this number, it would seem that it's effective but there is still room to grow. 

## Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/115745142/218356466-ddbbac47-b353-4fef-9459-b407a6f81152.png)

![image](https://user-images.githubusercontent.com/115745142/218356491-1dade648-350c-461c-980c-fea179e43511.png)


### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
The variance for all lots was 62.29, which was less than the required 100. When broken down by lot, Lot 3 had a variance of 170.29, which was well above the 100. Lot 1 had a variance of 0.98 and Lot 2 had a variance of 7.47, both significantly below the requirement. 

## T-Tests on Suspension Coils

![image](https://user-images.githubusercontent.com/115745142/218357327-68ffe885-6fa8-4f17-9bd2-0c0f52f65c34.png)

![image](https://user-images.githubusercontent.com/115745142/218357344-e730d416-3c9a-4958-86d4-19e7c86ec5e1.png)

![image](https://user-images.githubusercontent.com/115745142/218357359-e5e42cc5-a78f-437f-9519-bbb46ebf9c14.png)

![image](https://user-images.githubusercontent.com/115745142/218357376-5dc829a2-88f1-4eff-81b8-12fa8f580f89.png)

The first sample t-test on all manufacturers had a p-value of 0.06, which is higher than the significance level of 0.05, meaning we cannot reject the null hypothesis and the two are statistically similar. 

The t-test on Lot 1 had a p-value of 1, again higher than the significance level of 0.05, meaning we cannot reject the null hypothesis and the two are statistically similar.

The t-test on Lot 2 had a p-value of 0.61, again higher than the significance level of 0.05, meaning we cannot reject the null hypothesis and the two are statistically similar.

The t-test on Lot 3 had a p-value of 0.041, lower than the significance level of 0.05, meaning we can reject the null hypothesis and the two are not statistically simiar. 

## Study Design: MechaCar vs Competition

A statistical study that could be done to compare the performance of MechaCar vehicles against the performance of vehicles from other manufacturers could be looking at the relationship of factors in which affect the consumer. 

### What metric or metrics are you going to test?
I would test the cost of the vehicle, fuel efficiency, and safety ratings. 

### What is the null hypothesis or alternative hypothesis?
My null hypothesis would be that the vehicles would have the same scores in these metric compared to the other manufacturers, and the altnernative hypothesis would be the opposite. 

### What statistical test would you use to test the hypothesis? And why?
1-tailed t-tests could be used in order to see values for MechaCar compared to the other manufacturers. 

### What data is needed to run the statistical test?
We would need a list of the other manufacturers along with the cost of the vehicles, fuel efficiency for each, and the safety ratings. 
