# DSA210 - Term Project

# Urban Behavior Analysis Across Cities

This project investigates how environmental and social factors influence human mobility behavior across different cities using mobility, weather, and air quality datasets.

---

# Project Overview

Human mobility patterns are strongly affected by environmental conditions, transportation systems, and urban structure. This study analyzes mobility behavior in three major cities:

- Istanbul
- Ankara
- London

The project combines mobility reports, weather information, and air quality measurements to explore differences in urban movement patterns across cities and countries.

---

# Data Sources

The datasets used in this project were collected from publicly available sources:

- Google Community Mobility Reports
- Open-Meteo Weather API
- PM2.5 Air Quality Data

---

# Research Questions / Hypotheses

The project investigates the following hypotheses:

- **H1:** Higher air pollution (PM2.5) decreases mobility.
- **H2:** Weather conditions affect mobility patterns.
- **H3:** Mobility differs between Istanbul, Ankara, and London.
- **H4:** Mobility patterns differ across countries.

---

# Methodology

The project workflow consists of the following steps:

1. Data collection from multiple sources
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. City-level aggregation and comparison
5. Mobility visualization across cities
6. Machine Learning model implementation
7. Feature importance analysis

---

# Exploratory Data Analysis (EDA)

The EDA section includes:

- Mobility trend visualization over time
- Distribution comparison between cities
- Country-based mobility analysis
- Transportation-related mobility investigation
- PM2.5 air quality comparison
- Mobility variability analysis

---

# Machine Learning Models

Machine learning models were implemented to predict mobility behavior.

## Models Used

- Linear Regression
- Random Forest Regressor

## Features Used

- Grocery and pharmacy mobility
- Parks mobility
- Transit stations mobility
- Workplaces mobility
- Residential mobility
- Month
- Day of week

## Target Variable

- Retail and recreation mobility

---

# Results

The machine learning analysis produced the following results:

- Random Forest performed better than Linear Regression.
- Transit station mobility was the strongest predictor of mobility changes.
- Grocery and pharmacy mobility also had significant impact.
- Temporal variables such as month and day of week showed smaller effects.

---

# Visualizations Included

The project includes several visual analyses:

- Mobility comparison across cities
- Mobility distribution boxplots
- PM2.5 comparison charts
- City-level environmental comparisons
- Feature importance visualizations
- Time-series mobility trends

---

# Key Findings

The analysis revealed several important insights:

- Mobility patterns vary significantly across cities.
- Transportation-related mobility strongly influences urban movement.
- Environmental conditions may affect human behavior.
- Urban structure and country differences create distinct mobility patterns.
- London showed different mobility behavior compared to Ankara and Istanbul.

---

# Repository Structure

```plaintext
urban-behavior-analysis/
│
├── urban_behavior_analysis.ipynb
├── README.md
├── urban_behavior_analysis_complete.docx
├── data/
│   ├── mobility_data.csv
│   ├── weather_data.csv
│   └── air_quality_data.csv
│
├── report/
│   └── figures/
│
└── outputs/
    ├── graphs/
    └── model_results/
```

---

# Milestone 1 Progress

Completed tasks:

- Data collection
- Initial preprocessing
- Exploratory Data Analysis
- Visualization development
- City-level comparison

---

# Milestone 2 Progress

Completed tasks:

- Machine learning implementation
- Model evaluation
- Feature importance analysis
- Research question refinement
- Final visualization improvements

---

# Future Improvements

Possible future extensions include:

- More advanced statistical testing
- Additional environmental variables
- Deep learning approaches
- More cities and countries
- Real-time mobility prediction

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

# Author

DSA210 Term Project  
Urban Behavior Analysis Across Cities
