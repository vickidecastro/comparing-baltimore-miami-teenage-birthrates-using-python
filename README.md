# Comparing Teenage Birth Rates of Young Women from Low-Income Families in Baltimore, MD and Miami, FL Using Python

## Background
The article [Socioeconomic Disadvantage as a Social Determinant of Teen Childbearing in the U.S.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3562742/) finds that "unfavorable socioeconomic conditions" are a contributing factor to high teen birth rates in the US. Teenage births are associated with adverse outcomes for both child --preterm birth, low birthweight, and infant death-- and mother, depending on her specific circumstances.  

This topic is interesting because although teenage birth rates in the US have decreased, the _absolute_ teenage birth rate is still high. In 2010, the teenage birth rate was a low 34.3 births per 1,000 people. However, absolute teenage births were still high at 370,000 total teenage births in the same year. Further research is necessary to tackle the factors that influence teen pregnancy and to identify any possible interventions. 

This project explores open data from the Opportunity Atlas Group on teenage birth rates of females from low-income families in Baltimore, MD and Miami, FL and uses Python to conduct data analysis. The data takes teenage birth rates from tracts within neighborhoods in each city; several tracts can make up a neighborhood.

## Data Sources
1. Opportunity Atlas
  - [Miami](https://github.com/vickidecastro/comparing-baltimore-miami-teenage-birthrate-lowincome-parents/blob/master/shown_tract_teenbirth_rP_gF_p25%20miami.csv): Original open data on teenage birth rates of females from low-income families in Miami, FL
  - [Baltimore](https://github.com/vickidecastro/comparing-baltimore-miami-teenage-birthrate-lowincome-parents/blob/master/shown_tract_teenbirth_rP_gF_p25%20baltimore.csv): Original open data on teenage birth rates of females from low-income families in Baltimore, MD

Teenage birth rate is defined as the fraction of women who claimed to have had a child while the mother was between the ages of 13-19, who also claimed dependent status. Any time "Teen" or "Teenage birth rate" are mentioned, this refers to the birth rate of teenage girls coming from low-income families. Some teen birth rates from specific tracts in neighborhoods in Baltimore, MD and Miami, FL were missing from the data set. The parental income level for this group (low-income families) is defined as 25% of the income distribution. 
  

## Business Question
How do the teenage birth rates from females in low-income families in Baltimore, MD and Miami, FL compare?

## Data Questions
1. What are the mean teen birth rates in each city? 
2. What are the maximum and minimum teenage birth rates in each city?
3. Which neighborhoods in Miami and Baltimore have the top 5 highest average teenage birth rates? 

## Data Analysis
![stats_both](https://user-images.githubusercontent.com/70858878/99890073-9335f400-2c29-11eb-9be5-e76c94c715a0.png)
Figure 1: Bar graph depicting mean, min, max teenage birth rate (calculated by neighborhood, not tract) for each city

-Min Teenage BR
  -Baltimore, MD: 0.0691
  -Miami, FL: 0.012

-Mean Teenage BR
  -Baltimore, MD: 0.4107
  -Miami, FL: 0.1819

-Max Teenage BR
  -Baltimore, MD: 0.638
  -Miami, FL: 0.51

![bar_both](https://user-images.githubusercontent.com/70858878/99890023-fb380a80-2c28-11eb-9b29-3ef7bf4127b3.png)
Figure 2: Bar graph depicting top 5 neighborhoods in each city with highest teenage birth rates

![download-1](https://user-images.githubusercontent.com/70858878/99890209-ec525780-2c2a-11eb-93c2-0f884d5c9be9.png)

Figure 3: Histogram for Baltimore, MD

![download-2](https://user-images.githubusercontent.com/70858878/99890259-64208200-2c2b-11eb-9864-971c6f78c4c9.png)

Figure 4: Histogram for Miami, FL


