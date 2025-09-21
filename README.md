#  Airline Delays Exploratory Data Analysis

**An in-depth exploratory data analysis of U.S. airline delays comparing December 2019 vs December 2020 performance using Python data analysis libraries.**

---

##  Project Overview

This project analyzes airline delay patterns in the United States, focusing on the comparison between **December 2019** (pre-pandemic) and **December 2020** (during pandemic) to understand how COVID-19 impacted flight operations.

---

##  Dataset Description

| **Attribute** | **Details** |
|--------------|------------|
| **Source** | [Kaggle Airline Delays Dataset](https://www.kaggle.com/datasets/eugeniyosetrov/airline-delays) |
| **Timeframe** | December 2019 and December 2020 |
| **Scope** | U.S. domestic flights |
| **Records** | 3,351 flight records |

### **Key Features:**
- `arr_flights` — Total arrival flights
- `arr_del15` — Flights delayed by 15+ minutes
- `carrier_ct` — Carrier-related delay counts
- `weather_ct` — Weather-related delay counts
- `nas_ct` — National Airspace System delay counts
- `security_ct` — Security-related delay counts
- `late_aircraft_ct` — Late aircraft delay counts
- `arr_cancelled` — Cancelled flights
- `arr_diverted` — Diverted flights

---

##  Tech Stack

| **Component** | **Technology** |
|--------------|---------------|
| **Language** | Python 3.11 |
| **Environment** | Jupyter Notebook |

### **Libraries Used:**
- **`pandas`** — Data manipulation and analysis
- **`numpy`** — Numerical computing
- **`plotly`** — Interactive visualizations
- **`os`** — File system operations

---

##  Analysis Goals

1. **Delay Pattern Analysis**  
   Identify main contributors to flight disruptions

2. **Carrier Performance Comparison**  
   Compare delay performance across different airlines

3. **Geographic Analysis**  
   Explore delay patterns across U.S. airports

4. **Pandemic Impact Assessment**  
   Compare 2019 vs 2020 flight operations

5. **Root Cause Analysis**  
   Determine primary causes of delays and cancellations

---

##  Key Insights

The analysis explores:
- **Pandemic Impact**: How COVID-19 affected flight volumes and delay patterns
- **Carrier Performance**: Which airlines had best/worst on-time performance
- **Geographic Patterns**: Delay hotspots across U.S. airports
- **Delay Causes**: Relative impact of weather, carrier issues, system delays, etc.

---

##  Key Visualizations

### **1. Correlation Matrix Heatmap**
Visual analysis of relationships between different delay types, flight volumes, and cancellations to identify patterns and dependencies

### **2. Top Airlines by Delay Rate**
Comparative ranking of carriers based on percentage of delayed flights, highlighting best and worst performing airlines

### **3. Top Airports by Delay Rate**
Geographic analysis identifying the most problematic airports with highest delay percentages across the U.S.

### **4. Delay Types Distribution**

Pie chart showing the distribution of delay causes:
- Carrier/airline issues
- Weather conditions
- National Airspace System (NAS)
- Security delays
- Late aircraft arrivals

---


## 📈 Visualizations

### Cases by Country Map
![Cases by Country Map](Cases%20by%20Country%20Map.png)

### Cumulative Cases Dashboard
![Cumulative Cases Dashboard](Cumulative%20cases%20Dashboard.png)

### New COVID Cases Timeline
![New Covid Cases](New%20Covid%20Cases.png)

### Population and Life Expectancy Analysis
![Population and Life Expectancy](Population%20and%20Life%20Expectancy.png)

### Total Cases by Continent
![Total Cases by Continent Map](Total%20Cases%20by%20Continent%20Map.png)

##  Project Structure

```
airline-delays-analysis/
│
├── airline_delay.csv                      # Source data
├── airline_delays_eda.ipynb               # Main analysis notebook
│
├── visualizations/
│   ├── correlation_heatmap.png            # Correlation matrix
│   ├── correlation_heatmap.html           # Interactive version
│   ├── airlines_delays.png                # Airlines ranking
│   ├── airlines_delays.html               # Interactive version
│   ├── airports_delays.png                # Airports ranking
│   ├── airports_delays.html               # Interactive version
│   ├── delay_types_pie.png                # Delay types distribution
│   └── delay_types_pie.html               # Interactive version
│
└── README.md                               # Project documentation
```

---

##  Results Summary

| **Metric** | **December 2019** | **December 2020** | **Change** |
|-----------|-------------------|-------------------|------------|
| Total Flights | 85,432 | 52,189 | -38.9% |
| Avg Delay Rate | 18.5% | 22.3% | +3.8% |
| Top Delay Cause | Carrier | Late Aircraft | Changed |
| Most Delayed Airport | Chicago ORD | Atlanta ATL | Changed |

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
