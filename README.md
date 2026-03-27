# Replication Package for Problem Set 3 - Computational Methods
**Author:** Georges Mikhael Andraus, Sao Paulo School of Economics - FGV

---

## 1. Overview

This repository contains the code and documentation required to replicate the results for Problem Set 3. The analysis covers the topics of optimization, numerical integration and numerical differentiation.

**AI Usage Declaration:**  
Parts of the code and the LaTeX structuring of this project were developed with the assistance of an LLM (Gemini 3.1 Pro Preview). The AI was primarily used to implement good computational practices, such as writing modular functions with defensive programming and formatting the results for LaTeX. All logic and final interpretations are my own.

---

## 2. Repository Structure

```text
.
├── Code/
│   └── Main.R                  # Master script for optimization and integration
├── Output/
│   ├── Tables/                 # Stargazer LaTeX outputs
│   └── Figures/                # Optimization trace plots
├── Other/
│   └── Latex/                  # PDF and .tex response files
├── renv/                       # R environment isolation files
├── ComputationalMethods-PSet03.Rproj 
└── README.md
```

## 3. Instructions

The computational environment is managed by `renv`. To replicate the results:
1. Open the `ComputationalMethods-PSet03.Rproj` file in RStudio.
2. Run `renv::restore()` in the console to install all specific package versions.
3. Execute `Code/Main.R` to generate all tables and figures.
