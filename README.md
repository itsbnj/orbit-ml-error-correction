Project Overview
This project explores improving satellite orbit prediction accuracy by correcting classical SGP4 propagation errors using machine learning models trained on historical Two-Line Element (TLE) data.

Problem Statement
Traditional orbit propagation models accumulate error over time. This project investigates whether a lightweight machine learning model can learn systematic error patterns and reduce position prediction error.

Dataset
Public Two-Line Element (TLE) data from CelesTrak for the International Space Station (ISS).

Method

1. Parse historical TLE data

2. Propagate orbits using SGP4

3. Compute positional error over time

4. Train a machine learning model to predict and correct error residuals

Results
Baseline propagation error: TBD
ML-corrected error: TBD

How to Run

1. Install dependencies
   pip install -r requirements.txt

2. Run notebooks in order
   notebooks/01_data_exploration.ipynb
   notebooks/02_baseline_propagation.ipynb
   notebooks/03_ml_model.ipynb

Next Steps

1. Test additional satellites

2. Improve feature engineering

3. Evaluate longer prediction horizons
