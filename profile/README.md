<p align="center">
  <img src="https://raw.githubusercontent.com/OutliersAnalytics/.github/refs/heads/main/logos/logo_inline.png" alt="Outliers Analytics" />
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

### [Cellmate](https://github.com/OutliersAnalytics/cellmate)

**Cellmate** is a lightweight Python package for creating and managing styled Excel spreadsheets using [OpenPyXL](https://openpyxl.readthedocs.io/).  
It simplifies the process of generating reports with features like:

- Table formatting with headers and borders  
- Cell-level styling (alignment, font, number format, etc.)  
- Reusable components for programmatic report generation  
- Seamless integration into Python data pipelines

Ideal for data scientists and analysts who need to export structured reports directly from code.

More open-source statistical tools are in development and will be released here as they mature.

## 📫 Contact

Got questions, suggestions, or collaboration ideas?  
Reach us via [LinkedIn](https://www.linkedin.com/in/gustavo-furtado/).
