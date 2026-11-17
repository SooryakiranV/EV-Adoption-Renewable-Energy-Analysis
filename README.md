# EV Adoption and Renewable Energy Analysis

A notebook analysis of electric vehicle adoption and renewable electricity across countries.

## Results

The merged IEA Global EV Data 2024 and Our World in Data energy data contain 456 country-year observations. EV stock share and renewable electricity share are positively correlated: Pearson r = 0.44 overall, rising from 0.39 in 2013 to 0.72 in 2022. This is an association, not a causal result.

The notebook includes country-level visualisations and a yearly correlation analysis.

## Run

The notebook expects these CSV files in the repository root:

- `Global EV Data 2024 (1).csv`
- `owid-energy-data.csv`

Download the matching datasets from IEA Global EV Data 2024 and Our World in Data. The data files are not included here.

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
jupyter notebook ev_renewable_energy_analysis.ipynb.ipynb
```

Run the notebook cells in order after adding both CSV files.

## Topics

electric-vehicles, renewable-energy, data-analysis, pandas, jupyter-notebook
