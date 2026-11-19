# Electricity Generation Across Countries

**Module:** Data Exploration and Preparation (DEP) | **Domain:** Energy

## Research question
How do countries' electricity generation mixes differ, and which measures
(energy sources, demand per person, income, carbon intensity) explain the main
differences between countries?

## Tools
Python, pandas, matplotlib, seaborn, scikit-learn (Jupyter Notebook)


## Data
- **Source:** Our World in Data (OWID) energy dataset, Ritchie, Rosado and Roser (2024).
  https://ourworldindata.org/energy
- **How to get it:** download the energy dataset CSV from the link above and save it as
  `data/owid_energy.csv`. (The file is not stored in this repository because of its size.)
- **Size:** about 19,494 rows and 130 columns, one row per country per year.

## How to run
1. Install: `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
2. Put `owid_energy.csv` in the `data/` folder.
3. Open `notebooks/Electricity_Generation_Analysis.ipynb` and choose Run All.