# Financial Risk Modelling Projects in Python

This repository contains Python-based academic projects focused on financial risk modelling, including credit risk, market risk, operational risk, fixed-income portfolio risk, and bankruptcy prediction.

The projects combine statistical modelling, simulation, risk measures, model backtesting, and machine learning techniques. They cover practical applications such as Value at Risk, Expected Shortfall, CreditMetrics-style portfolio simulation, operational loss modelling, and corporate bankruptcy prediction.

## Projects

### 1. Fixed-Income Credit VaR and Expected Shortfall

**File:** `Fixed_income_Var (3).html`

This project applies a CreditMetrics-style approach to measure credit risk in a fixed-income bond portfolio. It simulates rating migration scenarios, values bonds under different credit states, and estimates portfolio credit risk using Value at Risk and Expected Shortfall.

The project includes:
- bond portfolio valuation under different rating scenarios,
- rating migration simulation,
- Monte Carlo scenario generation,
- portfolio value distribution analysis,
- credit VaR estimation at the 99.9% confidence level,
- Expected Shortfall calculation,
- comparison of correlated and uncorrelated credit risk scenarios,
- interpretation of diversification and correlation effects.

**Main topics:** credit risk, fixed income, CreditMetrics, rating migration, Monte Carlo simulation, VaR, Expected Shortfall.

---

### 2. Market Risk VaR and ES Backtesting for AAPL

**File:** `Tymoteusz Hanusiak IMRR (3).html`

This project estimates and backtests market risk measures for Apple stock returns. It calculates simple and logarithmic returns, tests distributional assumptions, estimates VaR and Expected Shortfall using historical and Monte Carlo methods, and evaluates model performance through backtesting.

The project includes:
- downloading AAPL price data,
- calculation of simple and log returns,
- descriptive statistics and distribution analysis,
- normality testing using Jarque-Bera, Shapiro-Wilk, and Anderson-Darling tests,
- historical VaR and ES estimation,
- Monte Carlo VaR and ES estimation,
- rolling-window risk estimation,
- VaR breach analysis,
- Basel traffic-light backtesting,
- Kupiec test for unconditional coverage,
- Christoffersen independence test.

**Main topics:** market risk, Value at Risk, Expected Shortfall, backtesting, Kupiec test, Christoffersen test, financial time series.

---

### 3. Operational Risk Modelling with LDA

**File:** `VAR_OP (1).html`

This project analyzes operational risk losses using the Loss Distribution Approach. It models operational loss frequency and severity, fits statistical distributions, and estimates extreme operational risk measures such as 99.9% VaR and Expected Shortfall.

The project includes:
- introduction to operational risk and regulatory measurement methods,
- discussion of LDA and SMA approaches,
- exploratory analysis of operational loss data,
- analysis of business lines and loss event types,
- frequency distribution modelling,
- severity distribution fitting,
- goodness-of-fit testing,
- simulation of aggregate annual losses,
- operational VaR estimation at the 99.9% level,
- Expected Shortfall calculation.

**Main topics:** operational risk, Loss Distribution Approach, SMA, loss frequency, loss severity, VaR, Expected Shortfall, regulatory risk.

---

### 4. Bankruptcy Prediction for Polish Companies

**File:** `ryzyko22 (1).html`

This project studies bankruptcy prediction using financial ratios from the Polish Companies Bankruptcy dataset. It compares the traditional Altman Z-score approach with logistic regression and random forest models.

The project includes:
- loading the Polish Companies Bankruptcy dataset,
- exploratory analysis of financial ratios,
- implementation of an Altman-style bankruptcy model,
- model accuracy evaluation,
- bootstrap analysis of Altman model performance,
- logistic regression for bankruptcy classification,
- train-test split evaluation,
- cross-validation,
- random forest classification,
- missing value imputation,
- confusion matrix analysis,
- feature importance interpretation.

**Main topics:** credit risk, bankruptcy prediction, Altman Z-score, logistic regression, random forest, classification, financial ratios.

---

## Technologies

- Python
- pandas
- NumPy
- scipy
- statsmodels
- scikit-learn
- seaborn
- matplotlib
- yfinance
- ucimlrepo
- Jupyter Notebook / HTML notebooks

## Main Areas

- Credit risk modelling
- Market risk modelling
- Operational risk modelling
- Value at Risk
- Expected Shortfall
- Fixed-income portfolio risk
- Monte Carlo simulation
- VaR backtesting
- Bankruptcy prediction
- Financial machine learning
