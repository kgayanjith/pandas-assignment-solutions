# Salary Dataset Analysis (Pandas + Matplotlib)

This project demonstrates a reporting-style analysis on a salary dataset using **Python**, **Pandas**, and **Matplotlib**.

✅ Focus areas:
- Data loading and cleaning
- Filtering (staff vs external/outstaffed)
- GroupBy aggregations (wage fund, stake totals)
- Basic visualization (pie chart + cumulative curves)

> Note: This repository contains practice tasks and my solutions.

---

## Dataset

Place the CSV file (example: `salary_fix_en.csv`) in the same folder as the notebook (or update the path in the code).

Expected columns (example):
- `RegNumber` — unique employee ID
- `Position` — job title
- `Stake` — workload ratio
- `Staff Salary` — base salary for staff employees
- `Extra or Outstuff Salary` — extra pay / external pay
- `Hourly Payment` — hourly pay (if available)
- `Total` — total payout for the record

---

## Tasks Covered

- Wage fund totals (overall, by position, staff only, external only)
- Stakes distribution by position (pie chart)
- Assistant salary stats (min/mean/max)
- External associate professors grouped by `RegNumber` (`r4a`, `r4b`)
- Staff salary stats (min/mean/max)
- External stake stats (min/mean/max)
- Associate professors with exactly 1.0 total stake
- Most underloaded staff worker(s)
- Cumulative wage fund plots (overall vs staff vs external)

---

## Run on Google Colab

1. Open Google Colab: `colab.research.google.com`
2. Click **New Notebook** (or upload the `.ipynb` from this repo).
3. Upload your dataset:
   - Left sidebar → **Files** → **Upload**
   - Upload your `.csv` file (example: `salary_fix_en.csv`)
4. Run the notebook cells.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
