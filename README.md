# INFO 6154 Assignment 1 - Pedro Aguiar

This repository contains work for INFO 6154 Assignment 1 by Pedro Aguiar.

## Files of interest

- `INFO_6154_Assignment_1_Pedro_Aguiar.ipynb` — Jupyter Notebook containing the assignment work.
- `AEP_hourly.csv` — Dataset used by the notebook (if applicable).

## Description

The notebook `INFO_6154_Assignment_1_Pedro_Aguiar.ipynb` includes analysis and code for the assignment. Open it with Jupyter Notebook or JupyterLab to run the cells. The notebook may expect the `AEP_hourly.csv` dataset to be in the same directory; adjust paths if you move files.

## Big picture

This notebook performs a full analysis pipeline on the provided dataset(s). At a glance, the project's purpose and flow are:

- Goal: analyze and model the time-series dataset(s) (for example energy consumption in `AEP_hourly.csv`) to extract insights and produce predictive models or visual summaries.
- Main steps:
  1. Load dataset(s) and inspect structure and basic quality checks.
  2. Data cleaning and preprocessing (handle missing values, type conversions, resampling or aggregation if needed).
  3. Exploratory data analysis (time-series plots, distributions, correlations, seasonal patterns).
  4. Feature engineering (create lag features, rolling statistics, datetime features).
  5. Model selection and training (baseline statistical models and/or machine learning / deep learning models depending on the notebook contents).
  6. Evaluation and visualization of results (error metrics, residual diagnostics, comparison plots).
  7. Export or save results (figures, model artifacts, summary tables).

- Expected outputs: figures and tables embedded in the notebook, model performance metrics, and any saved model/CSV files the notebook creates.

Add or adjust the above bullets to match specific modeling methods used in the notebook (for example ARIMA, Prophet, LSTM, etc.).

## How to run

1. Create and activate a Python environment (recommended).

   - Windows PowerShell (example):

     ```powershell
     python -m venv .venv; .\.venv\Scripts\Activate.ps1
     pip install -r requirements.txt
     jupyter lab
     ```

2. Open `INFO_6154_Assignment_1_Pedro_Aguiar.ipynb` in JupyterLab or Jupyter Notebook and run cells.

This repository references a `requirements.txt` for reproducible installs. You mentioned you already have a requirements file — keep it in the project root or update the path in the install command above if it's located elsewhere.

If you don't have a `requirements.txt`, install at least:

- jupyter
- pandas
- numpy
- matplotlib

## Notes

- Update the paths in the notebook if datasets are in subfolders.

## Contact

Pedro Aguiar
