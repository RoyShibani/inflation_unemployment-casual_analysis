# Inflation_unemployment-causal_analysis
## Causal Analysis of Interest Rates on GDP Growth

This repository contains a Python implementation of a causal analysis examining the effect of **interest rates on GDP growth** using global macroeconomic data from 2010–2023. The analysis combines **Difference-in-Differences (DiD)** and **Double Machine Learning (DML)** to estimate causal effects.

This project was completed as a class project for a **Causal Inference** course and is included here as part of my academic portfolio for graduate program applications.

---

## Project Overview

Interest rates are a key tool of monetary policy, but identifying their causal impact on economic growth is challenging because policy decisions respond to economic conditions.  
This project addresses that challenge by applying modern causal inference methods to real-world data.

The Python script in this repository:
- loads and cleans panel data,
- estimates a DiD model with fixed effects,
- implements cross-fitted DML using Random Forests,
- compares the two causal estimates,
- and produces diagnostic plots.

---

## Data

The analysis uses a global dataset of economic indicators (2010–2023), including:

- GDP growth rate  
- Interest rate  
- Inflation rate  
- Unemployment rate  
- Stock index value  
- Country and date identifiers  



---

## Methods 

**Difference-in-Differences (DiD):**  
Compares GDP growth between high-interest and low-interest countries before and after 2017.

**Double Machine Learning (DML):**  
Uses machine learning to control flexibly for confounders and estimate the marginal causal effect of interest rates on GDP growth.

Using both methods provides complementary evidence for causal interpretation.

---

## Main Findings

From this analysis:
- DiD suggests that high-interest countries experienced higher GDP growth after 2017.  
- DML indicates a positive marginal effect of interest rates on GDP growth after accounting for nonlinear confounders.  

Both approaches point to a consistent positive relationship in this dataset.

---

## References

- Chernozhukov, V. et al. (2018). *Double/debiased machine learning*. The Econometrics Journal.  
- Hansen, C., & Chernozhukov, V. (2021). *Machine learning for causal inference*. Annual Review of Economics.  
- Phillips, A. W. (1958). *The Phillips curve*. Economica.  
- Stock, J. H., & Watson, M. W. (2019). *Slack and cyclically sensitive inflation*. Journal of Money, Credit and Banking.

---


