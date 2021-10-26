Data used for pharmacological tests on mice is cleaned, and statistics for several predictors are found, utilizing pandas.

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed
and measured. The purpose of this study was to compare the performance of the drug of interest, Capomulin, versus the other treatment regimens.

Several analysis were performed to create visualizations to find key indications including:
> Summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen

> Bar plot that shows the total number of measurements taken for each treatment regimen throughout the course of the study

> Pie plot that shows the distribution of female or male mice in the study

> Using Matplotlib, a box and whisker plots the final tumor volume for all four treatment regimens and highlight any potential outliers

> Scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen

> Calculating the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment, a linear regression model is plotted on top of the previous scatter plot

Important factors of the mice were dependent upon differing age, weight, and gender.




![Tumor_Volumes](https://user-images.githubusercontent.com/80362935/138531573-1d23a45e-0b4b-4187-96c7-0e34a1367025.png)

<img width="459" alt="Capomulin Treatment" src="https://user-images.githubusercontent.com/80362935/138972173-3265ea64-0eb0-4d22-98c6-26641069e2fc.png">

<img width="474" alt="Avg Tumor Vol vs Avg Weight" src="https://user-images.githubusercontent.com/80362935/138972195-088f713e-06a1-43e9-91a1-ad5b7ebde998.png">

![Tumor_Correlation](https://user-images.githubusercontent.com/80362935/138531578-d8ea9c91-62b3-4d16-b3b4-523b246c9cd3.png)
