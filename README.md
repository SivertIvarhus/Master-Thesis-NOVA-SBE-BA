# Who Benefits from AI? Heterogeneous Effects of AI Tool Adoption on Developer Job Satisfaction

Master's thesis (Directed Research) — MSc Business Analytics, Nova SBE

## Overview

This thesis investigates the causal effect of AI tool adoption on software developer job satisfaction, with a focus on how this effect varies across developer subgroups. It uses the 2025 Stack Overflow Developer Survey and applies causal machine learning methods (Double ML and causal forests).

## Research Questions

1. Does AI tool adoption increase or decrease job satisfaction for developers on average?
2. Does the effect differ by experience level, organization size, and developer role?
3. What characterizes the developers who benefit most from AI adoption versus those who are harmed?

## Methods

- **Double/Debiased Machine Learning (DML)** — Average Treatment Effect
- **Causal Forests** — Conditional Average Treatment Effects (heterogeneity)
- Sensitivity analysis for unobserved confounding

## Repository Structure

```
.
├── data/
│   ├── raw/            # Original survey data (not committed — see .gitignore)
│   └── processed/      # Cleaned, analysis-ready data
├── notebooks/          # Jupyter notebooks for exploration and analysis
│   ├── 01-data-exploration.ipynb
│   ├── 02-data-cleaning.ipynb
│   ├── 03-descriptive-analysis.ipynb
│   └── 04-causal-analysis.ipynb
├── src/                # Reusable Python modules
├── results/
│   ├── figures/        # Generated plots
│   └── tables/         # Generated tables
└── docs/               # Proposal, notes, references
```

## Data

The 2025 Stack Overflow Developer Survey is publicly available under the Open Database License at https://survey.stackoverflow.co/. The raw data is not committed to this repository due to size; download it and place it in `data/raw/`.

## Setup

```bash
pip install -r requirements.txt
```

## Author

Sivert — MSc Business Analytics, Nova SBE
Supervisor: Professor Michail
