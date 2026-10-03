# Azatbek Nurbekov

## Description

I am originally from the Kyrgyz Republic (Central Asia region), a member of the Eurasian Economic Union (EAEU), where the car market and 
the import of foreign vehicles are relatively heavily regulated. In recent years, the number of electric vehicles imported into Kyrgyzstan, 
particularly from China, has increased significantly. The EAEU also provides annual quotas that allow a certain significant 
number of electric vehicles to be imported without customs duties, and in Kyrgyzstan these quotas have often been used up quite quickly
(which is very surprising). 
This made me interested in the broader question of how the electric vehicle market is developing around the world. 
There could be many reasons behind the fast growth of EV market, including gasoline prices, 
the falling cost and increasing availability of Chinese electric vehicles, government policies, and differences in charging infrastructure.
For this project, I want to explore the major trends in the global and US market.
I am particularly interested in EV sales, market share, EV stock, and the development of public charging infrastructure.
I would also like to look more closely at the United States because its EV market differs from many other parts of the world. 
Moreover, the EV market differs within the US states. 
When I visited California, I noticed a very large number of electric vehicles, especially Teslas, compared to other US states. 
This made me interested in understanding why EV market varies so much within the United States. 
Differences in state policies, incentives, charging infrastructure, income, and other factors may help explain these patterns.
I plan to examine differences not only between the United States and other countries, 
but also across US states and potentially at the county level (The reason is the availability of the data in the US). 
My goal is to understand where EV market is growing fastest, 
how charging infrastructure is developing alongside it, and how geographically uneven the transition to electric vehicles has been.

## Data Sources

### Data Source 1: IEA Global EV Outlook 2026 

URL: https://www.iea.org/data-and-statistics/data-product/global-ev-outlook-2026

Size: approximately 49,500 rows, 9-12 columns

This dataset contains country level data on the global electric vehicle market. 
It includes EV sales, EV stock, EV sales share, EV stock share, public charging points, vehicle types, powertrains, and yearly observations.
I have explored this dataset. It contains historical data from 2010 through 2025. 
I plan to use it to examine global EV market growth, compare countries.


### Data Source 2: U.S. Department of Energy Alternative Fuels Data Center: Electric Vehicle Registrations by State

URL: https://afdc.energy.gov/data/search?q=electric

Size: approximately 50 state-level observations for the most recent registration snapshot, 
additional historical vehicle-registration data are also available.
This dataset provides counts of light-duty electric vehicles registered across US states. 
I plan to use it to compare EV market across states and to examine how different the US market is geographically.
This data will be especially useful for comparing states such as California with other parts of the United States 
and for investigating whether differences in EV adoption are associated with state-level policies, infrastructure, or other characteristics.


### Data Source 3: U.S. Department of Energy Alternative Fuels Data Center: Alternative Fueling Station Locator

URL: https://afdc.energy.gov/data_download/new

Size: 10 000 of station-level observations; exact number of rows and columns will be determined after loading the EV-only dataset.
This dataset contains detailed information on public electric vehicle charging stations in the United States.
I plan to use this dataset to examine the geographic distribution of EV charging infrastructure across the United States. 
Because the observations are available at the individual station level, I may be able to aggregate the data by state and potentially by county.
I will use this source to compare charging infrastructure with EV adoption and identify places where the number of electric vehicles may be growing 
faster than the availability of public chargers.

### Data Source 4: U.S. Department of Energy Alternative Fuels Data Center: EV Laws and Incentives by State

URL: https://afdc.energy.gov/data/categories/laws-incentives

Size: To be determined after downloading the dataset.
This dataset contains information on state-level laws and incentives related to electric vehicles and charging infrastructure.
I plan to use it to explore whether states with more EV-related policies or incentives also tend to have higher EV adoption 
or more developed charging infrastructure. 
This analysis would be descriptive rather than causal, but it may help identify interesting differences between states.

## Questions

1. Is combining a global EV analysis with a more detailed US analysis too broad for this project?
2. I am considering the title "Global EV Market and Charging Infrastructure, with the U.S. as a Case Study."
   I would like to start with global trends, then focus on the US, and finally compare EV adoption and infrastructure across states.
   Does this seem like a good structure for the project?

