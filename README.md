# COVID-19 Pandemic Analysis (2019-2022)

## Overview

This project provides a detailed analysis of the development and progression of the COVID-19 pandemic from 2019 to 2022. Using data from the World Health Organization (WHO) and World Bank Development Indicators (WDI), the project examines:

- The time evolution of COVID-19 cases and deaths.
- Comparisons of the pandemic's impact across different countries, including Germany, Italy, France, and the UK.
- The relationship between new cases and deaths over time.
- Smoothing techniques for daily COVID-19 case data.
- Principal Component Analysis (PCA) of World Development Indicators to analyze socio-economic factors.

The analysis was performed using **R programming language** with visualizations and data manipulation handled via common R packages.

## Data Sources

The following datasets were used:

1. **WHO COVID-19 Data:** Daily numbers of new COVID-19 cases and deaths for most countries in the world, collected up to 2022-09-30.
2. **World Bank Development Indicators (WDI):** Socio-economic indicators for most countries, including population metrics, GDP per capita, life expectancy, and more.

## Key Sections

### 1. COVID-19 Time Evolution

- **Germany’s First Wave:** Analysis of the first COVID-19 wave in Germany, including daily case and death fluctuations from March to June 2020.
- **Country Comparisons:** Cumulative cases and deaths for Germany, Italy, France, and the UK. The study highlights differences in how each country managed the pandemic.
  
### 2. Smoothing Daily Data

- Multiple smoothing techniques (3-day, 7-day, and 10-day windows) are applied to daily case data to reduce noise and capture trends.

### 3. Correlating Cases and Deaths

- Analyzes how deaths followed new cases using time shifting and scaling methods. Includes case studies of Albania and Kosovo.

### 4. World Development Indicators (WDI) Analysis

- A Principal Component Analysis (PCA) on socio-economic data from the WDI dataset.
- Visualization of how countries group based on variables like urban population, GDP per capita, life expectancy, and more.
- Focus on countries that are missing data in the WDI dataset and their impact on the analysis.

## Key Findings

- The first COVID-19 wave peaked in different months across Germany, Italy, France, and the UK.
- Death waves consistently lag behind case waves by about five days, with a fatality rate of around 6.2% for the first wave.
- Smaller countries like Albania and Kosovo faced more challenges in handling cases and deaths compared to larger European countries.
- Socio-economic factors, such as urban population, life expectancy, and physician availability, vary significantly across regions, influencing the pandemic's impact.
