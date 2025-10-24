# Emission_Analysis

# Emission Analysis of African Ruminant Diet Shifts

This repository accompanies the forthcoming manuscript **“Diet Shifts and Enteric Methane Emission Intensity in African Ruminant Systems”**, which quantifies how feeding interventions influence **enteric methane (CH₄) emission intensity (EI)** across **cattle, sheep, and goats** in African livestock production systems.

The analysis integrates more than **500 feeding trials** compiled in the **ERA v1.0.1** database, harmonized through a reproducible **Tier-2 emission pipeline**.  
The workflow links **diet composition**, **gross energy reconstruction**, **animal performance**, and **methane estimation** using IPCC Tier-2 equations to derive consistent estimates of **CH₄ emissions (g CH₄ animal⁻¹ day⁻¹)** and **emission intensity (g CH₄ kg⁻¹ product)**.

### Repository contents

- **`data/`** – Cleaned datasets used for analysis (e.g., `GE_combined.csv`, `yield_data.csv`, `practice_tbl.csv`, etc.).  
- **`scripts/`** – All R scripts and notebooks for data processing, merging, and visualization.  
- **`10_Emission_Analysis.Rmd`** – Main analysis notebook reproducing all figures and metrics reported in the paper.  

All analyses are fully reproducible in R (≥ 4.3.0) and rely on open-source packages including `dplyr`, `ggplot2`, `arrow`, and `DT`.

### GitHub Pages (interactive results)

Interactive visual summaries, maps, and emission-intensity figures are available on the project website:

👉 **[View Results on GitHub Pages](https://ERAgriculture/Emission_Analysis/10_Emission_Analysis.html)**

This page allows co-authors and collaborators to explore the key results directly—viewing emission-intensity distributions, ΔEI comparisons by practice, ingredient category, and species, as well as spatial coverage of the dataset.
