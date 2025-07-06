
# 📈 Influence of Algorithmic Trading on Market Volatility

This repository explores the **impact of algorithmic trading on financial market volatility** using statistical modeling and time series analysis. The study aims to evaluate whether the increasing dominance of algorithmic trades contributes to market instability, specifically during periods of high-frequency trading activity.

---

## 📚 Project Overview

**Notebook:** `Influence_of_algorithmic_trading_on_market_volatility.ipynb`
This notebook performs:

* 📊 Exploratory Data Analysis (EDA) on trading and volatility metrics
* 📈 Time series decomposition and volatility modeling
* 🧠 Bayesian VAR modeling to capture market dynamics
* 📉 Evaluation of predictive power using R² and MAPE
* 📌 Interpretation of impulse response to algorithmic shocks

---

## 🔧 Tech Stack

| Component            | Tools/Libraries                            |
| -------------------- | ------------------------------------------ |
| Language             | Python                                     |
| Core Libraries       | `pandas`, `numpy`, `matplotlib`, `seaborn` |
| Statistical Modeling | `statsmodels`, `pmdarima`, `scikit-learn`  |
| Advanced Modeling    | `pyflux`, `bayesian-var` (if applicable)   |
| Notebook             | Jupyter Notebook                           |

---

## 📁 Repository Contents

```
.
├── Influence_of_algorithmic_trading_on_market_volatility.ipynb
└── README.md
```

---

## 🧠 Key Insights

* Bayesian VAR model achieved **R² ≈ 0.81**, suggesting strong predictive performance.
* Algorithmic trade volume has **positive impulse effects** on short-term volatility.
* Time series decomposition highlights cyclical patterns aligned with major economic events.

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/algorithmic-volatility-analysis.git
   cd algorithmic-volatility-analysis
   ```

2. Install dependencies (via pip or conda):

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Influence_of_algorithmic_trading_on_market_volatility.ipynb
   ```

---

## 📌 TODO

* [ ] Expand dataset with real-time feeds (e.g., NYSE/CRSP/Refinitiv)
* [ ] Integrate GARCH or EGARCH models for deeper volatility analysis
* [ ] Deploy insights via interactive dashboard

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

Dhiren Motwani
[Portfolio](https://www.dhirenmotwani.com/) | [LinkedIn](https://www.linkedin.com/in/dhirenmotwani/) | [GitHub](https://github.com/dhirenmotwani)


