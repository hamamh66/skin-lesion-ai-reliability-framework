# Skin Lesion AI Reliability Framework

## Overview
This repository provides a reproducible machine learning pipeline for skin lesion classification with a strong focus on reliability, robustness, and interpretability.

## Key Features
- Ensemble-based classification (ExtraTrees, Random Forest, Voting)
- Cross-validation stability analysis
- Robustness evaluation under perturbations (noise, brightness, contrast)
- Calibration and reliability analysis (reliability diagrams, calibration gap)
- Entropy-based uncertainty modeling
- Explainability via global feature importance and sensitivity analysis

## Methodology Highlights
The framework integrates predictive performance with:
- Calibration-aware evaluation
- Perturbation-based robustness analysis
- Feature importance and sensitivity consistency

## Outputs
All experiments automatically generate:
- Figures (calibration, robustness, importance maps)
- Tables (performance, cross-validation)
- Summary reports

## Reproducibility
- Fixed random seeds
- Structured experiment outputs
- End-to-end pipeline included

## Usage
Run the main notebook or pipeline script to reproduce all results and figures.

## License
MIT License
