# InsideAirbnb Temporal Dynamics

This project analyzes seasonal patterns and builds predictive models for nightly price and booking probability using InsideAirbnb data.

## Contents
- Night-level panel dataset construction
- Seasonality analysis for price and booking probability
- Temporal train/validation/test splits
- XGBoost and Neural Network models
- TensorBoard-based training analysis

## Dataset Source

All data comes from **InsideAirbnb**:

https://insideairbnb.com/get-the-data/

For each city, the following archived snapshots are used:

- **Austin:** December 14, 2024 and March 6, 2025  
- **Chicago:** December 18, 2024 and March 11, 2025  
- **Santa Cruz:** December 31, 2024 and March 28, 2025  
- **Washington, DC:** December 18, 2024 and March 13, 2025  

> **Note:** Raw InsideAirbnb CSV files are **not included** in this repository.
> Please download them manually and place them in the expected directory
> structure before running the notebook.


## How to Run
1. Place InsideAirbnb raw data under `data/raw/{city}/{snapshot_date}/`

2. Install dependencies:
pip install -r requirements.txt

3. Run the notebook:
notebook/insideairbnb_temporal_dynamics.ipynb


TensorBoard logs are stored in `logs/`, and screenshots are saved under `reports/tensorboardScreens/`.

## Data Source

This project uses publicly available InsideAirbnb data.

Listings and calendar files were downloaded from:
https://insideairbnb.com/get-the-data/

For reproducibility, the notebook documents all preprocessing steps.
Raw data files are not included in the repository due to size.
