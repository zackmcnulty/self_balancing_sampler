# Self-Balancing Sampler Empirical Results

This repository contains the exploratory simulations and plots for the self-balancing sampler project.

## Contents

- `simulation.ipynb`: main notebook for empirical experiments, including convergence, predictability, and citizens' assembly simulations.
- `health_inspections.ipynb`: Analyzes the performance of the self-balancing sampler on the NYC OpenData [Health Inspections Dataset](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/about_data).
- `data`: Relevant data used in `health_inspections.ipynb`. 

## Usage

Open the notebook with Jupyter and run the cells in order:

```bash
jupyter notebook simulation.ipynb
```

or

```bash
jupyter lab simulation.ipynb
```

The notebook assumes the usual scientific Python stack is available, including `numpy`, `matplotlib`, `pandas`, `seaborn`, `scikit-learn`, and `tqdm`.
