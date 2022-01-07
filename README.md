# Zillow Time Series
Authors: Matthew Reinhart, Jerry Vasquez and Wahaj Dar

# Business Objective
This project posits that we are consultants for a real estate company. We have been asked what are the five best zipcodes in the Metropolitan are of Phoenix to invest in for this company. We decided to look at growth to determine which should be considered the five best.

# Data
This project uses data from the [Zillow Research Page](https://www.zillow.com/research/data/) database. Which contains approximately 15,000 lines with basic information such as city, state, county, size rank from April 1996 - April 2018. We focused in on Zipcodes from the Phoenix area over the last 10 years.

# Methodology
Instead of using the given value column to model which zipcodes would be best we created a growth column in order to see how they grow on a month to month basis.
After creating that column we limited the data to the top 10 zipcodes in the Phoenix metropolitan area and from there did extensive modeling to find the five zipcodes that would return the highest growth in the area.

We then use an iterative approach to build time-series models for each zipcode . We utilize hyperparameter tuning, cross-validation and forecasting to select the highest zipcodes.

# Results
After comparing the Zipcodes in the Phoenix,Arizona area we came to the conclusion that the best five zip codes were:
85258 with a forecasted growth rate of 148.97%
85018 with a forecasted growth rate of 7.65%
85377 with a forecasted growth rate of 1.33%
85262 with a forecasted growth rate of 1.06%
85263 with a forecasted growth rate of .25%
# Conclusion
In conclusion The five Zipcodes we recommend above are the ones we would suggest you focus on in the Phoenix are and specifically those first two where there are more significant results.

The results of our time-series models were pretty encouraging based on the time frame we had to work on this project. We were able to make the data workable and build useable models with significant results.

If we did have more time we would have liked to look at the whole state of Arizona however we did not have time for that here so in the future we may revisit and analyze further.
# Repository Structure
```
├── README.md                           <- The top-level README for reviewers of this project
├── Main_Notebook.ipynb                 <- Narrative documentation of analysis in Jupyter Notebook
├── Zillow_Time_Series.pdf              <- PDF version of project presentation
├── time_series_functions.py            <- Python script with functions to be called in MAIN Notebook
├── Zillow Data                         <- Raw .csv source file from Zillow
├── Final_Notebooks                     <- Separate Notebooks showing completed models on each Zipcode
└── Obselete                            <- Older Notebooks that aren't necessary for final deliverables
```

