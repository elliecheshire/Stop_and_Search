# Police Stop and Search Data Analysis (England and Wales, 2006 - 2023)

## Introduction:
This project analyses police stop and search data in England and Wales from 2006 to 2023.
The goal is to investigate trends and potential biases in police stop and search practices with a particular focus on ethnicity.

## Aims:
- Explore trends in stop and search rates over time
- Analyse disparities in stop and search rates by ethnicity and region
- Visualise these findings

## Data Sources:
- Stop and Search Data (2006 - 2020)
      Source: GOV.UK
- Stop and Search Data (2021 - 2023)
      Source: GOV.UK
- Regional Shapefiles - used for mapping and geographical analysis
      Source: OpenDataSoft
- Population Data by Ethnicity - to assess the regional breakdowns of the population
      Source: Office for National Statistics

## Technologies:
- Programming Language: Python
- Key Libraries:
    - pandas (v2.2.2)
    - numpy (v1.26.4)
    - matplotlib (v3.10.0)
    - plotly (v5.24.1)
    - seaborn (v0.13.2)
    - geopandas (v1.0.1)
- Enviroment: Jupyter Notebook (v6.5.5)

## Repository Files:
- Exploring Disparities and Trends in Police Stops and Searches of England and Wales.pptx
        - Powerpoint presentation presenting analaysis
- Stop_Search_analysis.ipynb
        - Google Colab Notebook containing python code of analysis
- stop_search_07_20.xlsx
        - excel spreadsheet containing Stop and Search Data for financial years 2006-2020 from GOV.UK
- stop_search_21_23.xlsx
        - excel spreadsheet containing Stop and Search Data for financial years 2021-2023 from GOV.UK
- areas-of-england-and-wales-by-ethnicity.csv
        - csv file of the ethnicity demographics of England and Wales 2021
- georef-united-kingdom-region-millesime files
        - Shapefiles used for mapping and geographical analysis


## Setup:
The project is designed to run in the Google Colab notebook. 
Execute the cells in the notebook sequentially in order to preprocess the data and perform analysis.
