# Rebuild every chart from its source

Each notebook downloads the original document, prints the exact sentence each number comes from, checks it, and redraws the chart.

| Notebook | Chart |
|---|---|
| [01_ny_siting_clock.ipynb](01_ny_siting_clock.ipynb) | New York's 1-year deadline covers less than half the wait for a siting permit |
| [02_chicago_fema_vs_first_street.ipynb](02_chicago_fema_vs_first_street.ipynb) | A private flood model puts 40 times more of Chicago in the 100-year flood zone than FEMA |
| [03_slow_vs_fast_approvals.ipynb](03_slow_vs_fast_approvals.ipynb) | The same kind of approval can take months on one path and days on another |

Run: `pip install requests pypdf pandas matplotlib`, then open a notebook and run the cells top to bottom. One step in notebook 03 (a paywalled journal article) is a marked manual check.
