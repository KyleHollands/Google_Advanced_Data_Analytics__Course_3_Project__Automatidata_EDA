# Google_Advanced_Data_Analytics__Course_3_Project__Automatidata_EDA

# NYC Taxi Fare Prediction Project
## Project Overview
The NYC Taxi & Limousine Commission has partnered with Automatidata to develop a regression model capable of accurately predicting taxi fares. Before modeling can take place, the dataset must be analyzed, explored, cleaned, and structured to ensure reliable predictions.

## Problem Statement
During exploratory data analysis (EDA), several issues were identified in the dataset. Notably, some rows had missing trip distance values while still containing corresponding total amount values. These data points are considered anomalies and should be removed to prevent skewed model predictions.

## Solution
To address the anomalies, it is recommended to remove all data points with a trip distance of 0 from the dataset. Additional strategies should be considered for handling other outliers, such as:  
- Low trip distance but high total cost  
- High trip distance but low total cost  

## Data Understanding
EDA revealed that the two key variables for predicting fare amounts are **Trip Distance** and **Total Amount**. Scatter plots demonstrate a relatively linear relationship between these variables. Further analysis should investigate anomalous points and assess correlations to identify which variables are most relevant for regression models and statistical inference.

## Conclusion
Cleaning and exploring the dataset is a critical step prior to building regression models for fare prediction. Identifying anomalies and determining the most predictive variables ensures that subsequent modeling is based on accurate and reliable data.
