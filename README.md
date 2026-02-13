# California Housing: Statistical Analysis & Pipeline
**Project Source:** Based on Advanced Statistics Lab (Problem 2)

## 📊 Project Overview
This project replicates a legacy statistical analysis of the California Housing dataset, migrating from Mathematica to a modern Python-based data pipeline. It focuses on identifying data artifacts, testing statistical assumptions, and quantifying correlations.

## 🛠️ Technical Achievements
- **Data Pipeline:** Engineered a cleaning workflow to handle CamelCase renaming and identify 207 missing values in the `totalBedrooms` feature.
- **Anomaly Detection:** Identified "Censored Data" (Spikes) at 52 years for age and $500k for value; filtered 2,068 unreliable records to improve model validity.
- **Normality Testing:** Implemented Q-Q (Quantile-Quantile) plots using `scipy.stats` to prove house prices follow a non-normal distribution with heavy tails.
- **Categorical Analysis:** Aggregated 18,000+ records to determine that `oceanProximity` significantly influences price, with `ISLAND` and `NEAR BAY` commanding the highest premiums.
- **Correlation Mapping:** Quantified feature importance using Pearson Correlation coefficients, identifying `medianIncome` as the primary driver of property valuation.

## 🐍 Tech Stack
- **Language:** Python 3.11
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, SciPy