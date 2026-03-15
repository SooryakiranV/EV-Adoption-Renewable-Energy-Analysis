# EV Adoption & Renewable Energy Analysis

Data analysis project exploring the relationship between electric vehicle adoption and renewable energy share across countries (2010–2023).

# Results

- Pearson correlation of r = 0.78 (p < 0.05) between EV stock share and renewable energy share — suggesting countries investing in renewables are also accelerating   EV adoption
- Analysed 100,000+ records across 2010–2023 from two real-world datasets

# Dataset

- IEA Global EV Data 2024
- Our World in Data (OWID) energy dataset
- Resolved country name mismatches and applied per-country linear interpolation to fill short time-series gaps

# Tech Stack
 
  Python · Pandas · NumPy · Plotly · Seaborn · Matplotlib · SciPy · Jupyter Notebook

# Key Features

- Animated Plotly scatter visualisation with country-level trajectories and year-slider controls
- Quadrant shading to identify high EV + high renewables leaders vs laggards
- Yearly Pearson correlation trend analysis showing strengthening relationship over time
