[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/MiCHE652)
# Assignment_2

# Subtopic and its variable:
- GDP: GDP_level_b, quarterly_growth
- Housing price index: ave_quarter_property_price_index_growth
- Unemployment: Unemployment rate
- Australia Stock market: Index value
- Inflation: Inflation rate

# Variable explanation: 
- yearmonth: year and month
- Cash_rates: Interest rate
- GDP_level_b: GDP in billions
- quarterly_growth: GDP quarterly growth
- ave_quarter_property_price_index_growth: Average quarterly residential property price index growth
- Unemployment rate: Unemployment rate
- Index value: ASX-200 index monthly value
- Inflation rate: Inflation

# There will be NA values due to some reason:
- Orginal data collected on different timeframe, e.g. Cash rates in monthly but GDP growth in quarterly.
- Timezone of data collection is different, e.g. Cash rates from Jan 2013 to Apr 2023 while housing price index is from Mar 2013 to Dec 2021.

# Note:
All growth and rate variable is in %

#Suggested model:
- Fit linear model and assess p-value and coefficients.
- Assess correlation between cash_rates and variable.