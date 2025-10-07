# 🤖 Quant ML Lab  
**Machine Learning Systems for Signal Discovery, Prediction, and Portfolio Automation**

---

## 🔍 Overview
The **Quant ML Lab** explores the intersection of **quantitative finance and machine learning**, building modular, end-to-end research systems for feature engineering, signal discovery, model-based forecasting, and portfolio optimization.

It bridges **financial domain expertise** with **ML systems engineering** — spanning the full lifecycle from data ingestion to model evaluation and alpha tracking.

---

## 🎯 Objectives
- Engineer robust **financial features** and alpha signals  
- Train and evaluate **ML models** for return and volatility forecasting  
- Automate **data-to-signal pipelines** using modular systems design  
- Apply **explainability (SHAP, feature importance)** to quantify model intuition  
- Benchmark classical quant factors vs. deep learning and RL-based models  

---

## 📁 Repository Structure
| Folder | Description |
|--------|--------------|
| `data/` | Market and engineered datasets used for ML experiments |
| `notebooks/` | EDA, model training, and signal validation notebooks |
| `features/` | Feature engineering — factors, spreads, volatility regimes |
| `models/` | ML models (regressors, ensembles, deep networks, RL agents) |
| `systems/` | End-to-end pipelines integrating data, features, and models |
| `evaluation/` | Model evaluation — IC, hit ratio, alpha decay, and backtest metrics |
| `utils/` | Helper functions for logging, data loading, and plotting |
| `tests/` | Unit tests ensuring correctness and reproducibility |

---

## 🧰 Tech Stack
- **Core:** Python, Pandas, NumPy  
- **ML:** Scikit-learn, XGBoost, PyTorch, TensorFlow  
- **Visualization:** Plotly, Matplotlib, SHAP  
- **Automation:** Joblib, YAML configs, GitHub Actions  
- **Finance APIs:** yfinance, FRED, Quandl  

---


## 📈 Research Directions
- Regime detection using clustering & HMMs  
- Alpha factor engineering and feature selection  
- Portfolio optimization via reinforcement learning  
- Volatility forecasting using deep neural networks  
- Explainability-driven model evaluation  

---

## 🤝 Contributing
This project evolves continuously with new research directions.  
Contributions are welcome via:
- Pull requests with new models, pipelines, or features  
- Reporting issues related to bugs or reproducibility  
- Sharing datasets or alternative evaluation approaches  

---

## 📜 License
This project is released under the **MIT License** — free to use, modify, and distribute with attribution.  
*(Add full license text in a separate LICENSE file if desired)*

---

## 🧩 Author
**Vivek Sarma** — Quant Finance & ML Research  
*Exploring the convergence of Financial Markets, Data Science, and Systematic Research.*

🔗 [GitHub Profile](https://github.com/viveksarmar)

## 🚀 Quickstart
```bash
# (1) Optional: create and activate virtual environment
python -m venv .venv
.\.venv\Scripts\Activate.ps1

# (2) Install dependencies
pip install -r requirements.txt

# (3) Launch Jupyter Lab or run training pipeline
jupyter lab
