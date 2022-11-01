# DSI-Project-2-Ames-Housing-Data
For General Assembly DSI course

## Problem Statement
As a data-driven real estate company, we wish to determine the most important characteristics that affect housing prices in Ames, Iowa.

#### Method: 
To fit a regression model to determine the important determinants of Ames housing sale prices, and identify the most important variables.

#### Questions to answer:
- Which features appear to add the most value to a home?
- Which features hurt the value of a home the most?
- What are things that homeowners could improve in their homes to increase the value?
- What neighborhoods seem like they might be a good investment?

## Data Dictionary

The [data description](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt) is found here.

## Kaggle Submission



## Discussion

#### Key Insights

Top significant variables with positive coefficients:
- Neighborhood_GrnHill
- Neighborhood_StoneBr
- MS SubClass_30
- MS SubClass_45
- MS SubClass_75
- Garage Type_NA
- Exter Qual
- Overall Qual
- Kitchen Qual
- Garage Cars

Top 10 most significant variables with negative coefficients: 
- Roof Style_Mansard
- Neighborhood_NWAmes
- Neighborhood_Gilbert
- Neighborhood_SawyerW
- Yr Sold
- Neighborhood_OldTown
- Neighborhood_NAmes
- Bedroom AbvGr

#### Limitations 
Every model has its limitations. The limitations for this model include:
- Dataset was provided only for a limited time period. It is difficult to predict housing prices on the future because it is heavily dependent on the economy in general.
- Model probably cannot be generalised across USA cities because each city has different population size, income levels, etc. We would need to have to adjust the Sale Prices to the income levels and population of each state after finding out the 2 variables’ relationship with housing Sale Price.

#### Possible improvements to the model
- Can explore outliers to see the characteristics of houses are undervalued.
- Can explore interaction variables (e.g. Basement Quality x Basement Size, and Subclass x Neighbourhood)
- Monthly analysis can be done to find the best month to sell a house for the real estate company. Month should be treated as a categorical variable.
