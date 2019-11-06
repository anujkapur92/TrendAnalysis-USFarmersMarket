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

## Month-wise seasonality effect
Used the ggplot library to show the effect of seasons on the farmers market throughout the year.

![alt-tag](https://user-images.githubusercontent.com/42359693/68339254-36b17680-00b2-11ea-98bb-2d606ec51734.png)

The months of May and June show the highest number of farmer markets throughout the year. We can infer that the Summer season has a positive effect on the count of farmer markets, possibly due to the weather’s effect on the harvesting yield of the crops.

## Product Types
Used the ggplot library to show the number of products being supplied by the farmers market.

![alt-tag](https://user-images.githubusercontent.com/42359693/68339446-9740b380-00b2-11ea-9d6f-cb94792d2ae0.png)

There are 30 types of products being sold in the farmers market. The highest sale in numbers was made by vegetables (5792), followed by bakedgoods (5251) and then by fruits (4905). The least sale in count was made by tofu (235).

Treemap library is used to create a treemap of the different product types.

![alt-tag](https://user-images.githubusercontent.com/42359693/68339677-0c13ed80-00b3-11ea-8303-e9411177b594.png)

The products of the entire farmers market can be sub-grouped into multiple types. We choose to divide them into the following 3 types:
1.	Plant-based group
2.	Animal-based group
3.	Others (Neither plant-based nor animal-based)

![alt-tag](https://user-images.githubusercontent.com/42359693/68339854-5bf2b480-00b3-11ea-968d-ca326d68de45.png)

The plant-based group sells the maximum number of products in the farmers market, the least being sold by animal-based group, in the duration of 10 years.

## Payment Methods
Used the barplot to display the different types of payment methods being provided by the farmers market.

![alt-tag](https://user-images.githubusercontent.com/42359693/68339947-89d7f900-00b3-11ea-8ec9-b9a4b28d9c64.png)

‘Payment by credit’ is the most provided mode of payment throughout the farmers market in a span of 10 years.

Used the grouped bar plot to show the comparison of different payment methods provided by the Farmers market in various regions across the United States.

![alt-tag](https://user-images.githubusercontent.com/42359693/68340157-e1766480-00b3-11ea-8e33-985365cf4fd0.png)

Throughout all the regions of United States in a span of 10 years, ‘Payment by credit’ is the most provided modes of payment in the farmers market.

## Acknowledgements

R Core Team (2013). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. URL http://www.R-project.org/.

R Packages used : dplyr, usmap, ggplot2, lubridate, openintro, treemap