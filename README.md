# CMAPSS Predictive Maintenance (Blackbox Project)

### Overview
This repository contains a focused machine learning project (often referred to as the "Blackbox Project") aimed at predicting the **Remaining Useful Life (RUL)** of turbofan engines using the foundational **CMAPSS (Commercial Modular Aero-Propulsion System Simulation)** dataset. 

Predictive maintenance models are essential in modern industrial applications, as they forecast equipment degradation over consecutive cycles. This enables engineers to prevent sudden breakdowns, plan downtime effectively, and significantly cut operation costs.

### Key Highlights
- **Data Pre-processing Pipeline:** Cleans and processes complex, multi-sensor, time-series engine data alongside specific operational condition settings.
- **RUL Calculation and Mapping:** Automatically computes and aligns the target variable (Remaining Useful Life) across different engine units to properly format the regression task.
- **Robust Feature Structuring:** Utilizes a custom, iterative data generator approach to appropriately handle disjointed engine trajectories, readying the sequences for advanced model training.

### Files
- `C_mapssModel.ipynb`: The primary Jupyter Notebook containing the full workflow from data loading and preprocessing to model definition.

### How to use
1. Clone the repository: `git clone (https://github.com/Vicky-cmd-run/Black-Box.git)`
2. Ensure you have the standard data science stack installed (e.g., Python 3, `pandas`, `numpy`, `scikit-learn`, `matplotlib`).
3. Launch Jupyter Notebook or VS Code to run `C_mapssModel.ipynb`.
