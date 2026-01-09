# Algorithmic Profiling of Operational Risk Datasets

This repository contains the synthetic datasets and replication code associated with the paper:
**"Algorithmic Profiling of Operational Risk: A Data-Driven Predictive Model for Micro-Enterprise Solvency Assessment"**

## Contents

1. **micro_enterprise_solvency_dataset.csv**: 
   - The processed dataset used for training the XGBoost model.
   - **N = 5,000** unique entities.
   - **Target:** `Default` (0 = Solvent, 1 = Default).
   - **Key Features:** Transaction Variance, Supplier Latency (Normalized), Login Frequency.

2. **raw_transaction_logs_sample.csv**: 
   - A sample of raw transactional logs (JSON-structure flattened).
   - Demonstrates the difference between "Rhythmic" (Solvent) and "Volatile" (High Risk) operational patterns as described in Figure 2 of the manuscript.

## Usage
These datasets are intended for reproducing the results presented in the study, specifically the comparative analysis between Logistic Regression and XGBoost.

## Citation
If you use this data, please cite the original paper:
> Pérez-Salazar, J., Márquez, N., & Vidal-Silva, C. (2025). Algorithmic Profiling of Operational Risk: A Data-Driven Predictive Model for Micro-Enterprise Solvency Assessment. *Computers*, 1(0).
