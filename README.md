# Life Expectancy and GDP — Starter Analysis

Short project summary
- Exploratory analysis of life expectancy at birth and aggregate GDP for six countries (2000–2015).
- Includes EDA, visualizations (boxplots, time series, scatter facets, heatmap).
Files
- `life_expectancy_gdp.ipynb` — primary Jupyter notebook with data loading, plots and written interpretation.
- `all_data.csv` — dataset (Country, Year, Life expectancy at birth (years), GDP).

Key analyses & visuals included
- Boxplots (all countries; filtered without Zimbabwe) to show distribution and outlier influence.
- Time series plots of GDP (absolute and zoomed views) highlighting growth patterns and the 2008–2009 slowdown.
- Per-country GDP vs life-expectancy scatter panels to inspect within-country trajectories and yearwise movement.
- Heatmap (years × countries) for life expectancy trends and convergence signals.
- Narrative interpretation and concise data‑science recommendations included in notebook markdown.

Main findings (concise)
- GDP: US and China dominate in absolute size; China shows the strongest absolute growth. Zimbabwe has a very small, volatile GDP series.
- Life expectancy: increases for all countries; Zimbabwe is a low outlier but shows the largest absolute improvement.
- Relationship: positive but diminishing association between GDP and life expectancy; large GDP gains at high income produce smaller health gains.
- Analytic caveat: small sample (6 countries), aggregate GDP (not per‑capita) and omitted confounders limit causal claims.

Notes & limitations
- Treat Zimbabwe as an influential case when computing global summaries.
- Axis limits and scale choices affect comparability — prefer log scale or per-capita normalization for cross-country comparisons.

License & contact
- Project for learning/portfolio purposes. Cite sources if reused.
- For questions or improvements, open an issue or edit the notebook.
