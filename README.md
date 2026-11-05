# MATH840: Time Series Final Project

48-hour electricity generation forecasts with 95% prediction intervals.

## Files

- `01_eda_ets_snaive.ipynb` - EDA and the first submission: ETS + seasonal naive.
- `02_daylight_ensemble.ipynb` - the submitted Daylight MLP ensemble.
- `REPORT.ipynb` - methodology, results and limitations.
- `data/` - the two supplied CSV files.

## Run

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Open `02_daylight_ensemble.ipynb` in Jupyter and run all cells in order. It runs independently of notebook 01 and trains the models without checkpoints.

In Colab, run the installation cell and upload `train.csv` and `weather_forecast.csv` before loading the data.

The forecast is saved to `submissions/daylight_ensemble_reproduced.csv`. 

## LLM use

Before the competition, I prepared a knowledge base with reusable code blocks, common pitfalls and important checks.

Throughout the project, Codex acted as an assistant with the relevant project and course context. It helped assemble code blocks for comparing models, applying the appropriate workflow for each model and preparing clean, reproducible final notebooks.

Claude was occasionally used for an outside perspective and critical feedback.
