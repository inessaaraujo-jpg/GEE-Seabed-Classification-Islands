# GEE-Seabed-Classification-Islands
removal of sun glint
# GEE-Seabed-Classification-South-Atlantic-Islands

This repository contains the Google Earth Engine (GEE) scripts and methodology developed for the multi-decadal classification of seabed sediment cover in the Rocas Atoll and Fernando de Noronha Archipelago (South Atlantic).

## Project Overview
This study utilizes a 24-year time series (1999–2023) of Landsat (5, 7, 8, 9) and Sentinel-2 imagery to map benthic habitats and sediment dynamics. The workflow includes:
- **Deglint Processing:** Sun glint removal for improved seabed detection.
- **Machine Learning:** Implementation of the Random Forest algorithm for sediment classification.
- **Temporal Analysis:** Assessment of sediment mobility and burial risks for coral reefs and rhodolith beds.

## Repository Structure
- `/scripts`: Contains the `.js` files to be used in the Google Earth Engine Code Editor.
  - `01_preprocessing_deglint.js`: Script for atmospheric correction and glint removal.
  - `02_random_forest_classifier.js`: The core machine learning classification code.
- `/assets`: (Optional) Sample points or metadata descriptions.

## How to Use
1. Copy the code from the scripts in the `/scripts` folder.
2. Paste it into the [Google Earth Engine Code Editor](https://code.earthengine.google.com/).
3. Adjust the "Date Range" and "Study Area" variables as needed.
4. Run the script to generate the classified maps.

## Requirements
- A Google Earth Engine account.
- Basic knowledge of JavaScript for GEE.

## Contact
**Inessa Amancio** - inessa.araujo@ufpe.br
Federal University of Pernambuco (UFPE), Brazil.
