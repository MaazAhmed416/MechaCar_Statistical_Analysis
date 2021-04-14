## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/76402559/114760781-b32b9880-9d2d-11eb-8fa2-6d75152fd6c3.png)

Vehicle_weight, spoiler_angle and AWD provided a non random-amount of variance to the mpg values in the dataset
The slope of the linear is not considered zero. This is due to the fact that the p-value is 5.35e-11, which is lower than the significance level of 0.05
The multiple R squared amount is 0.7149 which tells us that 71.49% of the time, the model predicts mpg of MechaCar prototypes effectively

## Summary Statistics on Suspension Coils
![image](https://user-images.githubusercontent.com/76402559/114767976-4ff23400-9d36-11eb-9a15-aea78465bd14.png)

The current manufacturing data meets the design specification for all manufacturing lots in total. The variance is 62.29356 which is under 100

![image](https://user-images.githubusercontent.com/76402559/114768384-c727c800-9d36-11eb-941d-c7155e0b1ba6.png)

The manufacturing data meets the design specification for lots 1 and 2. The variances are well below 100 for these lots. However, Lot3 does not meet the specification and has a variance of 170.286 which is well above 100

## T-Tests on Suspension Coils
![image](https://user-images.githubusercontent.com/76402559/114770298-4b7b4a80-9d39-11eb-9a95-bf9e369f5a0f.png)

![image](https://user-images.githubusercontent.com/76402559/114770377-60f07480-9d39-11eb-86f4-c13fe9192698.png)

![image](https://user-images.githubusercontent.com/76402559/114770449-75cd0800-9d39-11eb-9dc0-48e91dd3f228.png)

![image](https://user-images.githubusercontent.com/76402559/114770512-87aeab00-9d39-11eb-9e71-04770eb76d09.png)

Collectively, the p value for the PSI is 0.06028 which is greater than the significance value of 0.05 and therefore we can conclude that it is not different from the mean population PSI results. Also, when looking looking at the data grouped by manufacturing lot, Lot 1 has a p value of 1 and Lot 2 has a p value of 0.6072 which means they are also not statistically different from the mean population PSI results. However, Lot 3 has a p value of 0.04168 which is below the significance value which tells us that it is statistically different from the mean population PSI results.
