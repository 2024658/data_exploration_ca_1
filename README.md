# Electricity Generation Across Countries

**Module:** Data Exploration and Preparation (DEP) | **Domain:** Energy

## Research question
How do countries' electricity generation mixes differ, and which measures
(energy sources, demand per person, income, carbon intensity) explain the main
differences between countries?

## Tools
Python, pandas, matplotlib, seaborn, scikit-learn (Jupyter Notebook)

## Data
- **Source:** Our World in Data (OWID) energy dataset, Ritchie, Rosado and Roser (2023).
- **Included in this repository:** `owid_energy.csv` (and the same data as
  `owid_energy.xlsx`), 19,494 rows and 130 columns, one row per country per year.
  OWID updates the file, so a newer download may give slightly different results.
  Latest version: https://github.com/owid/energy-data

## How to run
1. Install: `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
2. Keep `owid_energy.csv` in the same folder as the notebook (it is already here).
3. Open `Electricity_Generation_Analysis.ipynb` and choose Run All.

## References
Jolliffe, I.T. and Cadima, J. (2016) 'Principal component analysis: a review and recent developments', *Philosophical Transactions of the Royal Society A*, 374(2065), 20150202. Available at: https://doi.org/10.1098/rsta.2015.0202 (Accessed: 16 November 2026).

Pedregosa, F. et al. (2011) 'Scikit-learn: machine learning in Python', *Journal of Machine Learning Research*, 12(85), pp. 2825–2830. Available at: https://jmlr.org/papers/v12/pedregosa11a.html (Accessed: 9 November 2026).

Ritchie, H., Rosado, P. and Roser, M. (2023) 'Energy', *Our World in Data*. Available at: https://ourworldindata.org/energy (Accessed: 4 November 2026).

Our World in Data (n.d.) *Energy dataset* [Dataset]. Available at: https://github.com/owid/energy-data (Accessed: 4 November 2026).