<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/OutliersAnalytics/outliersanalytics.github.io/main/assets/images/logo-dark.png" />
    <img src="https://raw.githubusercontent.com/OutliersAnalytics/outliersanalytics.github.io/main/assets/images/logo-light.png" alt="Outliers Analytics" width="420" />
  </picture>
</p>

---

**Outliers Analytics** is a data science organization focused on applying electoral and socio-demographic data to build data-driven strategies for elections. Our mission is to turn public data into actionable insight through rigorous analysis, modeling, and visualization.

In parallel with our applied work, we also develop and release open-source statistical tools for Python, aimed at making data science workflows cleaner, faster, and more effective.

## 🧰 Open-Source Tools

### [DadosAbertosBrasil](https://github.com/GusFurtado/DadosAbertosBrasil)

**DadosAbertosBrasil** is a Python package for accessing open data and APIs of the Brazilian
government, wrapping sources like IBGE, IPEA, and the Chamber of Deputies into a single
`pandas`-friendly interface:

- Socio-economic, demographic, and geographic series from IBGE
- Macroeconomic data from IPEA
- Legislative data from the Chamber of Deputies
- Helpers for cleaning and cross-referencing Brazilian datasets

### [MarkoWizard](https://github.com/OutliersAnalytics/MarkoWizard)

**MarkoWizard** is a Python toolkit for [Markowitz](https://en.wikipedia.org/wiki/Modern_portfolio_theory) mean-variance portfolio optimization.
It turns a table of asset returns into an efficient frontier and an optimal allocation, with:

- Efficient-frontier optimization via `scipy.optimize`
- Capital allocation line for mixing risky portfolios with a risk-free asset
- Plotly visualizations — efficient frontier, allocation pie, CAL, correlation heatmaps, price timelines
- Optional market-data fetching through [yfinance](https://github.com/ranaroussi/yfinance)
- An interactive FastAPI web app with a dark-themed frontend

Useful for analysts exploring risk-return trade-offs in asset allocation.

### [statsjunk](https://github.com/OutliersAnalytics/statsjunk)

**statsjunk** is a framework-free Python library of general-purpose statistical functions —
correlation, regression, spatial autocorrelation, and prediction-model sample size calculations:

- Pearson and Spearman correlation, with confidence intervals
- Simple and multiple linear regression
- Global Moran's I spatial autocorrelation
- Minimum sample size for prediction models (a Python port of R's `pmsampsize`)

Ideal for dropping a well-tested, typed statistical function into a pipeline without reaching for R.

### [Cellmate](https://github.com/OutliersAnalytics/cellmate)

**Cellmate** is a lightweight Python package for creating and managing styled Excel spreadsheets using [OpenPyXL](https://openpyxl.readthedocs.io/).  
It simplifies the process of generating reports with features like:

- Table formatting with headers and borders  
- Cell-level styling (alignment, font, number format, etc.)  
- Reusable components for programmatic report generation  
- Seamless integration into Python data pipelines

Ideal for data scientists and analysts who need to export structured reports directly from code.

## 📫 Contact

Got questions, suggestions, or collaboration ideas?  
Reach us via [LinkedIn](https://www.linkedin.com/in/gustavo-furtado/).
