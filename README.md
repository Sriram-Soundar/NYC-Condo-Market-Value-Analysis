# NYC Condo Market Value Analysis

Welcome to the "Analysis of NYC Condo Market Values" project repository. This project involves rigorous statistical analysis to explore the relationships between various factors such as Total Units, Gross Square Footage, and Net Operating Income on the Full Market Value of condominiums in New York City.

## Project Overview

This project utilizes a comprehensive dataset of NYC condominiums to understand how different factors impact their market value. Through multiple linear regression models and exploratory data analysis, this analysis helps in identifying key predictors of condo market values and provides insights into the NYC real estate market.

## Dataset

The dataset includes the following variables:
- **Boro-Block-Lot**: Unique identifier for each property.
- **CondoSection**: Condominium section number.
- **Address**: Property address.
- **Neighborhood**: Neighborhood where the property is located.
- **Building Classification**: Classification code of the building.
- **Total Units**: Total number of units in the condominium.
- **Year Built**: The year in which the property was built.
- **Gross SqFt**: Total gross square footage of the building.
- **Estimated Gross Income**: Estimated annual gross income from the property.
- **Gross Income per SqFt**: Gross income per square foot.
- **Estimated Expense**: Annual estimated expenses for the property.
- **Expense per SqFt**: Expenses per square foot.
- **Net Operating Income**: Annual net operating income.
- **Full Market Value**: Assessed full market value of the condo.
- **Market Value per SqFt**: Market value per square foot.
- **Report Year**: Year the data was reported.

## Exploratory Data Analysis

Exploratory analysis includes:
- Generating pairwise plots to observe relationships between variables.
- Conducting ANOVA tests to compare different linear regression models.
- Utilizing boxplots and bar charts to explore the distribution of square footage per unit across neighborhoods.

## Statistical Models and Validation

Several linear regression models were tested:
- **Base Model**: Includes all variables.
- **Reduced Models**: Each omitting one or more variables to assess their impact on the model's predictive power.

Validation techniques used:
- **Split-Sample Validation**: Dividing the data into training and testing sets to evaluate model performance.
- **K-Fold Cross-Validation**: Used to ensure that the model's findings are not overfit to the data.

## Key Findings

- Certain variables like Gross SqFt and Net Operating Income significantly impact the Full Market Value.
- Neighborhood characteristics also play a crucial role in influencing condo prices.

## How to Use This Repository

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Sriram-Soundar/NYC-Condo-Market-Value-Analysis.git
   cd NYC-Condo-Market-Value-Analysis

2. **Data Exploration**:
   Open the R Markdown files to view the exploratory analysis and model testing.
