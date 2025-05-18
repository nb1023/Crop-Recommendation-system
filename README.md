This repository presents a data-driven crop recommendation system aimed at enhancing agricultural productivity, especially in regions like Latur district, Maharashtra, where traditional crop selection methods are no longer sufficient due to:

- Deteriorating soil health

- Unpredictable rainfall patterns

- Diminishing groundwater reserves

The system integrates multi-source datasets, including:

- Satellite-derived indices (NDWI, SMI, MSI)

- Ground truth soil properties (pH, EC, NPK, OC, Fertility)

- Crop labels from real-world data

This solution enables data-informed crop decisions, minimizing losses and boosting productivity for farmers and agricultural planners.

## Technologies Used

- Google Earth Engine (GEE) – for remote sensing and vegetation index computation

- Python – for data processing, modeling, and analysis

- Scikit-learn, XGBoost, LightGBM – for machine learning

- GridSearchCV – for hyperparameter tuning

- Stratified K-Fold Cross-Validation – for performance evaluation

## Data Sources
1. Sentinel-2 Satellite Imagery
- 13 spectral bands used

- Computation of:

- NDWI (Normalized Difference Water Index)

- SMI (Soil Moisture Index)

- MSI (Moisture Stress Index)

2. Ground Truth Soil Data

- Soil attributes:

- pH

- Electrical Conductivity (EC)

- Phosphorus

- Potassium

- Nitrogen

- Organic Carbon

- Fertility Level

- Crop labels from farmer records in Latur, Maharashtra
