# 📊 QUANT FINANCE CASE STUDIES

Rigorous, end-to-end quantitative finance case studies spanning derivatives pricing, portfolio construction, risk management, volatility modeling, and machine learning for markets. Each study includes clear problem framing, mathematical formulation, robust implementation, and empirical evaluation.

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)]()
[![Notebooks](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()
[![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)]()

---

## 🎯 Purpose

- Document real-world quant workflows as reproducible case studies.
- Bridge theory to practice with institutional-grade rigor.
- Provide clean, parameterized code and explainable results for interviews, research, and production prototyping.

---

## 🔬 Featured Case Studies

- Derivatives Pricing & Greeks
  - Black–Scholes–Merton with dividends, Greeks, implied vol inversion
  - Binomial/trinomial trees and Least-Squares Monte Carlo (American options)
  - Jump-diffusion (Merton/Kou) calibration and pricing
- Portfolio Construction
  - Mean–Variance with transaction costs and constraints
  - Black–Litterman with view confidence and market equilibrium
  - Risk Parity and Hierarchical Risk Parity (HRP)
  - Factor modeling (Fama–French, custom style factors)
- Risk Management
  - Parametric, Historical, and Monte Carlo VaR & Expected Shortfall
  - Backtesting (Kupiec, Christoffersen), procyclicality analysis
  - Stress testing (historical and hypothetical scenarios)
- Volatility & Term Structure
  - GARCH family (GARCH/EGARCH/GJR) with distributional choices
  - Stochastic Volatility (Heston) simulation and calibration
  - Volatility surface construction: smoothing, arbitrage checks
  - Yield curve bootstrapping, key rate duration, credit spreads
- Machine Learning for Markets
  - Regime detection (HMM), structural breaks
  - Alpha signals: tree-based, linear, and regularized models
  - Feature engineering, leakage control, walk-forward validation
  - RL agents for execution vs. directional policies (toy sims)

---

## 🧮 Methodology Standards

- Mathematical derivations with notation and assumptions
- Proper calibration objectives and validation splits
- Out-of-sample evaluation, robust metrics, and uncertainty quantification
- Reproducibility with fixed seeds and deterministic paths where applicable
- Clear separation between research code (notebooks) and reusable library code (src)

---

## 🛠️ Tech Stack

- Core: Python 3.9+, NumPy, Pandas, SciPy, Statsmodels
- ML: scikit-learn, xgboost/lightgbm (optional), PyTorch/TensorFlow (optional)
- Finance/Quant: pandas-datareader, yfinance, arch, QuantLib (optional)
- Visualization: Matplotlib, Seaborn, Plotly
- Utilities: Jupyter, tqdm, joblib, pydantic (optional)

---

## 📊 Evaluation & Reporting

- Performance: Sharpe, Sortino, Calmar, Information Ratio
- Drawdowns: magnitude, duration, recovery analysis
- Risk: ex-ante vs. ex-post, beta/active risk decomposition
- Statistical testing: bootstrap CI, reality-check style controls
- Transaction cost modeling and turnover constraints where relevant

---

## 📚 Documentation

- docs/math: derivations, assumptions, model diagrams
- docs/case_studies: narratives, figures, and result interpretation
- In-notebook references to methods and further reading

---

## 🧪 Testing


- Unit tests for core routines (pricing, Greeks, optimizers)
- Regression tests for calibration routines
- Seeded simulations for reproducibility

---

## 🧱 Data Policy

- No large datasets committed.
- Use small samples/synthetic data under data/ for structure only.
- For full experiments, use environment variables or config files to point to local or vendor data sources.

---

## 🤝 Contributing

Contributions are welcome:
- Add new case studies with clear structure and metrics
- Improve calibration routines and numerical stability
- Extend backtesting and risk modules
- Enhance documentation and tests

Please:
- Follow PEP 8, type-hint critical APIs
- Include tests and notebook outputs (light figures ok, avoid heavy artifacts)
- Add math notes if introducing new models

---

## ⚠️ Disclaimer

This repository is for research and education. It is not investment advice. Models are simplified and may fail under real-world conditions. Always validate with appropriate data, risk controls, and domain oversight.

---

## 📄 License

MIT. See LICENSE for details.

---

## 📬 Contact

- Author: Kai (Kai-tech-bit)
- Issues: use GitHub Issues
- Discussions/Requests: open a Discussion or Issue with [Feature] / [Bug] / [Case Study]



