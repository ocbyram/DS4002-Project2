# DS4002-Project1
Project 1 Analysis for DS 4002

## Contents


## Section 1: Software and Platform 
- Software: The following tools/programs were used to perform analysis
    <!-- - [R (3.3.0+)](https://cran.rstudio.com/) -->
    <!-- - [R Studio (2023.12.1)](https://posit.co/download/rstudio-desktop/) -->
    - [Python (3.10.12)](https://www.python.org/downloads/)
    - [Git](https://git-scm.com/)
- Hardware: Analyses were run on the following Hardware and Operating systems
    - Dell Latitude 7480 (Ubutnu 22.04.2)
- Dependencies: 
    - Matplotlib
    - sklearn 
    - pandas
) 


## Section 2: Documentation Map
Project Structure
```
Project
├── DATA
│   ├── weather.csv
├── LICENSE
├── OUTPUT
│   └── Graph Files
├── README.md
└── SCRIPTS
    └── DS4002_Analysis.Rmd
```

## Section 3: Reproducing

***To reproduce the analysis performed in R, one must first used the read.csv() function to import the weather csv data. Subset the columns that are mentioned in the data appendix, then create a new column labeled "year" with the year of the date subset into it. After this use the ANOVA function to perform a simple ANOVA test on the max temp, min temp, precipitation, and snow. Following this, create boxplots on the two that have significant p-values (precipitation and max temp). Finally, create a linear regression model using the lm function in R. This should regress max temp on date, which allows you to predict the max temperature of future dates based on past ones.*** 
