# The Impact of Visual Distraction on Reaction Time in Spot It!

This repository contains a statistical analysis project completed during my undergraduate studies at the University of Toronto.

The project investigates how increasing visual distraction affects participant accuracy and reaction time in a visual spot-the-difference task, using classical statistical modeling and hypothesis testing in R.

---

## Project Overview

Participants were shown pairs of images under varying levels of visual distraction and asked to identify differences within a fixed time window. The goal was to quantify how distraction influences:

- Identification accuracy  
- Reaction time  
- Performance trends across difficulty levels  

The analysis focuses on measuring correlation, fitting regression models, conducting ANOVA tests, and validating assumptions through diagnostic plots.

---

## Methods and Tools

- **Language:** R  
- **Visualization:** ggplot2  
- **Statistical techniques:**
  - Pearson correlation tests  
  - Linear regression  
  - ANOVA  
  - Residual diagnostics and model validation  

---

## Repository Contents

- **InputModeling.R** — Data ingestion, preprocessing, and exploratory calculations  
- **StatsTesting.R** — Statistical modeling, hypothesis testing, regression, and ANOVA  
- **PDF report** — Final written analysis with methodology, results, and interpretation  
- **README.md** — Project documentation  

---

## Analytical Questions

- Does increasing visual distraction significantly reduce participant accuracy?
- Is reaction time positively associated with difficulty level?
- Are the observed relationships statistically significant?
- Do linear model assumptions hold for the collected data?

---

## Future Work

If I were extending this project today, I would explore:

- Increasing the sample size and number of repeated trials  
- Randomizing experiment order to reduce learning effects  
- Mixed-effects or hierarchical models to account for participant-level variation  
- Bootstrapped confidence intervals for regression estimates  
- Non-linear relationships between distraction and performance  
