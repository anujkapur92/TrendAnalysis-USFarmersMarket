# Trend Analysis - US Farmers Market
Analyzed the data provided by the USDA website (https://www.ams.usda.gov/local-food-directories/farmersmarkets). It lists multiple farm vendors who sell their products directly to the consumers at a common, recurrent physical location. Information such as name of the market, its location, product offerings, operating times and accepted forms of payment has been provided.

## Packages required
dplyr, usmap, ggplot2, lubridate, openintro, treemap; all downloadable from CRAN

### Pre-requisites
R and R Studio

## Distribution of Farmers Market
Used the usmap library to show the distribution of farmers market throughout the United States.

![alt tag](https://user-images.githubusercontent.com/42359693/68337591-d240e800-00ae-11ea-9ee2-10700ecd4963.png)

Throughout the period from 2010 to 2019, the state of California has the maximum number of farmer markets (759 markets), followed by the state of New York (674 markets) and then the state of Michigan (343 markets). The state of Virgin Islands has the least number of farmer markets (4 markets).

## Year-wise evolution
Split the season's dates to pick the date when the season starts and then display the evolution of market over the years 2010 - 2019.

![alt tag](https://user-images.githubusercontent.com/42359693/68338761-319ff780-00b1-11ea-9d75-70250e3c379a.png)

There has been a substantial increase in the farmer markets after 2012, peaking at the year of 2014 and then at the year of 2016, but has been declining since then.

##Month-wise seasonality effect
Used the ggplot library to show the effect of seasons on the farmers market throughout the year.

![alt-tag](https://user-images.githubusercontent.com/42359693/68339254-36b17680-00b2-11ea-98bb-2d606ec51734.png)

The months of May and June show the highest number of farmer markets throughout the year. We can infer that the Summer season has a positive effect on the count of farmer markets, possibly due to the weather’s effect on the harvesting yield of the crops.

