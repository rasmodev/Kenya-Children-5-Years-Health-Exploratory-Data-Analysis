# Kenya-Children-5-Years-Health-Exploratory-Data-Analysis
This repository contains an RMarkdown script for conducting an exploratory data analysis (EDA) on a dataset related to children under 5 years of age in Kenya. The dataset includes monthly data, disaggregated at a county level, covering the period from January 2021 to June 2023. The dataset contains information on various health indicators for children, including the total number of children dewormed, cases of acute malnutrition, stunting, diarrhea, and underweight children.

# Child Health Data Analysis - Kenya

## Overview
This repository contains an RMarkdown script for analyzing child health data in Kenya. The dataset consists of monthly data for children under 5 years, disaggregated at a county level, spanning from January 2021 to June 2023. The dataset includes various health indicators, such as the total number of children dewormed, cases of acute malnutrition, stunting, diarrhea, and underweight children.

## Data Description
The dataset comprises the following variables:
- Period (months from January 2021 to June 2023)
- County (the 47 counties in Kenya)
- Total number of children dewormed (Total Dewormed)
- Number of children <5 years with acute malnutrition (Acute Malnutrition)
- Number of children stunted (categorized by age: 0-6 months, 6-23 months, 24-59 months)
- Number of children <5 years with diarrhea (Diarrhea cases)
- Number of children who are underweight (categorized by age: 0-6 months, 6-23 months, 24-59 months)

## Tasks
Your primary tasks include:
1. Conducting exploratory data analysis (EDA) on the provided dataset.
2. Formulating an appropriate research question based on your EDA.
3. Carrying out relevant data analysis to address your research question.

## Data Sources
- The primary dataset is provided in the "data" folder.
- Population data from the 2019 Kenya Census is included using the "rKenyaCensus" R package.

## Running the Analysis
1. Make sure you have R and RStudio installed on your system.
2. Install the required R packages mentioned in the RMarkdown script.
3. Run the RMarkdown script to perform data analysis.

## Visualizations
The analysis includes various visualizations, such as line plots, choropleth maps, and histograms, to help you explore and understand the data effectively.

## Research Question
The research question addressed in this analysis is: "What are the factors associated with the coverage of deworming in Kenya?"

## Results
The analysis provides insights into the factors associated with deworming coverage in Kenya, highlighting the impact of stunting and diarrhea cases. It suggests a potential need for targeted interventions in specific regions.

## Folder Structure
- `data`: Contains the primary dataset.
- `shapefiles`: Includes shapefiles for generating choropleth maps.
- `README.md`: This file providing an overview of the repository.
- `child_health_analysis.Rmd`: The RMarkdown script containing the data analysis.

## Contact
For any inquiries or further information, please feel free to contact:
- Rasmo Wanyama
- Email: rasmodev@gmail.com
- LinkedIn: https://www.linkedin.com/in/rasmo-/

We hope this analysis provides valuable insights into child health in Kenya.

