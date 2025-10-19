# Teco Customer Churn Analysis

## Overview
This project analyzes customer churn for Teco, a telecommunications company. The primary focus is on understanding the factors influencing customer churn, particularly through the lens of payment methods and contract types. The insights gained aim to guide the company in crafting effective retention strategies.

## Objective
The analysis aims to identify key drivers behind customer churn and provide actionable recommendations to enhance customer retention. By understanding the relationships between contract types, payment methods, and customer tenure, Teco can implement targeted strategies to minimize churn.

## Project Structure
- churn_analysis.ipynb: Jupyter notebook containing the complete analysis, including data processing, exploratory data analysis, and visualizations.
- data/Customer Churn.csv: Dataset used for the analysis, containing customer information and churn status.
- Teco Customer Churn Analysis.pdf: Summary document detailing key findings and recommendations.

## Key Insights
1.**Contract Type**: 
  - Customers on month-to-month contracts exhibit a higher churn rate (42%) compared to those on yearly (11%) or bi-annual contracts (3%).
  - **Recommendation**: Promote long-term contracts to improve retention.

2. **Payment Methods**: 
  - Customers using electronic checks are more likely to churn (45%) than those using credit cards or bank transfers (15-18%).
  - **Recommendation**: Encourage customers to switch to more reliable payment methods.

3. **Churn by Tenure**: 
  - Customers with less than one year of tenure have a churn rate of 50%, indicating a critical need for early engagement strategies.
  - **Recommendation**: Focus on improving the customer experience within the first year.

4. **Demographics**: 
  - Senior citizens (aged 65+) show a churn rate of 41%, compared to 26% among younger customers.
  - **Recommendation**: Create personalized retention programs targeted at senior customers.

## Visualizations
The analysis includes various visualizations such as:
- Bar plots illustrating churn rates by contract type and payment method.
- Line graphs showing churn trends over customer tenure.

These visual aids enhance the understanding of customer behavior and the impact of different factors on churn rates.

## Installation
To run this project, ensure you have the following Python libraries installed:

- numpy
- pandas
- matplotlib.pyplot
- seaborn  
