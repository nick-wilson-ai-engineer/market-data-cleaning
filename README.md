# Market Data Cleaning

<!-- One sentence: what this does and why anyone should care. -->
TODO: Cleans [dataset] so it can be trusted for [forecasting / pricing analysis / ...].

## The problem
<!-- What was wrong with the raw data? Be specific: nulls, duplicate rows, mixed date formats, outliers. -->
- TODO

## Data
- Source: [Online Retail II, UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
- UK-based online gift retailer, transactions Dec 2009 – Dec 2011
- Rows / columns (raw): 1,067,371 / 8
- Raw data is not committed. Download `online_retail_II.xlsx` into `data/raw/`.

## What I did
| Issue | Fix | Rows affected |
|---|---|---|
| TODO | TODO | TODO |

## Results
<!-- Before vs. after numbers. These are what a reviewer reads. -->
- TODO

## How to run
```bash
python -m venv .venv
.venv\Scripts\activate        # Windows
pip install -r requirements.txt
pytest
```

## Project layout
```
data/raw/         original download (gitignored)
data/processed/   cleaned output (gitignored)
notebooks/        exploration
src/              cleaning functions
tests/            pytest checks on the cleaned data
```

## What I'd do next
- TODO
