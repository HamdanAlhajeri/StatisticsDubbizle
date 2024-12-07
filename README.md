# Abu Dhabi Rental Market Analysis

## Overview
This project analyzes the rental market in Abu Dhabi, focusing on 3-bedroom properties across different neighborhoods. The analysis includes rental prices, property characteristics, and neighborhood trends.

## Dataset
The analysis uses data from `rentals_3bedr_Abu_Dhabi_2.csv`, which contains information about:
- Rental prices
- Number of bedrooms (all 3-bedroom properties)
- Number of bathrooms
- Property locations
- Property sizes
- City (all in Abu Dhabi)

## Key Features
- Statistical analysis of rental prices
- Property size distribution
- Neighborhood comparisons
- Outlier detection and removal
- Confidence interval calculations

## Tools Used
- Python
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy

## Key Findings
- Price range: 50,000 AED to 1,400,000 AED
- Sample size: 322 properties
- Detailed confidence intervals for specific neighborhoods:
  - Corniche Area: 111,793 - 130,539 AED
  - Hamdan Street: 75,360 - 84,639 AED

## Visualizations
The project includes various visualizations:
- Average rental prices by neighborhood with confidence intervals
- Q-Q plots for price distribution analysis
- Statistical summaries of property characteristics

## Getting Started
1. Clone this repository
2. Ensure you have Python and required libraries installed
3. Run the Jupyter notebook `Data.ipynb`
