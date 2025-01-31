## Impact of inequality on Economic Growth 

Participants will use public UK national and regional data over time to try and establish whether there is a relationship between income inequality and growth in the UK? And what can we say about the direction of causality?

### Background

Economic growth is a strategic objective for HM Treasury and other parts of government. 

Economic theory has long posited a relationship between income inequality and economic growth, starting with Kuznets’1 theory of the ‘inverted-U’ relationship – that is, income inequality initially rises with GDP growth before falling. Acemoglu and Robinson (2002)2 noted that the Kuznets hypothesis essentially holds when looking at Western European countries during the 19th century, but doesn’t appear to hold for other countries and time periods. It is important to note that the relationship between income inequality and economic growth arguably holds both ways i.e growth has an impact on income inequality and income inequality has an impact on growth.  

As far as we can tell, there are no empirical studies examining the relationship between income inequality and growth in the modern (post Second World War) UK context. This project aims to start to fill this gap.  

If the project finds that there is a statistically significant relationship between income inequality and growth in the modern UK context, this would be an important result, suggesting policies targeted at reducing income inequality (such as higher taxation on the top of the income distribution) could be beneficial for growth.  

### Scope

Income inequality, the unequal distribution of income among individuals or households in a society is within scope, whilst wealth inequality, the unequal distribution of assets or net worth among individuals or households in a society, is not within scope.  

The project is planned to look at the modern UK context (post World War 2) only: other countries and the historic UK trend are out of scope. Assigning a time frame is tricky: the UK has evidently changed significantly since 1945, but a longer time frame provides more data points. 

We are also interested in finding out what drives the relationship between income inequality and economic growth in the UK. Theories suggested by the literature include the strength of institutions, inequality acting on human capital accumulation and a decline in worker power.  

### Analysis Strategy

We plan to replicate an [existing single-country study](https://mpra.ub.uni-muenchen.de/78268/1/MPRA_paper_78268.pdf), using UK data since 1945. Other approaches are available, such as [a regional approach](https://www.researchgate.net/publication/267403855_ECONOMIC_GROWTH_AND_INCOME_INEQUALITY_IN_BRAZIL_ANALIZING_THE_COMPARABLE_MINIMUM_AREAS). 

The precise operationalisation of this project is important. Even if we take the regression above as a format, ignoring other approaches, there are still important choices to be made on key variables. 

For example, this [OECD paper](https://www.oecd.org/en/publications/trends-in-income-inequality-and-its-impact-on-economic-growth_5jxrjncwxv6j-en.html) found that income inequality has a negative and statistically significant impact on subsequent growth. In particular, what matters most is the gap between low income households and the rest of the population. In contrast, no evidence is found that those with high incomes pulling away from the rest of the population harms growth. We will therefore need to run specifications on different types of inequality. 

Similarly, what we use for output is important. If one of the mechanisms that income inequality acts on growth is by acting on human capital accumulation, it is important to control for the number of hours worked. We will therefore need to determine whether a metric such as real productivity per hour is more appropriate than GDP per capita.  


### Data Available
If we follow the style of regression outlined above then we need data on the following areas:

| Data Details          | Origin | Blob Storage |
|-----------------------|--------|--------------|
| Economic growth       |        |              |
| [GDP](https://www.ons.gov.uk/economy/grossdomesticproductgdp/timeseries/ybha/ukea) | ONS    |              |
| [Labour Productivity](https://www.ons.gov.uk/employmentandlabourmarket/peopleinwork/labourproductivity) | ONS    |              |
| [Any other approaches to growth we can think of] |        |              |
| Human Capital         |        |              |
| [Human Capital Index](https://datacatalog.worldbank.org/search/dataset/0038030/Human-Capital-Index) | World Bank |              |
| Labour                |        |              |
| [Population Growth](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates#timeseries) | ONS    |              |
| Physical Capital      |        |              |
| [Capital Stocks](https://www.ons.gov.uk/economy/nationalaccounts/uksectoraccounts/bulletins/capitalstocksconsumptionoffixedcapital/previousReleases) | ONS    |              |
| Income inequality     |        |              |
| [Gini](https://www.ons.gov.uk/peoplepopulationandcommunity/personalandhouseholdfinances/incomeandwealth/bulletins/householdincomeinequalityfinancial/financialyearending2022), Palma Ratio, S80/S20, P90/P10, P50/P10 | ONS    |              |
| Inflation rate        |        |              |
| [CPI](https://www.ons.gov.uk/economy/inflationandpriceindices/datasets/consumerpriceindices) / alternatives | ONS    |              |


#### Return [home](index.md)
