# HW #4.3: Reproducible Data Analysis

This repository contains my HW 4.3 assignment for STAT 184. It includes a Quatro (.qmd) file used for simulation and data analysis, along with the final rendered PDF submission.

## Overview

This project presents a reproducible data analysis created using Quarto. It combines multiple components from prior coursework into a single, organized report that includes data wrangling, visualization, and written interpretation.
The project analyzes passenger traffic across six major airports over time and explores how simulation methods like Monte Carlo integration can approximate mathematical values. It also examines the use of generative AI tools by comparing a structured, plan-based prompt with a generic prompt to evaluate differences in output quality. The goal of this project is to demonstrate both technical data analysis skills and effective communication of results.

### Interesting Insight (Optional)

One key insight from this project is how the Monte Carlo simulation demonstrated that increasing the number of random sample points leads to more accurate estimates. At low sample sizes, results vary widely, but as the number of points increases, the estimate stabilizes and approaches the true value of 1 for the area under the standard normal curve.
![Monte Carlo Simulation](monte_carlo_small_multiple.png)

## Data Sources and Acknowledgements

- Airport passenger traffic data were scraped from: https://en.wikipedia.org/wiki/List_of_busiest_airports_by_passenger_traffic
- Calcium dataset provided by course materials (longitudinal study of calcium levels in women)
- This project also utilized:
  - R packages: {tidyverse}, {rvest}, {ggplot2}, {patchwork}
  - Microsoft Copilot (with enterprise data protection) for the generative AI comparison section

## Current Plan

This project serves as a foundation for future reproducible analyses. Future improvements could include:
- adding statistical analysis to compare trends between groups
- refining visualizations for clarity and presentation quality
- expanding the GenAI comparison to include multiple tools or prompts
This project may also be extended in future assignments as part of a larger workflow.

## Repo Structure

This repository is organized to support reproducibility and clarity:
- hw4.3.qmd -> Main Quarto document containing the full analysis
- hw4.3.pdf -> Rendered output for submission
- calcium.csv -> Dataset used for GenAI analysis
- monte_carlo_small_multiple.png -> Image used for Monte Carlo visualization
The Quarto document contains:
- main analysis sections (airports, Monte Carlo, GenAI comparison)
- appendices with code and AI usage documentation


## Authors

Gianna Kearns  
Pennsylvania State University  

For questions, please contact via Penn State email: gmk5637@psu.edu

updated on work branch
