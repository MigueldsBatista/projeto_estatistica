# Netflix Users Database Statistical Analysis

## Project Overview
This project analyzes a Netflix users database to extract statistical insights and calculate various probabilities. The analysis is performed using Python with Pandas in a Jupyter Notebook environment.

## Dataset
The project uses the "Netflix Users Database" dataset from Kaggle, which contains information about Netflix users including:
- Age
- Country
- Subscription Type
- Favorite Genre
- Watch Time (Hours)
- And other user metrics

## Features
The notebook performs the following analyses:

### Data Processing
- Imports and cleans the Netflix users dataset
- Handles missing values
- Standardizes text fields (lowercase, strip whitespace)

### Statistical Analysis
- Calculates the average age of users
- Counts and computes percentages of users by country
- Analyzes subscription types (Premium, Basic, Standard) distribution
- Examines favorite genre preferences across users

### Probability Calculations
- Computes basic probability calculations using custom functions
- Calculates the probability of intersections (e.g., being American and preferring horror)
- Determines the probability of unions of events
- Analyses conditional probabilities

### Key Probabilities Analyzed
- Probability of being from specific countries
- Probability of having certain genre preferences
- Probability of age being above 50
- Probability of watch time exceeding 300 hours
- Combined probabilities based on multiple conditions

## How to Use
1. Make sure you have Jupyter Notebook installed
2. Install required dependencies: `pandas`, `kagglehub`
3. Run the notebook cells sequentially to perform the analysis
4. Observe the calculated statistics and probabilities in the output

## Requirements
- Python 3.x
- pandas
- kagglehub (for dataset download)

## Note
This project demonstrates the application of probability theory and statistical analysis on real-world user data, providing insights into Netflix user demographics and preferences.
