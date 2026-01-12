# COIL PHP – Published Results Table (IRB-safe Recreation)

This package **recreates the final manuscript results table** for the COIL PHP manuscript using **published summary statistics only**.

## What this is
- A frozen, publication-aligned table recreation.
- Intended for transparency, teaching, and reproducibility documentation when **participant-level data are IRB-protected**.

## What this is NOT
- This is **not** a re-analysis of participant-level data.
- This does **not** recompute t-tests or p-values from raw observations.

## Files
- `coil_php_published_recreation.py` — script that prints the table and optionally exports CSV/XLSX
- `COIL_PHP_published_recreation.ipynb` — notebook version of the same table
- `METHODS_language.md` — methods/notes file (see below)

## How to run
```bash
pip install pandas openpyxl
python coil_php_published_recreation.py
```

## Outputs (optional)
If left enabled in the script, it will write:
- `results_table_published.csv`
- `results_table_published.xlsx`

## Notes on p-values
The manuscript p-values are presented **as published**. They are not recomputed from rounded t-statistics because rounding can change computed p-values at the reported precision.
