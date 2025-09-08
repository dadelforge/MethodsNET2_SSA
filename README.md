# MethodsNET2_SSA

This repository provides supporting materials for the short training session "Exploring, Denoising, and Filtering Time Series with Singular Spectrum Analysis" delivered at the MethodsNET 2nd Conference (Louvain-la-Neuve, Belgium; 10–12 September 2025). It contains a hands-on Jupyter notebook and links to the public data used in the exercises.

## Contents
- 250910_SSA_MethodsNET2.pdf — slide deck used during the short training session
- hands_on_tutorial.ipynb — step-by-step SSA walkthrough (decomposition, grouping, reconstruction, visualization)
- Data sources:
  - DOI: https://doi.org/10.2908/DEMO_R_MWK3_TS
  - Eurostat API (weekly mortality, BE31): https://ec.europa.eu/eurostat/api/dissemination/sdmx/3.0/data/dataflow/ESTAT/demo_r_mwk3_ts/1.0/*.*.*.*?c[freq]=W&c[sex]=T&c[unit]=NR&c[geo]=BE31&&compress=false&format=csvdata&formatVersion=1.0&lang=en&labels=label_only&sinceTimePeriod=2001&untilTimePeriod=2024

## How to use
1. Open hands_on_tutorial.ipynb in Jupyter (or JupyterLab).
2. Run cells sequentially to reproduce the SSA analysis and plots.



## Terms of use
All data are subject to the licensing terms of their respective providers (see linked sources). The notebook and accompanying materials are shared for educational purposes.

If you refer to this material or presentation, please use or adapt the following citation:

Delforge, D. (2025, September 10–12). Exploring, Denoising, and Filtering Time Series with Singular Spectrum Analysis (short training session). MethodsNET 2nd Conference, Louvain-la-Neuve, Belgium.