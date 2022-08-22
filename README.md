## Topic

Our group is interested in the impact of the COVID pandemic on the Job Market, with special attention to the LGBTQ population. We look at whether employment in cities with more LGBTQ populations is more greatly affected by Covid Cases. We also controlled the predictors that we found to be significantly correlated with employment to see if the effect from the LGBTQ population still persists. 

## Results

Here, we are making a general observation on how emplyment and COVID new cases change over the time in the United States. 
<img src="https://github.com/JunoWuu/Datathon/blob/master/time_series.png">

Then, we run an VAR model on both of those time series and get the coefficients of different MSAs. We use those to create an interactive map. 
<img src="https://github.com/JunoWuu/Datathon/blob/master/heatmap.png">

In addition to that, we also created a TSA graph. 

<img src="https://github.com/JunoWuu/Datathon/blob/master/tsa_forecast.png">

Most importantly, we find that LGBTQ population can significantly predict the coefficient(COVID'S affect on employment) even after controlling to related variables. 

<img src="https://github.com/JunoWuu/Datathon/blob/master/significance.png">

These findings imply that cities with different LGBTQ population’s employment are affected by COVID differently. It is possible that LGBTQ population are more severely impacted by COVID in their career. It warns us that more study and attention to be paid to this group especially when COVID is not over yet.  
