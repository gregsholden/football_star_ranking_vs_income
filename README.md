# Is The Playing Field Level?

## Background

This project compares the distribution of rankings of top high school football players to the distribution of income across the U.S.

Top high school football players are given star rankings by recruiting services.  These range from 1 to 5 stars, where 5 star prospects are the highest ranked.  Approximately 1% of the 3,300 recruits ranked annually receive a 5-star ranking, while the next ~10% receive a 4-star ranking.  U.S. college football programs pay close attention to these rankings, and try to recruit as many highly-ranked players as possible.

The goal of this project was to see if wealthier recruits (who are more likely to be able to afford private coaching and camps) tended to receive a disproportionate share of top rankings.  If so, this could lead to more scholarship offers from prestigious college football programs, which in turn leads to a greater chance of receiving a lucrative NFL contract.

The analysis uses average income by zip code as a proxy for wealth, and maps the income data to each player's hometown.  

## Data Sources

1.  High school player data is sourced from the CollegeFootballData.com website and covers the years 2011-2023:
https://api.collegefootballdata.com/api/docs/?url=/api-docs.json

2.  Zip code information is taken from https://www.unitedstateszipcodes.org/zip-code-database/

3.  Income data is from https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2019-zip-code-data-soi

## Key Files

1.  593 Project_Position and Team Analysis_FINAL.ipynb: Combines recruiting, income and zip code data and is used to conduct analysis by school and position.

2.  Recruiting_and_outcome_result_correlations.ipynb: Used to calculate correlations between different position groups and winning percentagess

3.  :  Used to create maps for showing hometowns of recruits by school and based on star rankings.
