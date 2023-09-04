# Kenya-Children-5-Years-Health-Exploratory-Data-Analysis
This repository contains an RMarkdown script for conducting an exploratory data analysis (EDA) on a dataset related to children under 5 years of age in Kenya. The dataset includes monthly data, disaggregated at a county level, covering the period from January 2021 to June 2023. The dataset contains information on various health indicators for children, including the total number of children dewormed, cases of acute malnutrition, stunting, diarrhea, and underweight children.

### Introduction

The dataset includes the following variables:
- Period (months from January 2021 to June 2023)
- County (representing the 47 counties in Kenya)
- Total number of children dewormed (Total Dewormed)
- Number of children under 5 years with acute malnutrition (Acute Malnutrition)
- Number of children stunted in different age groups (0-6 months, 6-23 months, 24-59 months)
- Number of children under 5 years with diarrhea (Diarrhea cases)
- Number of underweight children in different age groups (0-6 months, 6-23 months, 24-59 months)

Before formulating our research question, I start by exploring the dataset.

### Data Loading and Exploration

I imported various R packages for data analysis and loaded the dataset from a provided link. The data initially had 1,410 observations and 11 variables.

I performed data cleaning, such as combining stunting and underweight columns and formatting the date column. I also removed redundant words from the county names and handled missing values appropriately.

### Descriptive Statistics

I computed descriptive statistics for the dataset, focusing on the average number of cases reported and treatments administered among children under 5 years in Kenya from 2021 to 2023. This analysis provided insights into the trends and patterns of health syndromes and deworming.

### Data Visualization

I visualized the data to showcase trends in the average number of reported cases per month and the deworming data. Using line and point graphs, I highlighted the increasing trends in reported cases of diarrhea, stunting, underweight, and children dewormed.

I also created a choropleth map to illustrate the prevalence of various malnutrition conditions across Kenyan counties. This interactive map allows users to explore health indicators at the county level.

### Research Question

Based on our exploratory data analysis, I formulated our research question: "What are the factors associated with the coverage of deworming in Kenya?" To answer this question, I used a mixed-effects model.

To prepare for the modeling, I incorporated population data to calculate the coverage of deworming per 100,000 children and the incidence of cases per 100,000 children under 5 years.

### Statistical Modeling

I began by checking the skewness of our outcome variable (coverage of deworming) using a histogram. The data appeared skewed, so I opted for a negative binomial model.

I conducted univariable model analyses, assessing the association between the coverage of deworming and each independent variable (diarrhea cases, stunting, and underweight) separately. These univariable models guided us in selecting variables for the multivariable model.

In the multivariable model, I included all three independent variables. The results showed that coverage of deworming was weakly associated with an increased risk of stunted cases per 100,000 children and a decreased risk of diarrhea cases per 100,000 children. There was no significant association with underweight cases.

These findings provide insights into the factors influencing deworming coverage in Kenya.

Please feel free to explore the code and analysis in this repository for a detailed understanding of the research.


## Contact
For any inquiries or further information, please feel free to contact:
- Rasmo Wanyama
- Email: rasmodev@gmail.com
- LinkedIn: https://www.linkedin.com/in/rasmo-/

I hope this analysis provides valuable insights.
