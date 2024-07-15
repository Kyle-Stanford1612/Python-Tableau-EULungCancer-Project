# European Union Lung Cancer Analysis Project
This repository contains my Python code for a student project I completed whilst studying at CareerFoundry. This project lead to the development of a Tableau Storyboard detailing insights about Lung Cancer incidence and survival across EU countries. Python scripts have also been included to document the various analyses run on the data.

## Project Context:
![image](https://github.com/user-attachments/assets/3fcd7aa4-0e37-4831-b096-fc14bc316466)

In the EU, Lung Cancer is estimated to account for 20.4% of all deaths due to cancer, making it the leading cause of cancer death in men and second in women. Analysing demographic, biological, behavioural, and treatment-related factors in lung cancer patients can contribute to developing cancer-risk prediction models and support decisions regarding appropriate treatment.

## Key Questions and Objectives:
This analysis attempts to answer the following questions:

● Which health indicators are most strongly associated with lung cancer survival?

● Which countries in the European Union have the highest survival rate of lung cancer? why might some countries' survival rates be ahead of others?

● Can a predictive model be developed to determine an individual's likelihood of surviving lung cancer based on health indicators, treatment, and/or demographic variables?

## Data:

1) Lung cancer mortality data:

● MasterDataSan. (2024, May). Lung Cancer Mortality Datasets v2. Retrieved June 12 from https://www.kaggle.com/datasets/masterdatasan/lung-cancer-mortality-datasets-v2.

2) World Bank development indicators were sourced to supplement the analysis. The link is:

● https://databank.worldbank.org/reports.aspx?source=2&series=NY.GDP.MKTP.CD&country

3) A custom JSON file was generated from the following website:

● https://geojson-maps.kyd.au/

## Tools Used:

● **Python:** Scripts were written in Jupyter notebook to conduct data cleaning, data wrangling, and various analyses to uncover relationships and patterns within the data.

● **Tableau Public:** Tableau was utilised to illustrate and report on findings made throughout the project. Key insights, limitations, and future steps have been detaled in the conclusion.

● **Excel:** On occasion, Excel was utilised to wrangle the data and simplify the process of creating certain visualisations in Tableau.

## Folders
Project files are stored using the following folder structure:

● *01 Project Management*: Contains project brief and data sourcing documentation.

● *02 Data*: The following subfolders were used (folder could not be uploaded to GitHub due to file size):

  → Original Data contains the original data frames. 
  
  → Prepared Data contains data frames that have been edited using Python (cleaning, merging, etc.) as well as JSON files for spatial analysis

● *03 Python Scripts*: Contains Jupyter notebooks with all relevant code used throughout the project.

## Final Product:
The link to the storyboard made using Tableau Public can be accessed [here](https://public.tableau.com/views/AnalysisofLungCancerAcrosstheEuropeanUnion/StoryBoard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

This storyboard does not contain every step conducted throughout the analysis - only those relevant to the final results.
