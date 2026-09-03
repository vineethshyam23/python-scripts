# Python scripts archive (2019–2021)

Notebooks copied from Google Drive `Python Scripts`, catalogued, and **redacted** for a public repo.

| Folder | What |
| --- | --- |
| `notebooks/learning/` | Practice (NumPy, clustering, CatBoost, recommenders) |
| `notebooks/utils/` | File conversion, pandas, threading |
| `notebooks/hrs-era/` | Hotel-platform era experiments. Credentials, DSNs, and API keys removed |
| `scripts/multiscorer.py` | Small CV helper |
| `data/diabetes.csv` | Public sample used by `cancer.ipynb` |

Full list: [NOTEBOOKS.md](NOTEBOOKS.md).

## Not in this repo

- Hotel extracts (`Matching/` CSVs)
- Bulk `SQL Scripts/`
- AWS PEM / GeoSure client files
- Udemy course clones and certificates

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install jupyter pandas numpy scikit-learn
jupyter notebook notebooks/learning
```

HRS-era notebooks expect databases and APIs that you will not have. They are archival. Set any remaining connection settings via environment variables; do not paste secrets back into git.

Related: private [python-learning-notebooks](https://github.com/vineethshyam23/python-learning-notebooks) holds an earlier learning-only subset.
