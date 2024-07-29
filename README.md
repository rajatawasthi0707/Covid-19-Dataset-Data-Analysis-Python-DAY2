# Covid-19-Dataset-Data-Analysis-Python-DAY2
Covid-19-Dataset-Data-Analysis-Python-DAY2
# COVID-19 Data Analysis

This repository contains a comprehensive analysis of COVID-19 data, using a dataset that tracks confirmed cases, deaths, recoveries, and other related metrics across various countries and regions. The analysis includes visualizations and statistical insights to better understand the impact of COVID-19 worldwide.

## Data

The dataset used in this project is stored in `full_grouped.csv`. It includes the following columns:

- **Date**: The date of the record.
- **Country/Region**: The country or region where the data was recorded.
- **Confirmed**: Total number of confirmed COVID-19 cases.
- **Deaths**: Total number of COVID-19 related deaths.
- **Recovered**: Total number of recovered COVID-19 cases.
- **Active**: Total number of active COVID-19 cases.
- **New cases**: Number of new confirmed cases.
- **New deaths**: Number of new deaths.
- **New recovered**: Number of new recoveries.
- **WHO Region**: WHO region classification.

## Analysis

### Overview

1. **Data Import and Cleaning**: The dataset is loaded and checked for null values. It is confirmed to be clean and free from duplicates.
   
2. **Descriptive Statistics**: Basic statistics are computed for key metrics including confirmed cases, deaths, recoveries, active cases, and new cases.

### Visualizations

1. **Top 10 Countries by Total Confirmed Cases**: A bar plot shows the top 10 countries with the highest total confirmed COVID-19 cases.

   ![Top 10 Countries by Total Confirmed Cases](path/to/your/plot.png)

2. **Top 10 Countries by Total Deaths**: A bar plot displays the top 10 countries with the highest total COVID-19 deaths.

   ![Top 10 Countries by Total Deaths](path/to/your/plot.png)

3. **Top 10 Countries by Total Active Cases**: A bar plot illustrates the countries with the highest number of active COVID-19 cases.

   ![Top 10 Countries by Total Active Cases](path/to/your/plot.png)

4. **Distribution of Recovery Rate**: A histogram showing the distribution of the recovery rate across all records.

   ![Distribution of Recovery Rate](path/to/your/plot.png)

5. **Distribution of Death Rate**: A histogram showing the distribution of the death rate across all records.

   ![Distribution of Death Rate](path/to/your/plot.png)

6. **Correlation Matrix**: A heatmap displaying the correlation between confirmed cases, deaths, recoveries, and active cases.

   ![Correlation Matrix](path/to/your/plot.png)

7. **Scatter Plot of Confirmed Cases vs. Deaths**: A scatter plot showing the relationship between confirmed cases and deaths, with logarithmic scaling for clarity.

   ![Scatter Plot of Confirmed Cases vs. Deaths](path/to/your/plot.png)

## Installation

To run the analysis locally, you need Python along with the following packages:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

You can install the required packages using pip:

```bash
pip install numpy pandas matplotlib seaborn
