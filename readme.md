# Crime Data Analysis Project 📊

## Overview
This project analyzes crime data in Los Angeles from 2020 to present (2023), focusing on trends, patterns, and factors influencing crime rates. The analysis includes data cleaning, exploratory data analysis, and predictive modeling using Prophet.

## Team Members
- Nirmit Ajay Sachde
- Krishna Priya Gitalaxmi
- Aarathi Saranya Pandravada
- Pratham Pawar
- Sri Sai Tarun Vemu

## Data Sources
- Primary crime dataset: Crime Data from 2020 to Present (Los Angeles City)
- Major events data: Los Angeles Times
- Population data: U.S. Census Bureau
- Employment and income data: LA Neighborhood Data
- LAPD regions data: LAPD Official Website

## Key Findings

### 1. Overall Crime Trends
- 2022 recorded the highest number of crimes
- Notable increase in crime rates post-COVID lockdowns
- Vehicle theft consistently ranks as the top reported offense

### 2. Regional Analysis
- Central region shows highest crime count (54,556 in 2021)
- Notable correlation between economic factors and crime rates:
  - Higher median household income → Lower crime rates
  - Higher unemployment rates → Higher crime rates

### 3. Temporal Patterns
- Peak crime hours: Afternoon
- Highest crime day: Friday
- Seasonal peaks during summer months
- New Year's Day consistently shows spike in crime rates

### 4. Demographic Insights
- Age distribution: 20-40 years most frequent
- Gender analysis: Slightly higher male victimization
- Exception: Identity theft shows higher female victimization

## Data Cleaning Process
1. Date and time formatting
   - Standardized date formats
   - Converted 24-hour time format
2. Missing data handling
   - Standardized gender categories (M, F, X)
   - Addressed age inconsistencies
3. Duplicate removal and outlier handling
4. Data type standardization

## Technologies Used
- Python
- Pandas for data manipulation
- Prophet for time series forecasting
- Matplotlib/Seaborn for visualizations
- GeoPandas for geographical analysis

## Model Performance
Prophet Model Metrics:
- MAE: 5.34
- MAPE: 0.091
- RMSE: 76.40

## Key Visualizations
1. Crime Rate Distribution Map
2. Time Series Analysis Plots
3. Demographic Distribution Charts
4. Economic Correlation Plots

## Future Work
- Integration of additional demographic factors
- Enhanced predictive modeling
- Real-time data integration capabilities
- Deeper analysis of specific crime categories

## Installation and Usage
1. Clone the repository
```bash
git clone https://github.com/NirmitSachde/Crime-Data-Analysis.git
```

2. Install required dependencies
```bash
pip install -r requirements.txt
```

3. Run Jupyter notebooks
```bash
jupyter notebook
```

## Contributors
Thanks to all team members who contributed to this analysis project!

## License
MIT License

---
*Note: This project was completed as part of IE6400 Foundations Data Analytics Engineering course at Northeastern University.*