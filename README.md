# BSAD 482 – Milestone 3: Causal Inference & Correlation Analysis

By: Adriel Uangbaoje

## Project Overview

This project analyzes the rise in femicide in Canada from 2008 to 2022 using a cleaned homicide dataset. The goal is to identify regional and demographic patterns, visualize trends over time, and explore possible causal relationships using correlation analysis.

The complete notebook can be found in [`milestone3.ipynb`](milestone3.ipynb).

---

## VISUALIZATIONS

### 1. Correlation Matrix

![Correlation Matrix](visualizations/Correlation%20Matrix.png)

I observed a moderate correlation (`r ≈ 0.22`) between femicide numbers and population-adjusted rates, while age showed a weaker relationship. This implies population size may play a stronger role than age in regional femicide prevalence.

---

### 2. Homicide Trends Over Time by Region

![Homicide Trends by Region](visualizations/Homicide%20Trend.png)

The **Americas** and **Europe** regions showed a strong upward trend from 2013–2020, peaking around 2019. Other regions remained relatively stable, indicating regional concentration of rising homicide rates.

---

## Causal Inference Summary

While some variables are correlated, this does not imply causation. Without additional socioeconomic, legal, or cultural data, I cannot draw definitive causal conclusions. However, the observed trends support the idea that regional conditions may influence femicide rates — a topic worth deeper investigation.

---

## Files in This Repo

- `milestone3.ipynb`: Main notebook with code and analysis  
- `visualizations/Correlation Matrix.png`: Correlation heatmap  
- `visualizations/Homicide Trend.png`: Regional trend line plot  

---

## 🧾 Author

Adriel – BSAD 482 | Decision Intelligence  
March 2025
