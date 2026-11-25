# FIN-417 — Project 1, Group H

Open `Project_template.ipynb` in the project folder alongside `QRM_2026_Project_prices.csv`, restart the kernel and run all cells in order. The notebook uses NumPy, pandas, SciPy, Matplotlib, statsmodels and arch. It writes the figures and backtest CSV files to `output/`. The random seed for the ES simulations is 0.

## Where to find the report results

| Report item | Notebook section | Result |
|---|---|---|
| Figure 1 | Q1(a), daily returns | `q1a_returns.png` |
| Figure 2 and Table 1 | Q1(b), autocorrelations and Ljung–Box tests | `q1b_acf.png` and `q1b_ljungbox.csv` |
| Figure 3 and Table 2 | Q1(c), normal QQ-plots and Jarque–Bera tests | `q1c_qq.png` and `q1c_jarquebera.csv` |
| Figure 4 | Q2(d), fitted densities | `q2d_densities.png` |
| Table 3 | Q2, cell starting with `q2_rows = []` | First-window VaR and ES in `q2_rows`, with degrees of freedom in `q2_nu`. Multiply VaR and ES by 100 for the report. |
| Table 4 | Q4(a)(i) | `results_table` gives AIC and BIC for each AR order. |
| Table 5 | Q4(a)(ii), cell starting with the calculation of `p_bic` after the comment | The cell prints the mean-model estimates and standard errors, including the transformed mean and its standard error for JPM. |
| Table 6 | Q4(a)(iii) | `lb_ar` gives the residual and squared-residual tests. |
| Tables 7–9 | Q4(b) | Table 7 uses the printed parameter estimates and standard errors, Table 8 uses `ic_garch`, and Table 9 uses `lb_ar_garch`. |
| Table 10 | Q4(d) | The cell prints the mean Fissler–Ziegel score difference, DM statistic and p-value for GARCH-t versus historical simulation. |
| Table 11 | Q5(b) | `q5_dm.csv` gives the pinball-loss comparisons and DM tests. |
| Figure 5 and Table 12 | Q6(b)–(c) | `q6b_mean_excess.png` shows the mean excess curves. The cell prints the GPD estimates and standard errors from `gpd_rows`. |
| Figure 6 and Table 13 | Q6(c)–(e) | `q6c_gpd_fit.png` compares the empirical and fitted tails. The cell prints the 99.9% VaR and ES estimates from `q6_rows`. |
| Tables 14–15 | Q5(b), combined backtests from Q3–Q5 | `var_backtest_combined.csv`, filtered to `alpha = 0.975` for Table 14 and `alpha = 0.99` for Table 15. |
| Table 16 | Q5(b), combined ES backtests from Q3 and Q4 | `es_backtest_combined.csv` gives the Acerbi–Székely statistic, simulated p-value and average Fissler–Ziegel score at 97.5%. |
