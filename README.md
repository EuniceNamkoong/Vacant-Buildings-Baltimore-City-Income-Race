# Analyzing the Distribution of Vacant Buildings in Baltimore City
How can we better understand the relationship between vacant buildings and geographic distribution of race and income? 

The sections below will cover the following: 
* Challenge/Problem: History of Baltimore infrastructure and problems residents have experienced  
* Solution: Data analysis of number of vacant houses by neighborhood based on race and median income 
* Suggestion: Application of data findings to Baltimore City legislation 

## Why is this a Challenge/Problem? 
The high volume of vacant buildings present a [huge safety and public health problem in Baltimore City](https://www.marketplace.org/2020/07/08/why-cant-baltimore-solve-vacant-housing-problem/). Not only is this detrimental to quality of life for residents but there have been documented cases of deteriorating vacant buildings collapsing on pedestrians. Additionally, with more people leaving Baltimore City, there are large swaths of 10-20 row houses being hollowed out and 1 in 3 houses vacant in West Baltimore. Furthermore, we will be exploring how this issue is related to median income and race due to similiarities between the geographical locations of vacant houses and the Black Butterfly. 

![black butterfly map](https://github.com/EuniceNamkoong/Vacant-Buildings-Baltimore-City-Income-Race/blob/main/Black%20Butterfly%20Map.JPG)

The map above shows the ["Black Butterfly"](https://apps.urban.org/features/baltimore-investment-flows/), a description of the butterfly wing shape of segregated black communities dispersed across Baltimore City's eastern and western halves. The ["White L"](https://ncrc.org/the-black-butterfly/) is comprised of high-income neighborhoods located around Inner Harbor to the North. 

![vacant house map](https://github.com/EuniceNamkoong/Vacant-Buildings-Baltimore-City-Income-Race/blob/main/Vacant%20Houses%20Map.JPG)

When the vacant buildings are mapped geographically by neighborhoods, they similarly form the shape of the Black Butterfly.

## Your Solution


![insert2](https://github.com/EuniceNamkoong/Vacant-Buildings-Baltimore-City-Income-Race/blob/9f42f1ec0b3f6defb37d1b9235fab7265b64b839/BaltimoreCityMedianIncomeNeighborhood.png) 

This graph was created using a Pivot Table to understand how median household income is distributed across Baltimore City by neighborhoods. The top 5 neighborhoods are located in north, south, and central Baltimore and the bottom 5 neighborhoods are located in west and southeast Baltimore. This suggests that there are wealth inequalities and distribution is not equal across the neighborhoods and districts. 

![insert1](NeighborhoodVacantBuildings.png)

Using the total number of vacant buildings in Baltimore City by neighborhood data, a Pivot Table was created to analyze the stark discrepancy between neighborhoods in the eastern/western halves vs. north/south. The top 5 neighborhoods with the highest total number of vacant buildings are located in East, northern, southwestern, and southeastern Baltimore. The bottom 5 neighborhoods are located in the north or southeast. It is important to note that some neighborhoods are grouped together due to the combination of several data sets which may slightly affect which district the neighborhoods are grouped under. 


![insert3](https://github.com/EuniceNamkoong/Vacant-Buildings-Baltimore-City-Income-Race/blob/main/BaltimoreCityMedianIncomeScatterGraph.png)

To plot the vacant buildings and median household income data sets together, a scatterplot was used. We can see that the trendline suggests a general inverse relationship. As the median household income increases, the total number of vacant buidings are less likely to be a prominent issue in the high-income neighborhoods. 


![insert4](VacantBuildingsBlackResidents.png)

As the percent of Black residents in the neighborhoods increases, the total vacant buildings shows a general upwards trend. 

![insert5](VacantBuildingsWhiteResidents.png)

As the percent of White residents in the neighborhoods increases, the total vacant buildings shows a general downwards trend. This is an inverse relationship of the graph of Black residents.

![insert6](PoliceDistrictVacantBuildings.png)

It is important to note that the Black Butterfly suggests racial disparities are clustered within the western and eastern halves of Baltimore. In the graph above, the highest number of vacant buildings are within the western and eastern police districts, suggesting that race could be a significant factor. 

![insert7](https://github.com/EuniceNamkoong/Vacant-Buildings-Baltimore-City-Income-Race/blob/main/Cluster%20Nodes%20Grouping%20Table.png)

Combining all the data above, a cluster analysis was conducted to group like neighborhoods by charactersistics. 
* Cluster 1: 
  * higher than average Black residents
  * lower than average White residents
  * higher than average percent of households below the poverty line
  * lower than the average household median income
  * **much higher than average vacant buildings** 
* Cluster 2: 
  * lower than average Black residents
  * higher than average White residents
  * lower than average number of households below the poverty line
  * lower than the average household median income
  * lower vacant buildings cluster
* Cluster 3: 
  * higher than average Black residents
  * lower than average White residents
  * lower than average number of households below the poverty line
  * lower than the average household median income
  * **slightly higher than average vacant buildings cluster**
* Cluster 4: 
  * much lower than average Black residents
  * much higher than average White residents
  * much lower than average number of households below the poverty line
  * much higher than the average household median income
  * lower than average vacant buildings cluster
 

Proposed Policy Solution: 
To put our findings into action, we wanted to focus on strengthening existing Baltimore City legisation. In August 2019, [Baltimore Councilman Burnett](https://www.bizjournals.com/baltimore/news/2020/09/21/council-bill-signage-qr-code-vacant-properties.html) proposed a new way for Baltimore to hold negligent owners accountable through sign postages. However, just recently, as of this past March, the [Law Department amended the bill](
https://baltimorefishbowl.com/stories/burnetts-bill-would-force-vacant-property-owners-to-post-a-sign-or-a-pay-a-fine/) to have DHCD as the party responsible for posting the signage instead of the owners themselves. Instead of a paper sign, they must publish a [scannable QR code](https://www.qrcodepress.com/new-legislation-may-bring-vacancy-qr-codes-to-baltimore/8538335/) with contact information. The goal of the vacancy QR codes is to help make slumlord accountable for these empty buildings across the city and make these spaces more accessible to their neighbors. 

## Future Suggestions
Projections to completely get rid of the house vacancy problem in Baltimore is over a [billion dollars](https://www.marketplace.org/2020/07/08/why-cant-baltimore-solve-vacant-housing-problem/). However, working to efficiently enact this current legislation will reduce time, cost, and effort. According to DHCD, it would cost the agency $39k in the first year for supplies, printing costs, and staff and $14k each year after. Efficient policy enforcement that reduce cost in the long run combined with current social and political landscape, such as [Black Lives Matter](https://www.marketplace.org/2020/07/08/why-cant-baltimore-solve-vacant-housing-problem/) show great potential in creating strides on the income, race, and public health disparities regarding house vacancy in Baltimore. 

How our data can be important:
1) Agency can focus on covering certain police districts in order of highest to lowest number of vacant buildings present (western, eastern, southwestern, southern, etc.)
2) Focus on neighborhoods within clusters 1 and 3 when making inspection rounds to make the most efficient impact revitalizing the city.

If given more time, we would further analyze more data such as population loss, crime rates by neighborhood, and state funding/money allocation based on public health issues. Having access to this information can help 1) see overview of which neighborhoods should be prioritized in terms of development and funding 2) which neighborhoods are getting funding already (needs more), getting funding already (doesn’t need anymore), is not getting funding (needs fundings). 
