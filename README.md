# Python scripts archive

Public catalog of notebooks from a 2019–2021 Google Drive folder (`Python Scripts`).

- **Learning** — practice notebooks (NumPy, clustering, CatBoost, recommenders).
- **HRS-era** — hotel / GBTA / Exasol / DB2 / API sketches from that job. Connection strings and keys are redacted. Hotel extracts and SQL dumps are **not** here.
- **Utils** — small file and pandas helpers.

These are archival. Paths and library versions match that period, not a modern package.

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install jupyter pandas numpy scikit-learn
jupyter notebook notebooks/
```

Do not put credentials in notebooks. Use environment variables if you revive an HRS-era API script.

## Index

See [NOTEBOOKS.md](NOTEBOOKS.md) for a one-line description of each file.

## Not included

AWS PEM files, GeoSure client secrets, Nanonets API keys, Google Sheets configs, `Matching/` CSVs, bulk `SQL Scripts/`, Udemy course clones, and personal documents.
