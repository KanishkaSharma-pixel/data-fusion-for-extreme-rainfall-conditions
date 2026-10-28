# Western Himalaya Extreme Rainfall Analysis

## Overview
This project investigates localized extreme rainfall over the Western Himalayan region of India using environmental data analysis and multi-source data fusion.

## Objectives
- Explore rainfall distribution and spatiotemporal variability.
- Integrate rainfall observations with satellite precipitation, atmospheric reanalysis, and terrain features.
- Evaluate retrospective machine-learning approaches for extreme-rainfall classification.
- Examine the potential contribution of different data sources.

## Data Sources
- **IMD:** Rainfall observations used as the reference target.
- **GPM IMERG:** Satellite-derived precipitation.
- **ERA5:** Atmospheric variables.
- **DEM-derived features:** Elevation and slope characteristics.

## Methodology
1. Data preparation and quality assessment.
2. Exploratory data analysis.
3. Feature integration and rainfall-target construction.
4. Retrospective machine-learning experiments.
5. Model comparison using Average Precision, ROC-AUC, precision, recall, and F2-score.

## Important Limitations
The current experiments use a limited 2025 study period and a restricted spatial domain. The rainfall threshold used for classification is an exploratory extreme-rainfall definition, not an officially validated cloudburst label. The experiments do not establish operational forecasting capability or a validated early-warning system.

## Repository Contents
- `western-himalaya-extreme-rainfall-analysis.ipynb` — notebook containing the analysis and model results.

## Status
Research and exploratory analysis stage. Dataset validation, broader temporal evaluation, and further validation remain necessary.
