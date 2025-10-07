# quant-ml-lab

ML-driven research and automation â€” feature engineering, ML models, training pipelines and evaluation.

## Structure
- `data/`       â€” raw and cleaned datasets
- `notebooks/`  â€” EDA and experiment notebooks
- `features/`   â€” feature engineering scripts and pipelines
- `models/`     â€” model code, training scripts, saved weights
- `systems/`    â€” orchestration: training / data pipeline / configs
- `evaluation/` â€” metrics, IC, backtests linked to ML signals
- `utils/`      â€” data loaders, time split helpers, common utils
- `tests/`      â€” unit tests for data transforms and pipelines

## Quickstart
1. Create a Python env (optional): `python -m venv .venv`
2. Install deps: `pip install -r requirements.txt`
3. Run `notebooks/` experiments and track results
