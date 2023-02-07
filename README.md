# AirBnB price prediction in USA

## Why is this an intersting project?
* Pricing is one of the most important decisions that hosts need to make to gain profits.
* The prediction exercise here provides a method to predict prices for properties around the same area with similar conditions.
* It will give the hosts a better idea of the property’s market values.
* Airbnb can retain hosts, expand its business, and eventually increase revenues.

#### Data Source : https://www.kaggle.com/datasets/kritikseth/us-airbnb-open-data

## Methodology
* Data preprocessing: Drop missing data and remove outliers
* Exploratoy Data Analysis:
  * Create histograms and correlation matrix for numeric features
  * Visualize listings and prices distributions across states
* Data Modeling:
  * Use linear regression, XGBoost and multivariate adaptive regression splines to predict prices
  * Compare the model performances by RMSE, MAE and R2 Score

## Outcomes
* Price is most positively correlated with host listings count and availabilty in the year. 
* So, more listing a host has, the price is higher and if the place is more available, you can charge more!

<img src="https://user-images.githubusercontent.com/31558571/217119991-a0806cdd-fd58-42c7-ad50-000d6303911d.png"  width="60%" height="30%">
<img src="https://user-images.githubusercontent.com/31558571/217120001-250b52ab-044a-426f-bfbc-3bbf1d8e84bb.png"  width="60%" height="30%">
Looks like renting an entire appartment is more attractive over other options!
<img src="https://user-images.githubusercontent.com/31558571/217120192-3d859732-845c-4ee2-a5bb-00c287b4544e.png"  width="60%" height="30%">

## Conclusion

* Predicted prices with three models: linear regression, multivariate adaptive regression splines, and XGBoost.
* XGBoost has the best performance with the highest R square and lowest RMSE and MAE.
* Room types and city are the key predictors.

