# UMMS 2026–2027 Medical Plan Comparison

A static, browser-only tool that helps UMMS team members compare their current medical plan with the 2026–2027 plan year options.

**Live site:** _populated after first deploy_

## What it does
- Pick coverage tier, salary band ($25K–$250K in $5K increments), and current 2025 plan.
- Compare against up to 2 of the 2026 medical plans side-by-side (or up to 3 plans if new to UMMS).
- Shows per-paycheck (bi-weekly) and annual premium impact, along with side-by-side plan design (deductible, OOP max, copays, etc.) and prescription drug tiers.

## Data sources
All values come directly from:
- *Kelly Benefits — UMMS 2025 Team Member Guide* (pp. 8, 9, 11)
- *UMMS 2026–2027 Benefits Guide* (pp. 7, 8, 9, 12)

No backend, no analytics, no data storage. Selections live only in the browser session.

## Local preview
```
cd site
python3 -m http.server 8000
# → http://localhost:8000
```

## Disclaimer
Estimates only. Official plan documents and Summary Plan Descriptions govern in case of any discrepancy. Premiums shown are full-time (FTE 0.90–1.00) bi-weekly deductions; part-time, supplemental/PRN, and tobacco-surcharge rates are not modeled. Dental, vision, and other ancillary benefits are out of scope.
