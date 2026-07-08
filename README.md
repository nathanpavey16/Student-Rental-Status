## Student Rental Status and Academic Outcomes: An Exploratory Statistical Analysis
### Overview

This project investigates whether rental status is associated with differences in academic performance, weekly food expenditure, and preferred teaching structure among university students. Using survey data collected from the University of Sydney, the analysis applies data cleaning, exploratory data analysis (EDA), visualisation, and statistical hypothesis testing to identify relationships between rental status and key student outcomes.

The project demonstrates a complete report, from importing and cleaning raw survey data to performing statistical analysis and communicating findings through clear visualisations.

### Objectives

The analysis addresses three research questions:

1. Is rental status associated with students' preferred teaching structure (semester vs trimester)?

2. Do students who rent spend more on food each week than those who do not?

3. Is there a difference in academic performance (Weighted Average Mark) between students who rent and those who do not?

### Methods

The project was completed entirely in R using tidyverse

#### Data Preparation
Imported survey data from Excel

Renamed and selected relevant variables

Removed missing observations

Filtered invalid or unrealistic values

Prepared a clean dataset for analysis

#### Exploratory Data Analysis
Proportional bar charts

Boxplots

Histograms

#### Statistical Analysis
Fisher's Exact Test

Wilcoxon Rank-Sum Test

Monte Carlo Permutation Test

### Key Findings
No statistically significant relationship was found between rental status and preference for semesters or trimesters.
Students who rent exhibited significantly different weekly food expenditure compared with students who do not rent.
A statistically significant difference in Weighted Average Mark (WAM) was observed between the two groups.

These findings represent statistical associations and should not be interpreted as evidence of causation.

### Tools Used
R
tidyverse
dplyr
ggplot2
readxl
Rmarkdown
