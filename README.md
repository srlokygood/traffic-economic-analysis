# Does Traffic Congestion Track GDP per Capita? Evidence from 15 Latin American Cities (2024)

I compared congestion, travel times, and GDP per capita across 15 Latin American cities in 2024. I found no clear, consistent relationship between wealth and congestion. Mexico City combined high GDP per capita with the highest congestion in the sample, while Montevideo combined high GDP per capita with low congestion.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)

## Business Question

Does urban traffic congestion relate to a city's economic productivity? Answering this helps urban planners and infrastructure decision-makers judge whether economic development and mobility problems move together, and which unusual cases deserve further study.

## Data

- **Period:** 2024
- **Coverage:** 15 Latin American cities
- **Files used:** ladb_mobility_economy_2024_clean.csv

## Process

- **Integration:** traffic and GDP datasets combined with an `INNER JOIN`-style merge on city and year.
- **Aggregation:** metrics aggregated by city and year.
- **Analysis:** exploratory data analysis (EDA), correlation analysis, and outlier detection.
- **Visualization:** Matplotlib and Seaborn.

```python
# [MISSING: 1-2 representative code snippets, e.g. the merge and the correlation]
```

## Findings

1. No clear, consistent relationship between GDP per capita and traffic congestion appeared across the cities analyzed.
2. Montevideo combined relatively high GDP per capita with low congestion, while Mexico City had high GDP per capita and the highest congestion in the sample.
3. Brazilian cities showed relatively favorable economic indicators with low traffic delay. Countries are unequally represented in the sample, so this needs further investigation.

## Recommendations

- Do not treat GDP per capita alone as a predictor of congestion when prioritizing mobility projects.
- Investigate outlier cities such as Mexico City and Montevideo to understand what drives their different outcomes (for example transit coverage, urban layout, and policy).
- Expand the sample with more cities per country and more years before using the results for infrastructure planning.

## Limitations

- The results show observed associations in the 2024 data, not causality.
- The sample is small (15 cities) and countries are unequally represented.
- A single year of data cannot capture trends over time.
- The data is not sufficient to decide infrastructure investment priorities on its own.

## How to Open It

- Python: install the dependencies from `requirements.txt` and open the notebook (S5_ladb_mobility_economy_project_student.ipynb).

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn
