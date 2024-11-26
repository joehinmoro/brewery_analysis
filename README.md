# Brewery Sales Analysis

This project analyzes brewery sales data from multiple countries over three years, aiming to uncover insights into sales trends, profit distribution, product performance, and regional preferences.

## Table of Contents
- [Overview](#overview)
- [Dependencies](#dependencies)
- [Steps](#steps)
- [Usage](#usage)

## Overview
The notebook investigates the following:
- Monthly and yearly profit trends.
- Regional preferences between Anglophone and Francophone territories.
- Performance of specific brands, with a focus on high-performing and low-performing products.
- Insights into sales representatives and their impact on revenue.

## Dependencies
The notebook requires the following Python libraries:
- `numpy`
- `pandas`
- `calendar`

Make sure these libraries are installed before running the analysis.

## Steps
The analysis follows these key steps:
1. **Data Loading**: Load the sales dataset (`brew_analysis.csv`) and inspect its structure.
2. **Data Cleaning**: Standardize column names and create derived features such as `month_num` and `territory`.
3. **Exploratory Analysis**: Identify trends in sales, profit, and product popularity:
   - Monthly profit patterns.
   - Regional product preferences (e.g., malt vs. non-malt beverages).
   - Identification of key markets and their sales drivers.
4. **Deep Dive Analysis**: Explore:
   - Top-performing brands and representatives.
   - Yearly trends and seasonal fluctuations.
   - Country-specific profit and consumption patterns.


## Usage
1. Clone the repository or download the notebook.
2. Ensure the dataset (`brew_analysis.csv`) is in the working directory.
3. Open the notebook in Jupyter or any compatible environment and run the cells sequentially.
