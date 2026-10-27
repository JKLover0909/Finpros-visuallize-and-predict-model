# AGENTS.md

## Overview
Stock price-change prediction exercise (intern test): visualizes intraday price data for four Vietnamese stocks (FPT, MSN, PNJ, VIC) and fits regression models with scikit-learn. Educational only — not investment advice.

## Layout
- `Nguyen_Dinh_Son_InternTest_PredictStock.ipynb` — the whole analysis (pandas, seaborn, plotly, scikit-learn); written for Google Colab.
- `FPT.csv`, `MSN.csv`, `PNJ.csv`, `VIC.csv` — 1-minute bars: `Ticker,Date/Time,Open,High,Low,Close,Volume,Open Interest` (~100k–135k rows each, starting Dec 2018).

## Commands
- Install: `pip install pandas numpy scikit-learn matplotlib seaborn plotly`
- Run: `jupyter notebook Nguyen_Dinh_Son_InternTest_PredictStock.ipynb` (or upload to Colab; the notebook reads the CSVs from a path variable such as `file_path_fpt` — point it at the repo files).

## Rules
- Do not modify the CSV data files; they are the raw inputs.
- Keep `Date/Time` parsing consistent (`MM/DD/YYYY H:MM`).
- Do not present model outputs as financial advice.
