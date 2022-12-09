# California Housing

## by Ojikutu Aisha


## Dataset

The dataset contains 20,640 observations and 10 features. The features are listed below:
1. longitude
2. latitude
3. housing_median_age (Years)
4. total_rooms
5. total_bedrooms
6. population
7. households
8. median_income (USD)
9. median_house_value (USD)
10. ocean_proximity

The dataset can be found [here](https://www.kaggle.com/datasets/camnugent/california-housing-prices?select=housing.csv) on the page including the data features.

## Summary of Findings

In my research, I discovered that there is a high positive correlation between income and house value, meaning that a household's average income is related to the worth of the home they live in. I also learned that inland homes are less expensive than those on the ocean. Regardless of age, homes near the seaside and the Bay region tend to be more expensive.

There were 207 empty observations was dropped in the dataset. Using the categorical feature `ocean_proximity`, most of the houses in the dataset are less than an hour to the ocean. During exploration, there is a linear relationship between the `median_income` and `median_house_value`. I also found out that `housing_median_age` does not have any relationship with `median house_value`. Another unexpected finding is that the 'median house value' as shown on the map is higher the closer the homes are near the 'ocean' or 'bay area'.

## Key Insights for Presentation

I utilized a scatter plot to illustrate the link between "median income" and "median house value" for the presentation. The distribution of "median income," "housing median age," and "median house value" was then displayed.
After that, I create a chart that displays the houses' spatial distribution, location, and value.