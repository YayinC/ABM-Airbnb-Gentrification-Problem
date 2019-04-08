# Agent Based Modeling: Airbnb's Gentrification Problem
By Yayin Cai & Xiao Wu   

## WHAT IS IT?
This model provides a simple sandbox to simulate the role Airbnb plays in gentrification. There are patches representing streets, residential, commercial, places of interests and parks, and two kinds of agents representing AirBnbs and long-term rental houses.  
This model only considers about the demand-side of the rental market in the study area by having each patch calculate its distance to various amenities, therefore these distances give each patch two values, Airbnb rent, and long term rent.
The motivation for this model is to show the change the first Airbnb brings in the gentrification process. When people of other residential patches realize that becoming Airbnb is more beneficial than long term rental houses, they will switch their houses into Airbnb. However, when there are too many Airbnb, the long-term rent increases because of the shrinking market and people may consider about switching back.  
This could be used in the future for governments to intervene the gentrification process, for instance, providing more allowance to the rental houses when there are too many Airbnb.  
## HOW IT WORKS
The idea of creating these multipliers is to change the weights according to the users’ preferences and allow the simulation to be applied to multiple occasions. Those weights are applied to a scaled distance metric to produce two patch properties, land value, and tourism value, where the metrics are weighted differently. These two properties also defined the Airbnb rent and long-term rental rent.  
After the simulation starts, the long-term rents and Airbnb rent value would also be penalized by the number of them in the markets.  
After the simulation starts, you would see the rental houses keep switching to Airbnb until the number of Airbnb reach to a peak, and then some of them begin to switch back to long-term rental houses. You should also be able to see the land value change during this process when you click on show land value.  
## HOW TO USE IT
First, please make sure you are running the model in the 5.2.1 environment. Change the multipliers value, these multipliers define the weights that each amenity take on affecting the land value, long-term rent and Airbnb rent.
Second, click set up to generate the first Airbnb and all the other rental houses on all the residential patches.
Third, after clicking on the Show Change button, this model would be able to show you how Airbnb contributes to the gentrification process.
During this process, if you click on show land value, you should also be able to see the relationship between this process and gentrification.
## THINGS TO NOTICE
The emergent phenomenon this model shows is the change between Airbnb and long-term rental houses after the first Airbnb appears.
## THINGS TO TRY
Try adjusting the weights of multipliers, you should be able to see the change of speed in the simulation, the final balance they reach and numbers of Airbnbs and rental houses when they finally came to a balance.  
The plot would show the fluctuation of the rental houses and Airbnb’s counts in the rental market.  
## EXTENDING THE MODEL
This model is simulating the rental market in an ideal occasion that all the residential patches are rental, either long-term or Airbnb, and different land use patches would not change throughout the time. All the calculation of rents is based on empirical estimation. We would need more theoretical supports on economics to improve the model in the near future.  
We think the model is generalizable under our assumptions. It’s calculating the rents based on the same calculation logic thus all the rental houses are given equal opportunities to switch back and forth.  
We have another theory of testing how Airbnb affects gentrification. Because in the real life, after too much Airbnb appears, more developing opportunities would be brought to the Airbnb clustered area. The vacant parcels might become commercials, parks or other land use and thus affect the rental value and the Airbnb rent again, which is an even more complicated process. We would improve our simulation model in calculating Airbnb rent and long term rent in the near future.  
## NETLOGO FEATURES
We used points, turtles, and patches in coding this simulation. The crimes are point features, Airbnb and long-term rental houses are turtles, and the various land uses are patches.  
## CREDITS AND REFERENCES
Horn, Keren, and Mark Merante. “Is home sharing driving up rents? Evidence from Airbnb in Boston.” Journal of Housing Economics 38 (2017): 14-24.  
Barron, Kyle, Edward Kung, and Davide Proserpio. “The Sharing Economy and Housing Affordability: Evidence from Airbnb.” (2017).
