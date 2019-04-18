# World-Bank-Loan-Analysis
Developed insights of World bank Loan using Tableau to translate buisness strategy into accountability. The dashboards created helps us to analysis time frame of disbursement and repayment

## Motivation

World Bank provides loans and credits to the developed and developing countries for their overall growth in the sectors for which the government of these countries need funds for. The World Bank Loan data domain is divided into 2 sectors - IBRD and IDA. 

**IBRD:**<br/>
The International Bank for Reconstruction and Development lends to governments of middle- income and creditworthy low- income countries. 

**IDA:**<br/>
The International Development Association provides interest free loans called credits and grants to the government of poor countries 

## Problem Statement:
As massive amount of finances are involved contributing to the Gross income of countries all over the world, credit check and analysis is extremely necessary for World bank as a business to decide which countries and specific sectors to invest in.

**Project Pipeline :**
1)  Get the data from the source
2)  Perform data cleaning and data munging in Python 
3)  Perform data blending with List of Developed and developing countries in Tableau 
4)  Visualize the data in Tableau 
5) Visualize the data based on the country, year number and represent the sectors which were funded in a particular year for both Developed and Developed Countries. 
6) Analyze the lending and Return patterns over the years.
7) Analyze the average number of days taken by India and Japan to return the loan. Study the loan statuses
8) Visualize the per sector status for the two countries
9) Recommendation for the World Bank giving sector specific details for the two countries. 

**Tableau Visualizations:**<br/>
Developed and Developing Countries represented on a world map.<br/>
IBRD - Developing Countries<br/>
IDA - Developed Countries<br/>

![image_descript](/images/1.png)

### Dashboard :
1) Select the country 
2) Key Learning - Filters: Based on the the country filtered, it shows the amount of loan taken and repaid over the years on the timeline. 
3) Key Leaning - Actions: When we hover over a specific year, the sectors for which the countries had taken loan can be visualized. 

**Developing Countries:**

![image_descript](/images/2.png)

**Developed Countries:**

![image_descript](/images/3.png)

**Lending and Return Pattern:**

![image_descript](/images/4.png)

## Key factors:
**Key Learning : Website Integration**<br/>

![image_descript](/images/5.png)
<br/>
**Per Sector Status for India and Japan:**

![image_descript](/images/6.png)
<br/>
## Recommendation:
Of all the developed and the Developing Countries borrowed from the World Bank Data , India and Japan have the highest performance rating based on their repayment patterns.<br/>In the future , these are the sectors in which the World Bank can invest:

**India:**<br/>
Road Construction<br/>
Power and Energy Resources<br/>
Education and Research 

**Japan:**<br/>
Power and Energy Resources<br/>
Road Construction<br/>
Agriculture and Fisheries 


## Acknowledgments

* [World Bank Group](https://data.worldbank.org/)
