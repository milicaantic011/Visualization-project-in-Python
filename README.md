# COVID-19 Data Visualization Project

## Overview
This project focuses on applying Python libraries for **data visualization**, including **Seaborn**, **Plotly**, and **Dash** to analyze the global COVID-19 pandemic.
The project is divided into several parts that, when combined, form a comprehensive analysis of pandemic trends worldwide.

---

##  Development Setup
- **Programming Language**: Python 3.x
- **Libraries Used**: `pandas`, `matplotlib`, `seaborn`, `plotly`, `dash`
- **Development Environment**: Visual Studio Code
- **Final Output**: Jupyter Notebook (`*.ipynb` format)

---

## Dataset
The dataset is sourced from the GitHub repository of **[Our World In Data](https://github.com/owid/covid-19-data)**, which provides a comprehensive knowledge base on the **COVID-19 pandemic (2020 onward)**.

For the purposes of this project:
- Unnecessary columns were removed
- Geographic coordinates were added for mapping visualizations

**File used**: `project_1_python.csv`

---

## Data Cleaning
During the project, **rows with missing values (`NaN`) were removed** for the selected metrics.
This ensured that all visualizations only included valid and complete data for accurate representation.

---

## 📋 Dataset Features

| Feature | Description |
|---------|-------------|
| `iso_code` | ISO country code |
| `continent` | Continent of the country |
| `location` | Country name |
| `total_cases` | Total number of reported cases |
| `new_cases` | Newly reported cases (per day) |
| `total_deaths` | Total number of deaths |
| `new_deaths` | Newly reported deaths (per day) |
| `hosp_patients` | Number of hospitalized patients |
| `total_tests` | Total number of performed tests |
| `new_tests` | Newly performed tests (per day) |
| `tests_per_case` | Tests conducted per detected case |
| `total_vaccinations` | Total vaccinations administered |
| `people_vaccinated` | People vaccinated (at least one dose) |
| `people_fully_vaccinated` | People fully vaccinated |
| `total_boosters` | Booster doses administered |
| `new_vaccinations` | New vaccinations administered (per day) |
| `population` | Population of the country |
| `median_age` | Median age of the population |
| `gdp_per_capita` | Gross Domestic Product per capita |
| `life_expectancy` | Life expectancy in the country |
| `latitude` | Country latitude |
| `longitude` | Country longitude |

---

## Problem Statement
The project aims to **analyze the course of the COVID-19 pandemic worldwide**, focusing on:
- Dynamics of cases and deaths over time
- Testing rates and effectiveness
- Hospitalization patterns
- Vaccination progress across countries
- Demographic factors affecting pandemic impact

---

## Visualizations

### 1. Cases by Country Map
![Cases by Country Map](Cases%20by%20Country%20Map.png)
Geographic distribution of COVID-19 cases worldwide.

### 2. Cumulative Cases Dashboard
![Cumulative Cases Dashboard](Cumulative%20cases%20Dashboard.png)
Interactive dashboard showing cumulative case trends over time.

### 3. New COVID Cases Timeline
![New Covid Cases](New%20Covid%20Cases.png)
Daily new case counts showing pandemic waves and peaks.

### 4. Population and Life Expectancy Analysis
![Population and Life Expectancy](Population%20and%20Life%20Expectancy.png)
Correlation between demographic factors and COVID-19 impact.

### 5. Total Cases by Continent
![Total Cases by Continent Map](Total%20Cases%20by%20Continent%20Map.png)
Continental breakdown of total COVID-19 cases.

---

##  Solution
A comprehensive data visualization and analysis notebook developed in **Visual Studio Code**, with the final solution exported as a `*.ipynb` file containing:
- Interactive visualizations using Plotly
- Statistical analysis with Seaborn
- Geographic mapping of pandemic spread
- Time series analysis of case trends
- Demographic correlation studies

---

## 📁 Project Structure


##  Project Structure

```


---
COVID-19-Visualization-Project/
│
├── Visualization project in Python.ipynb  # Main notebook with analysis
├── project_1_python.csv                   # Dataset file
├── Cases by Country Map.png               # World map visualization
├── Cumulative cases Dashboard.png         # Dashboard visualization
├── New Covid Cases.png                    # Time series visualization
├── Population and Life Expectancy.png     # Demographic analysis
├── Total Cases by Continent Map.png       # Continental breakdown
└── README.md                              # Project documentation

---

##  Author

**Milica Antic**  
- GitHub: [@milicaantic011](https://github.com/milicaantic011)
- LinkedIn: [Milica Antic](https://www.linkedin.com/in/milica-antic-ds/)

---

##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

##  Acknowledgments

- Data source: Kaggle Airline Delays Dataset
- Inspiration: Impact of COVID-19 on aviation industry
- Tools: Plotly for interactive visualizations

---

*Last Updated: September 21, 2025*
