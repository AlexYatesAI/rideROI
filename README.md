# Transportation & Viral Suppression ROI Pilot — `rideROI`

**Purpose.** HRSA Ryan White–style program evaluation (with synthetic data) estimating how ride vouchers impact appointment adherence and Viral Load Suppression (VLS), plus cost–benefit (ROI).

**Deliverables**
- `/data/` synthetic CSVs for analysis and dashboards
- `/notebooks/` analysis + charts (Python)
- `/dashboard/` Power BI file (`rideROI.pbix`)
- `/reports/` brief + slides suitable for leadership/funders

**Quickstart**
1) `python -m venv .venv && source .venv/bin/activate` (Windows: `.venv\Scripts\activate`)
2) `pip install -r requirements.txt`
3) Open `/notebooks/01_generate_synthetic_data.ipynb`
4) Open `/dashboard/rideROI.pbix` (Power BI) and point to `/data`

**Repo Structure**
data/ # synthetic raw/processed CSVs
notebooks/ # analysis & visualizations
dashboard/ # rideROI.pbix (Power BI)
reports/ # evaluation brief & slides
docs/ # references (HRSA measures, notes)


**Disclaimer**
This is a portfolio project using **synthetic data** only. No real patient data is used.
