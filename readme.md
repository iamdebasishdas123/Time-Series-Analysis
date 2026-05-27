
# 📈 Time Series Analysis — Complete Practical Guide

This repository contains a single, comprehensive Jupyter Notebook that demonstrates core concepts and practical techniques in time series analysis using real-world datasets.

- Notebook: [time_series_analysis.ipynb](time_series_analysis.ipynb)

## Overview

The notebook walks through foundations, decomposition, stationarity testing and transformations, forecasting models (univariate & multivariate), smoothing methods, evaluation metrics, and preprocessing techniques. It uses three example datasets provided by `statsmodels`:

- Mauna Loa CO₂ (monthly, via `sm.datasets.co2`)
- Sunspot activity (annual, via `sm.datasets.sunspots`)
- US macroeconomic data (quarterly, via `sm.datasets.macrodata`)

## Contents (Notebook Sections)

0. Load Real-World Datasets
1. Foundations — definitions and characteristics
2. Decomposition — classical and STL comparisons
3. Stationarity — tests (ADF, KPSS) and transformations
4. Forecasting Models — ACF/PACF, ARIMA, SARIMA, VAR
5. Smoothing Methods — MA, EMA, Holt(-Winters)
6. Evaluation Metrics — MAE, RMSE, MAPE, AIC
7. Data Pre-processing — missing values, outliers, resampling
8. Full End-to-End Pipeline checklist

## Requirements

Install the required Python packages (recommended in a virtual environment):

```bash
python -m venv .venv
source .venv/Scripts/activate   # Windows PowerShell: .venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install numpy pandas matplotlib statsmodels scipy scikit-learn jupyter
```

## Quick Start

1. Open the notebook in Jupyter:

```bash
jupyter notebook time_series_analysis.ipynb
```

2. Run cells sequentially. The notebook includes visualizations and example model fits for each major topic.

## Datasets

All datasets are loaded directly from `statsmodels` within the notebook (no external downloads required). See the dataset-loading cell in the notebook for details and frequency/resampling applied.

## Notes

- The notebook uses a dark matplotlib style and customized plotting parameters for readability.
- If you prefer reproducible runs, consider creating a `requirements.txt` or `environment.yml` from your environment after installing packages.

---

If you want, I can also generate a `requirements.txt` file or add runnable examples (scripts) to reproduce specific figures outside the notebook. Would you like that?
