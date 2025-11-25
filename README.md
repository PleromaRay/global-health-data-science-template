# global-health-data-science-template
Python + R template for global health data science (DHS, WHO, Malaria Atlas, Shiny, Streamlit)

A professional, immediately usable template for data science in global health — (starter kit) 2025

Works out-of-the-box with real, up-to-date global health datasets and best-practice workflows in **both Python and R**.

## What's Inside

- Real datasets auto-downloaded (DHS, WHO COVID, World Bank, Malaria Atlas, HDX, GADM boundaries)
- Ready-to-run Jupyter + RMarkdown notebooks (publication & ministry ready)
- Streamlit dashboard (Python) + Shiny dashboard (R)
- Bayesian modelling examples (PyMC + INLA)
- Reproducible environments (conda + renv)
- Quarto reporting template

## One-Command Setup

```bash
git clone https://github.com/yourusername/global-health-data-science-template.git
cd global-health-data-science-template

# Recommended: Python + R together
conda env create -f environment.yml
conda activate globalhealth

# Then download all datasets
python download_data.py   # or Rscript download_data.R
