# InsideAirbnb Temporal Dynamics

This project analyzes seasonal patterns and builds predictive models for nightly price and booking probability using InsideAirbnb data.

## Contents
- Night-level panel dataset construction
- Seasonality analysis for price and booking probability
- Temporal train/validation/test splits
- XGBoost and Neural Network models
- TensorBoard-based training analysis

## How to Run
1. Place InsideAirbnb raw data under `data/raw/{city}/{snapshot_date}/`

2. Install dependencies:
pip install -r requirements.txt

3. Run the notebook:
notebook/insideairbnb_temporal_dynamics.ipynb


TensorBoard logs are stored in `logs/`, and screenshots are saved under `reports/tensorboardScreens/`.
