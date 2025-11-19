# ESG Optimization Project

This project looks at how portfolio weights change when sustainability constraints are added to a standard mean-variance optimization. Using historical returns together with ESG scores, the analysis compares:

- the unconstrained optimal portfolio (maximum Sharpe),
- portfolios with **higher ESG requirements**, and
- portfolios with **lower ESG requirements**.

The purpose is to see how introducing an ESG constraint affects both the risk–return profile and the resulting sustainability score.

## Contents
- **esg-optimization.ipynb** – main notebook containing all calculations
- **Datasets/** – return data and ESG scores used in the optimization

## What the notebook does
1. Loads return and ESG data  
2. Computes mean returns and the covariance matrix  
3. Solves the standard Sharpe-ratio optimization problem  
4. Applies ESG constraints above and below the baseline level  
5. Compares the resulting portfolios and visualizes the differences

## Requirements
The notebook uses the following Python libraries:

