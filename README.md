# Plantation Mapping in Sumatra Using SAR, Optical, and Ancillary Data

This repository supports the code and data references used in the study currently under peer review:  
**"Integrating SAR and Optical Data with Contextual Ancillary Layers for Precise Plantation Mapping in Sumatra, Indonesia"** by Adzan et al.

## Repository Content

- `scripts/`: Google Earth Engine code for image preparation, feature extraction, and Random Forest classification (Model 3).
- `data/`: Information and links to source datasets (Sentinel-1, Sentinel-2, GEDI, SRTM, etc.).
- `model/`: Top variable importance metrics from the Random Forest classification.

## Data Sources

All datasets used are publicly available and accessed via Google Earth Engine:
- Sentinel-1 SAR: `COPERNICUS/S1_GRD`
- Sentinel-2 MSI: `COPERNICUS/S2_SR`
- SRTM DEM: `USGS/SRTMGL1_003`
- Dynamic World Land Cover: `GOOGLE/DYNAMICWORLD/V1`

## Code Availability

Core classification and preprocessing code was written in the [Google Earth Engine Code Editor](https://code.earthengine.google.com/).  
A sample version of the main script is included in `scripts/gee_classification_model3.js`.

> **Note:** The manuscript is currently under review and this repository may be updated following peer review and acceptance.

## License

This repository is licensed under the MIT License. You are free to use and adapt the code with attribution.

## Contact

For questions or collaboration, please contact: gemasakti.adzan@wri.org
