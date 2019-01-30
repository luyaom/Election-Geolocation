# Election-Geolocation

1.1 Downloaded 2008 - 2012 election result data from https://github.com/tonmcg/US_County_Level_Election_Results_08-16.git, and preprocessed the data. 

1.2 Scraped census data from https://censusreport.org, and preprocessed data (calculate ratio or normalize). 

2 Visualized election result (html files)

3.1 Built census model
1) AUC is surprisingly high, greater than 0.9. 
2) variables make cense: class_model_importance_v1.csv ranked by variable importance, check variable is positive or negative by ratio. For example, to predict democracy, they are less likely to be white, but minorities; less likely to be middle-class, but either rich or poor; less likely to be married-couple family; more likely to live in counties with larger population; more likely to have a higher education level. 

