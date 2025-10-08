## Covid19 Prediction and Reporting

### Project Overview
The project focuses on building a comprehensive data platform for the reporting and prediction of COVID-19 spread. 

The primary objectives are:
#### Machine Learning and Predictive Analytics:
Develop a data platform to support the data science team in running machine learning models aimed at predicting the spread of COVID-19 and uncovering actionable insights from the data.
#### Reporting and Trend Analysis:
Create a robust reporting environment that enables data analysts to efficiently generate reports and visualize COVID-19 trends using modern reporting tools.

The scope of this project is specifically limited to data related to European Union (EU) countries and the United Kingdom (UK).

### Architecture

![Architecture](https://github.com/Pavani9707/covid-reporting-repo/blob/ef0009c55dc3ca6ca9735cea61020bbd6b1b5f5b/Architecture.png)

### Data Sources
#### ECDC Website (European Centre for Disease Prevention and Control)
1. Confirmed Cases
2. Mortality
3. Hospitalization/ICU Cases
4. Testing Numbers

#### Eurostat Website
1. Population by age

## Data Destinations
#### Data Lake

The data lake will serve as the centralized repository for all COVID-19–related raw and processed data. It will be populated and updated on a daily basis with the following datasets:

Confirmed COVID-19 cases: Daily counts of new confirmed cases.  
Mortality data: Daily records of fatalities resulting from COVID-19.  
Hospitalization and ICU statistics: Details on hospital admissions, ICU cases, weekly new admissions, and patients in hospital at the end of each day.  
Testing data: Information on the number of tests conducted per week and the number of new positive cases identified through testing.  
Population demographics: Country-level population statistics segmented by age groups.

This data will provide a foundation for the data science team to perform predictive analytics and build machine learning models to forecast the spread of COVID-19 and derive insights.

#### Data Warehouse

A data warehouse will be created and populated with a subset of this curated data from the data lake. 
This warehouse will include aggregated weekly data for confirmed cases, mortality rates, hospitalizations, ICU admissions, and testing statistics. 

The data analysts will use this warehouse to report on COVID-19 trends.
