# Market Data Cleaning

<!-- One sentence: what this does and why anyone should care. -->
TODO: Cleans [dataset] so it can be trusted for [forecasting / pricing analysis / ...].

## The problem
<!-- What was wrong with the raw data? Be specific: nulls, duplicate rows, mixed date formats, outliers. -->
- TODO

## Data
- Source: TODO (Kaggle link)
- Rows / columns (raw): TODO
- Raw data is not committed. Download it into `data/raw/`.

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
