# Seoul Bike_Sharing_Demand_Predction

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes



# Conclusion

This study focused on predicting the bike sharing demand using given dataset. Regression techniques like Lasso Regression Ridge Regression to predict the trip duration. This statistical data analysis shows interesting outcomes in prediction method and also in an exploratory analysis.

During the time of our analysis, we initially did EDA on all the features of our datset. We first analysed our dependent variable, 'Rented Bike Count' and also transformed it. Next we analysed categorical variable and dropped the variable who had majority of one class, we also analysed numerical variable, found out the correlation, distribution and their relationship with the dependent variable. We also removed some numerical features who had mostly 0 values and hot encoded the categorical variables.

Next we implemented 3 machine learning Regression algorithms , Lasso Regression, Ridge Regression, Elasticnet Regression. We did hyperparameter tuning to improve our model performance.

No overfitting is seen.

Random forest Regressor and Lasso gridsearchcv gives the highest R2 score

We can deploy this model.

The experimental result shows that:

Heat map shows Temperature and
Dew point temperature is highly correlated.

Bike is rented when functioning day
is there otherwise not.

More number of bike are rented in
year 2018

Most number of bike are rented 17
to 19th hour of the day and in morning at 8 pm. ost number of bikes are rented on 6th and 9th day of month.

Most numbers of Bikes were rented in
summer, followed by autumn, spring, and winter. May-July is the peak Bike renting Season, and Dec-Feb is the least preferred month for bike renting.

Most number of bikes are rented on
Working day instead of holiday.

This is evident from EDA analysis where bike
demand is more on weekdays, working days in Seoul
