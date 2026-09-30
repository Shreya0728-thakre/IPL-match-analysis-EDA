# IPL Match Analysis — EDA

Exploratory data analysis of IPL matches (2008–2024) to find what actually predicts a win — toss decisions, venue effects, and early-innings performance — using 1,095 matches and 260,920 ball-by-ball deliveries.

## Key Findings
- **Toss matters:** Teams that win the toss and choose to field first win significantly more often than teams that bat first (chi-square test, p = 0.0104).
- **But it depends on the venue:** The toss advantage isn't uniform — some grounds strongly favor fielding first, others show no advantage at all.
- **Powerplay performance predicts wins:** Teams scoring more runs in the first 6 overs are significantly more likely to win the match (t-test, p < 0.000001).

## Tools
Python, pandas, matplotlib, seaborn, scipy

## Data Source
[Cricsheet](https://cricsheet.org), via Kaggle's [IPL Complete Dataset (2008-2024)](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)

## Notebook
See [`01_load_and_inspect.ipynb`](01_load_and_inspect.ipynb) for the full analysis, including data cleaning, statistical tests, and visualizations.
