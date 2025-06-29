# Aviation Risk Assessment Report

## Author
Neema Naledi

## Overview
The company had planned to diversify its portfolio by entering the aviation industry, aiming to acquire and operate aircraft for both commercial and private use.

Initially lacking knowledge about potential aircraft risks, a comprehensive risk assessment had been conducted to determine which aircraft had posed the lowest operational risks for the new business venture.

## Links

- **Slide Presentation**: []
- **Tableau Dashboard**: []

## Prerequisites
*Getting started*
1. Fork 
Create a fork.

2. Clone 

- Type: git clone [https://github.com/veenaledi/DS-Phase-1-Project.git]
(you can clone using either *SSH key*  or the *HTTPS*)

### Business Understanding
__The Problem:__ The company wants to start a new airplane business, but doesn't know which planes are safe to buy and operate. 
The head of the new airplane division needs clear information to decide which planes to purchase. I need to find out which airplanes have the fewest accidents and problems so the company can buy the safest ones first. 
- By picking the safest airplanes, the company can: 
1. Save money 
2. Avoid disasters  
3. Build a successful new business without taking unnecessary risks.

### Data Understanding 
- **Data source**: [https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses]
This data is perfect for the project because it contains detailed records of aircraft incidents, allowing us to identify which planes have the most and fewest accidents.
- **Tools**: VS Code, Jupyter Notebook, Tableau(for the dashboard) were used to analyze the dataset. 
- **Time period**: The dataset has been collected from 1948 to 2022
- **Data Limitations**: 
1. The data set only includes reported accidents
2. The newer aircrafts have less historical data
3. The dataset may not capture all operational factors affecting safety
5. Different reporting standards across time periods 

Despite limitations, this data provides the best available evidence for comparing aircraft safety and making informed purchasing decisions for our aviation business.

### Data Preparation
- 1. First import necessary libraries.

- 2. Then load the data - in this case our data came as a *zipfile* therefore needing to extract it then properly load it on to the notebook.

- 3. Clean the Data Types - so as to correct any miscategorized data types.

- 4. Missing values - handling missing values so as to have a smooth analysis.

- 5. Checking for duplicates in certain colums

- 6. Outliers can deeply affect majority of analysis if not properly handled

- 7. Standardizing columns - this is just standardizing the format format

- 8. Saving the cleaned data in order to now make the dashboard.

This preparation gives us clean data to answer: *"Which planes have the fewest accidents"*

### Analysis & Modeling
- Calculated fatality ratios and accident frequencies by aircraft type
- Cross-validated findings across time periods

### Deployment
Interactive Tableau dashboard with aircraft safety rankings and operational insights.

## Key Findings

**Recommended Aircraft**: 
**Avoid**: 
**Focus**: Commercial passenger service aircraft show superior safety metrics

## Reccomendations 


## Testing
To run the cells press ctrl+shift

## Technologies Used
- Python

## Contributions

Contributions to the Aviation Risk Assessment Report are welcome! If you have any suggestions, bug fixes, or additional features you'd like to add to the dashoard, please feel free to submit a pull request or open an issue.

## Support
naledi.student@moringaschool.com
