# Uncertainty quantification for nutrient retention during boiling

Parametric uncertainty analysis supporting the manuscript "A multiphysics computational framework for quantifying 
nutrient retention in domestic cooking", Journal of Food Engineering (under review).

## Purpose

This analysis recovers the thermal-dose history of a completed simulation from the run's 
output, then re-evaluates beta-carotene retention under different kinetic parameters without re-running the simulation. 

Includes local sensitivity analysis, Monte Carlo propagation and Sobol variance attribution.

## Files

- `uncertainty_quantification.ipynb` — the analysis
- `Results - 20min cold start.csv` — reference run output (stainless steel 304, 60 kW/m2, cold start, 20 min)

## How to run this analysis

Open file in Google Colab, upload the CSV when prompted in step 0, run all cells.
Requires numpy, pandas and matplotlib.

## Simulation code

As of September 18, 2026, the simulation that produced the input is at https://github.com/Amankrah/boiling-sim
