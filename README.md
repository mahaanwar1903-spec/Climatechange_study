
Visualizing Climate Change
# Temperature & Rainfall Trends over 50 Years

> An exploratory data analysis project using Python to uncover long-term climate patterns through visualizations — built as part of BS Data Science coursework at the University of Agriculture Faisalabad.


# 📌 Project Overview

This project tells a data-driven story about climate change by analysing two independent real-world datasets spanning over 50 years. The analysis is split into three focused notebooks, each with a distinct purpose, and brought together in a final correlation analysis.
| `TEMPvisuals.ipynb` | Global land temperature trends, heatmaps, and anomaly detection |
| `Rainfallvisuals.ipynb` | Pakistan rainfall trends, variability, distribution, and decadal shifts |
| `Climaterelation.ipynb` | Cross-variable correlation between temperature and rainfall |

# Visualizations

The project produces **9 charts** across the three notebooks:
**Temperature Analysis**
- Global Temperature Heatmap (Year × Month)
-  Temperature Trend with 5-Year Rolling Average & Trend Line
-  Temperature Trend with Hottest Year (2015) & Coldest Year (1976) annotated

**Rainfall Analysis**
-  Rainfall Trend with Highest (1994) & Lowest (2000) Year annotated
-  Rainfall Variability Over Time (Rolling Std Dev)
- Average Rainfall by Decade (1970s – 2010s)
-  Distribution of Yearly Rainfall (Histogram + KDE)
-  Box Plot of Yearly Rainfall

**Correlation**
 Temperature vs Rainfall Regression Scatter Plot
- 
# 🗂️ Datasets

**GlobalTemperatures.csv** — Berkeley Earth Surface Temperature Study (via Kaggle). Monthly global land surface temperature from 1750 to 2015, filtered to 1970 onward. Columns used: `dt`, `LandAverageTemperature`.
**Rainfall_1901_2016_PAK.csv** — Pakistan Meteorological Department / World Bank Climate Portal. Monthly Pakistan rainfall from 1901 to 2016, filtered to 1970 onward. Columns used: `Year`, `Month`, `Rainfall - (MM)`.

## Key Findings

**Temperature:** Global land temperature rose by ~1°C over the 50-year window. 2015 was the hottest year (~9.83°C) and 1976 the coldest (~8.37°C). Warming is distributed across all months of the year, not just summer.
**Rainfall:** Pakistan's annual rainfall shows no strong directional trend, but volatility is high. 1994 was the wettest year (~424 MM) and 2000 the driest (~194 MM) — a difference of over 100% within just six years.
**Correlation:** The regression scatter shows a weak positive relationship between global temperature and Pakistan rainfall. The wide confidence interval confirms that temperature alone is a poor predictor — local monsoon dynamics dominate.

## 🛠️ Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## ⚙️ Usage
Run the notebooks in this order: `TEMPvisuals.ipynb` → `Rainfallvisuals.ipynb` → `Climaterelation.ipynb`


# 📁 Project Structure
```
climate-change-visualization/
├── TEMPvisuals.ipynb
├── Rainfallvisuals.ipynb
├── Climaterelation.ipynb
├── GlobalTemperatures.csv
├── Rainfall_1901_2016_PAK.csv
└── README.md
```
# Author
**Maha Anwar** · BS Data Science, 4th Semester · University of Agriculture Faisalabad
