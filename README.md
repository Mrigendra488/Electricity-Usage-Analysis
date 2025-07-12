# Electricity-Usage-Analysis

## Overview

This project provides a comprehensive analysis of electricity usage, focusing on consumption patterns across different geographical regions, countries, and energy sources. Using a detailed household-level dataset, it explores the relationships between electricity consumption (in KWH), energy sources (Biomass, Geothermal, Hydro, Solar, Wind), and socio-economic factors.

The primary goal is to derive actionable insights from the data through interactive visualizations. The centerpiece of this project is a Tableau dashboard that allows stakeholders to explore trends, compare metrics, and understand the dynamics of electricity consumption and cost savings.

## Key Features

- **Geographical Analysis**: Compares electricity usage (KWH) and a customer metric (CSU) across different regions and countries.
- **Energy Source Breakdown**: Analyzes the contribution and consumption patterns of various renewable energy sources.
- **Interactive Dashboard**: A user-friendly Tableau dashboard for dynamic data exploration with filters and drill-down capabilities.
- **Socio-Economic Insights**: The underlying dataset includes variables like household income, urban/rural location, and subsidy adoption, allowing for deeper analysis.

## Dataset Description

The analysis is based on a sample dataset with the following structure:

| Column                 | Description                                                  | Example Value      |
|------------------------|--------------------------------------------------------------|--------------------|
| `Household ID`         | A unique identifier for each household.                      | `H01502`           |
| `Region`               | The continent where the household is located.                | `North America`    |
| `Country`              | The country of the household.                                | `USA`              |
| `Energy_Source`        | The primary renewable energy source used.                    | `Hydro`            |
| `Monthly_L_Year`       | Monthly electricity consumption in KWH from the last year.   | `1043.49`          |
| `Year`                 | The year the data was recorded.                              | `2024`             |
| `Household_Income_Level` | A categorical rating of the household's income.            | `4 Low`            |
| `Urban_Rural`          | Specifies if the household is in an Urban or Rural area.     | `Rural`            |
| `Adoption_Subsidy`     | Indicates if a subsidy was adopted and the year.             | `2023 Yes`         |
| `RI_Cost_Savings_USD`  | The total cost savings in USD.                               | `10.46`            |

## Dashboard Insights

The Tableau dashboard visualizes key findings from the dataset:

- **Energy Source Dominance**: Wind power is the leading energy source, generating the highest KWH (232,968) and CSU (43,551) among all sources.
- **Regional Consumption**: South America is the top consumer of electricity in terms of KWH (166,019), while also leading in the CSU metric (32,625).
- **Country-Level Leaders**:
  - **Argentina** shows the highest KWH consumption among all countries.
  - **New Zealand** leads in the CSU metric.
- **Comparative Analysis**: The dashboard effectively allows for side-by-side comparisons, such as contrasting KWH usage by region versus by energy source, providing a multi-dimensional view of the data.

## Technologies Used

- **Data Visualization**: **Tableau** was used to create the interactive dashboard.
- **Data Processing**: **Python** (using libraries like Pandas and NumPy) or **SQL** can be used for data cleaning, transformation, and pre-processing.
- **Data Storage**: The dataset can be stored in flat files like **CSV** or in a relational database like **PostgreSQL** or **MySQL**.

## How to Use This Project

### Prerequisites

- **Tableau Desktop** or **Tableau Public** to open and interact with the dashboard file (`.twbx`).
- (Optional) **Python 3.x** with **Pandas** if you wish to perform your own data analysis.



### Interacting with the Dashboard

- Use the filters on the dashboard to narrow down the analysis by region, country, or energy source.
- Hover over bars and segments in the charts to see detailed tooltips with exact figures.
- Click on elements within one chart to see how they filter and affect the other charts on the dashboard.



