# Time Series Analysis on Racial Hate Crimes in the United States

*Last Updated*: Dec. 15. 2022

*Author*: Seung Hyeon Mandy Hong

*Denison University, Fall 2022, MATH 422 semester-long research project*

# Description
Using the same research topics from my Data Analytics senior captsone project, I am implementing time-series methods to find the best predictive models for all racial hate crimes, anti-Black or African American hate crimes, and anti-Asian hate crimes. As part of the assignment submission, the semester-long project is divided into two parts: mid-semester project and final project.

# Software
I used *Python 3* to collect and clean data (Van Rossum & Drake, 2009). For descriptive and predictive analysis, I used R v4.1.3 (R Core Team, 2022). Packages used will be updated.

# Data
Main datasets come from the Federal Bureau of Investigation Crime Data Explorer (***hate_crime.csv***), the United States Bureau of Labor Statistics, and the national centers for environmental information (NOAA).

**Time series data for racial hate crimes** (3 columns with 360 rows, monthly from 1991 to 2020)
1. *all_race_hc_ts.csv*: three columns are year, month, and number of all racial hate crimes
2. *black_hc_ts.csv*: three columns are year, month, and number of anti-Black hate crimes
3. *asian_hc_ts.csv*: three columns are year, month, and number of anti-Asian hate crimes

**Time series data as explanatory variables** (3 columns with 360 rows, monthly from 1991 to 2020)
4 *cpi.csv*: monthly consumer price index (CPI)
5. *avg_temp.csv*: monthly U.S. average temperature
6. *unemployment.csv*: monthly unemployment rate
7. *non_racial_hc_ts.csv*: three columns are year, month, and number of non-racial hate crimes (hate crimes motivated by offenders’ bias against religion, sexual orientation, disability, gender, and gender identity.)


# Code

1. *midsemester project.final.html*: R markdown file including descriptive analysis and predictive analysis on racial hate crimes in the U.S using **function of time models** and **SARIMA** models. Cross-validated models with train/test data. Made prediction on 2021 and 2022.
2. *final-project.html*: R markdown file including predictive analysis on racial hate crimes in the U.S. using **spectral analysis, regression with ARIMA errors, GARCH**, and **ARFIMA**. Cross-validated models with train/test data. Made prediction on 2021 and 2022.

2. *FBI hate crime data cleaning.ipynb*: Jupyter notebook including codes for FBI data cleaning. The code includes procedures to generate time series data from FBI’s hate crime data (data 1 - 3 listed above.)

2. *FBI hate crime time series data (non racial hate crime).ipynb*: Jupyter notebook including codes with procedures to generate non-racial hate crime time series data from FBI’s hate crime data (data 7 listed above.)

# Paper
1. *MATH 422 mid semester project paper*: Research paper including descriptive analysis and predictive analysis (function of time and SARIMA)
2. *MATH 422 final paper(1)*: Continuing the research from the mid-semester project, this research paper includes  predictive analysis using spectral analysis, regression with ARIMA errors, GARCH, and ARFIMA.
