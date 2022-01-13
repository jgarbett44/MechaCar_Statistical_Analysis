# MechaCar: Statistical Analysis

## Linear Regression to Predict MPG

See D1 Screenshot - https://github.com/jgarbett44/MechaCar_Statistical_Analysis/blob/39bfb18fb52bd37625607f0cc691184b0fab901c/D1_Screenshot.png

According to our results, vehicle length and ground clearance provided non-random variance to the mpg in the dataset.

The p-value of our linear regression analysis is 5.35e-11, which is smaller than our assumed significance level. We can reject our null hypothesis; **the slope of our linear model is not zero**.

Our r-squared value is .72, showing a strong positive correlation, so it will predict mpg effectively.

## Summary Statistics on Suspension Coils

See D2 Screenshot - https://github.com/jgarbett44/MechaCar_Statistical_Analysis/blob/39bfb18fb52bd37625607f0cc691184b0fab901c/D2%20Screenshot.png

Our suspension coil specifications require that the variance must not exceed 100 pounds per square inch. Looking at the total summary, variance is 62, well below 100, meeting our requirement. However, the lot summary shows "Lot 3" with a variance of 170. Therefore, the current data does not meet the specifications for each lot individually.

## T-Tests on Suspension Coils

See All_Lots Screenshot - https://github.com/jgarbett44/MechaCar_Statistical_Analysis/blob/39bfb18fb52bd37625607f0cc691184b0fab901c/All_Lots.png

Assuming our significance level was the common 0.05 percent, our 0.06 p-value is below that level. Therefore, the two means are not statistically similar.

See Individual_Lots Screenshot - https://github.com/jgarbett44/MechaCar_Statistical_Analysis/blob/39bfb18fb52bd37625607f0cc691184b0fab901c/Individual_Lots.png

Lots 1 and 2 p-value is above our significance level and we would state that the two means are statistically similar. We do not have sufficient evidence to reject the null hypothesis.

## Study Design: MechaCar vs Competition


