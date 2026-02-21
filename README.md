# Deep Learning Housing Price Prediction (Boston Housing Regression)

Predict housing prices using a deep learning regression model trained on the Boston Housing dataset.

## Problem
Housing price prediction is a classic regression task where the goal is to estimate a continuous target value (price) from multiple input features (e.g., crime rate, number of rooms, tax rate, etc.).

## What I built (in the notebook)
- Loaded the Boston Housing dataset for a regression task
- Split data into training/testing sets
- Performed preprocessing (standardization/normalization for stable training)
- Built a feed-forward neural network (Dense layers) for regression
- Trained the model and monitored loss/metrics over epochs
- Evaluated the model on test data and analyzed prediction quality

## Files in this repo
- `BostonHousingProce_First_Deep_Learning_code(Regression).ipynb` — complete notebook (data prep → model → training → evaluation)

## Tech stack
- Python
- Jupyter Notebook
- TensorFlow / Keras (deep learning model)
- NumPy / Pandas (data handling)
- Matplotlib (plots)

## How to run
### Option 1: Run locally (recommended)
```bash
# create env
python -m venv .venv
# mac/linux
source .venv/bin/activate
# windows
# .venv\Scripts\activate

# install dependencies
pip install numpy pandas matplotlib jupyter tensorflow

# start notebook
jupyter notebook
