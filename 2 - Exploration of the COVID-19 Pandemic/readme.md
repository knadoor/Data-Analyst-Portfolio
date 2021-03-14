# Exploration of the COVID-19 Pandemic

## Project Overview
I wanted to explore how COVID-19 was impacting different countries and explore which anti-pandemic efforts have been effective in curbing its spread.

## Datasets
Two datasets were used for analysis.

The [first dataset](https://github.com/owid/covid-19-data/tree/master/public/data) provides data on the fatalities from COVID-19 across different countries. This dataset was provided by 'Our World In Data' - and is current as at 17/02/2020.

The [second dataset](https://www.acaps.org/covid-19-government-measures-dataset) provides data on the anti-pandemic measures taken by different governments. It's provided by ACAPS, which is a non-profit project that provides international, independent humanitarian analysis (according to Wikipedia) - and is current as at 10/12/2020.

## Data wrangling steps prior to conducting analysis included:
* Renaming column headers 
* Dropping unnecessary columns
* Dropping duplicate rows
* Convert object header types to categorical datatypes
* Convert object header for the date, to the datetime format
* Merge data sets
* Filtering the data set to only include data for select countries


## Summary of Findings
* Initial analysis indicates a strong response against the pandemic from all governments under analysis based on their Stringency Index.
* Further investigation revealed that not all responses were neither strong, nor appropriate, in successfully controlling the pandemic. 
* The fatality rates of some of the select countries has been investigated in the presentation.
* Analysis indicates that the countries that successfully controlled the pandemic all used lockdowns and strict movement restrictions.


## Key Insights for Presentation
The main threads for exploration in the presentation is investigating the severity of the COVID-19 pandemic and comparing the efforts of different governments in fighting it.

A key insight found was that both the United States and India, even though they have higher deaths per million when compared with Australia, a person has a higher chance of surviving COVID-19 in these countries as per the statistics, because the case fatality rates (CFR) are much lower than Australia's.
