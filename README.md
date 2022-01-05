# Zillow Time Series
Authors: Matthew Reinhart, Jerry Vasquez and Wahaj Dar

# Overview


# Business Objective
This project posits that we are consultants for a real estate company. We have been asked what are the five best zipcodes in the Metropolitan are of Phoenix to invest in for this company. We decided to look at growth to determine which should be considered the five best.

# Data
This project uses data from the [Zillow Research Page](https://www.zillow.com/research/data/) database. Which contains approximately 15,000 lines with basic information such as city, state, county, size rank from April 1996 - April 2018. We focused in on Zipcodes from the Phoenix area over the last 10 years.

# Methodology
Instead of using the given value column to model which zipcodes would be best we created a growth column in order to see how they grow on a month to month basis.
After creating that column we limited the data to the top 10 zipcodes in the Phoenix metropolitan area and from there did extensive modeling to find the five zipcodes that would return the highest growth in the area.

We then use an iterative approach to build time-series models for each zipcode . We utilize hyperparameter tuning, cross-validation and forecasting to select the highest zipcodes.

# Results



