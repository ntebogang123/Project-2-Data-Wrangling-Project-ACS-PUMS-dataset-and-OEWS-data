# Project-2-Data-Wrangling-Project-ACS-PUMS-dataset-and-OEWS-data

**Analyzing Socio-Economic Factors in the U.S. Workforce: A Data-Driven Approach**

## Overview

This project utilizes the 2020 ACS PUMS dataset and OEWS data to investigate the interplay of socio-economic factors, such as sex, disability, education, and employment, in the United States. By analyzing disparities in occupation, income, and workforce participation across demographic groups, the study aims to provide insights into the complex dynamics of the U.S. labor market.

## Research Questions

1. **Occupational Distribution:**
   - How does the distribution of occupations vary based on sex, disability status, and educational attainment?
   - Are there noticeable trends in the participation of different demographic groups across various occupations?

2. **Educational Attainment and Wages:**
   - Are there discernible correlations between educational attainment levels and wages within different occupations?
   - What is the impact of education on income, and are there significant variations between occupations?

3. **Wage Analysis:**
   - What is the range of the average wage corresponding to manager positions and legal positions?
   - Are there substantial differences in income levels between managerial and legal occupations?

## Data Sources

- [Bureau of Labor Statistics (BLS) Occupational Handbook](https://www.bls.gov/soc/2018/soc_2018_manual.pdf)
- [OEWS Data - Occupational Employment and Wage Estimates](https://data.wa.gov/Employment/Occupational-Employment-and-Wage-Estimates/icqj-j27g/about_data)
- [ACS PUMS Data - American Community Survey Public Use Microdata Sample](https://data.census.gov/mdat/#/search?ds=ACSPUMS5Y2020&cv=SEX,DEAR,DEYE,WRK,ACCESSINET&rv=ucgid,SOCP&nv=SCHL&g=0400000US53)

## Analysis Results

### 1. Occupational Distribution

- Women appear to dominate the Legal Occupation class more than men.
- Certain occupation classes, such as Protective Service Occupations and Architecture and Engineering, exhibit low participation of women.
- Management Occupations show a significant presence of women, nearly equal to men.

### 2. Correlation Between Education and Wages

- Legal Occupations have an average wage of $33.24, with variations based on educational attainment.
- Specific educational levels contribute to varying income levels across different occupations.

   | Occupation                        | Average Wage |
   |-----------------------------------|--------------|
   | Architecture and Engineering      | $51.26       |
   | Legal Occupations                 | $33.25       |
   | Management Occupations            | $62.48       |
   | Protective Service Occupations    | $38.78       |

### 3. Wage Range for Managerial and Legal Positions

- Management Occupations have an average wage of $51.27.
- Legal Occupations have an average wage of $33.25.

## Reflection

The project's findings prompt a critical examination of data quality issues and a validation of the dataset's accuracy. Further research could involve exploring occupations corresponding to lower and higher ends of the mean hourly wage, potentially necessitating additional data to ensure comprehensive and reliable insights into the U.S. workforce landscape.
