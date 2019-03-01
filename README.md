I) Design

The project sought to model the median income level of residents without a Bachelor’s degree in a given geographic region in order to determine what public policy decisions could be made to help increase the income levels of these populations. In this case, it was decided to use data points from the county level, since there were both enough data points to be sufficiently numerous and enough data points that did not have incomplete information.

The raw data, as mentioned below was compiled using a variety of methods, including web scraping, and then transformed into the desired values and units for the regression analysis.
The data was then analyzed through a multitude of regression models, beginning with a simple Linear Regression, which ended up being the ultimate result. Next, the data from the Linear Regression was cross-validated through a train-test split, which showed a relative goodness of fit of the model with little over- or under-fitting. Finally, due diligence checks were performed on the model to see if any other types of regression, such as Ridge or Lasso Regression would be better fits for the model; however, it was found that there was no improvements over the standard Linear Regression model.

II) Tools

A) Python (Programming Language)
1) Pandas (Data Analysis)
2) Numpy (Data Analysis)
3) BeautifulSoup4 (Web Scraping)
4) Selenium (Web Scraping)
5) Statsmodels (Modeling)
6) Scikit-learn (Modeling)
7) Matplotlib (Modeling)
8) Seaborn (Modeling)

B) Google Drive (Presentation)

III) Data

The table below depicts each feature used in the model, its specific context, and its source.



The overall results of the regression showed a moderate predicting power with an R2 of 0.61 and an F-Statistic of 460. These results combined mean that the model can capture around 61% of the variation between the income levels of those without a Bachelor’s Degree across various communities and that the null hypothesis that none of the variables is statistically significant is rejected.

IV) Next Steps

While the project was successful at returning a moderately accurate estimate, there are still a variety of other factors that would ideally go into the next refinements of this project. One of them would be to return more in-depth analyses on the different sub-groups within a population, including different ages, different genders, and different races or ethnicities. In addition, the ideal project would include a breakdown of the different counties to find the differences between different cities and towns within each county.