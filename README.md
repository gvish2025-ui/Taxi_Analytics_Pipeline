# NYC Taxi Analytics

A Streamlit dashboard for NYC taxi trip analytics using DuckDB.

## Repo structure

- `scripts/` — ingestion, transformation, visualization scripts
- `sql/` — example analytical queries
- `requirements.txt` — Python dependencies

## Requirements

- Python 3.14
- `streamlit`
- `duckdb`
- `pandas`

## Run locally

1. Install dependencies:
   ```bash
   pip install -r requirements.txt

   python -m streamlit run scripts/visualize.py
