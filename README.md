# Tejeshwar Singh

**Quantitative Researcher — Volatility, Derivatives & Regime Modeling**

> *Price tells you what happened. Volatility tells you what the market believes.*
> *I build systems that read the second signal.*

---

## What I Do

I research the structure of volatility — not as a risk metric, but as a lens into market positioning, collective fear, and regime transitions.

My work sits at the intersection of statistical inference, derivatives theory, and systematic research design. The goal is always the same: compress what would take an analyst hours of manual surface reading into a structured, repeatable, auditable research thesis.

The research philosophy is buy-side in orientation — signal quality, regime awareness, and risk-conditioned sizing — with sell-side rigour in the underlying methodology — surface construction, Greeks approximation, and stochastic modelling foundations.

---

## Research Mindset

Three questions drive every piece of work:

**1. Is this signal real or noise?**
Most patterns in financial data are coincidence. Every signal goes through stationarity testing, distributional diagnostics, and out-of-sample validation before it enters a research framework.

**2. Even if real — is it already priced?**
The edge is rarely in the signal itself. It is in the conditions under which the signal is valid — the regime, the carry environment, the stress state, the surface stability. Conjunction matters more than any single indicator.

**3. Even if valid — what breaks it?**
A research thesis without explicit invalidation conditions is incomplete. Every recommendation carries a scenario analysis showing what vol expansion, vol compression, and adverse spot shocks do to the position.

---

## Core Knowledge Areas

**Volatility & Derivatives**
Options surface analysis · Implied volatility structure · IV skew and convexity · Term structure dynamics · Volatility risk premium (VRP) · Put-call asymmetry · Greeks (Delta, Gamma, Theta, Vega) · Black-Scholes framework · Stochastic volatility intuition (Heston, SABR) · Carry and roll-down

**Statistical & Stochastic Modelling**
GARCH(1,1) volatility clustering · ARIMA time series · ADF / KPSS stationarity testing · Gaussian Mixture Models (GMM) · Principal Component Analysis (PCA) · Maximum Likelihood Estimation (MLE) · Bayesian updating · Monte Carlo simulation · Brownian Motion and GBM · Itô's Lemma foundation

**Econometrics**
OLS and multiple regression · Heteroskedasticity and autocorrelation diagnostics · Durbin-Watson · Breusch-Pagan · VIF multicollinearity · Robust standard errors · Newey-West

**Risk & Regime**
Regime detection and classification · Tail risk measurement · Excess kurtosis and fat tail identification · Stress scoring (hybrid realized + implied) · Percentile-based self-calibrating thresholds · Scenario analysis · Risk-conditioned position sizing

**Research Infrastructure**
Pipeline architecture · Signal inheritance and single source of truth design · Probabilistic state representation · Contradiction detection and feedback loops · Research note generation

---

## Technical Stack

```
Language     Python 3.x

Data         pandas · numpy · yfinance

Statistics   scipy.stats · statsmodels · arch · pmdarima

Machine      scikit-learn · GaussianMixture · PCA
Learning     StandardScaler

Optimisation cvxpy · scipy.optimize

Visualisation matplotlib · seaborn

Symbolic     sympy

Quant        QuantLib (foundation)
```

## How I Think About Markets

Volatility is not a risk metric. It is the market's collective opinion made visible — on fear, on positioning, on how far uncertainty extends through time.

The options surface shows you five things that price alone cannot:

```
Skew        → What the market fears
Term Slope  → How far out that fear extends  
VRP         → Whether fear is overpriced or underpriced
Convexity   → How the market is pricing tail events
Stability   → How confident the market is in its own view
```

This is why derivatives research is not a subset of equity research. It is a different information channel — one that carries the nervous system of the market, not just its price.

---

## Currently Researching

- Horizon-matched VRP — aligning IV and RV measurement windows to the same expiry horizon
- Out-of-sample regime validation — does GMM classification at *t* predict realized vol over the next *N* days?
- Forward vol curve extraction — computing explicit F(t,T) forward implied vol from the ATM term structure
- Regime-conditional stress weights — fixed hybrid stress weights are a known limitation; optimal weights likely shift by regime type

---

*Built on the belief that the most important signal in markets is the one most people aren't reading.*
