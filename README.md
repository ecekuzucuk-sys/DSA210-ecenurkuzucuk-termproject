# DSA210 - Term Project

## Urban Behavior Analysis Across Cities

This project investigates how environmental and contextual factors influence human mobility patterns across different cities.

---

## Cities

* Istanbul
* Ankara
* London

---

## Data Sources

* Google Community Mobility Reports
* Weather data (Open-Meteo)
* Air quality data (PM2.5)

---

## Research Questions / Hypotheses

* **H1:** Higher air pollution (PM2.5) decreases mobility
* **H2:** Weather conditions (temperature, precipitation) affect mobility
* **H3:** Mobility patterns differ between cities within the same country
* **H4:** Mobility patterns differ across countries

---

## Methodology

* Data collection from multiple sources
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* City-level aggregation (mean values)
* Visualization of mobility, air quality, and temperature
* Machine Learning modeling

---

## Machine Learning

Machine learning methods were applied to predict mobility levels.

### Models Used

* Linear Regression
* Random Forest Regressor

### Features

* City
* Month
* Day of week
* Weekend indicator
* Population density
* Coastal indicator

### Target

* Mobility level

---

## Key Findings

* Mobility levels vary across cities
* Istanbul shows higher air pollution levels compared to others
* Environmental factors (PM2.5, weather) influence mobility patterns
* Random Forest performed better than Linear Regression, suggesting non-linear relationships
* Mobility differences across cities indicate structural and environmental impacts

---

## Limitations

* Data from different sources could not be perfectly aligned by date
* Analysis is limited to three cities
* Some features (e.g., weather) are aggregated rather than fully synchronized

---

## Future Work

* Improve time alignment across datasets
* Add more cities and features
* Apply more advanced machine learning models
* Perform deeper statistical and causal analysis

---

## Repository Structure

* `urban_behavior_analysis.ipynb` → Main analysis notebook
* `data/` → Raw datasets

---

## Project Status

✔ Data collection completed
✔ Data cleaning and preprocessing
✔ Exploratory Data Analysis (EDA)
✔ Visualization and comparison across cities
✔ Machine Learning modeling

---
