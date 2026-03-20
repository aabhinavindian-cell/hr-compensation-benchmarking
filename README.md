# HR Compensation Benchmarking Tool

## Business Problem
Organisations that fail to benchmark compensation against market rates risk losing top talent to competitors while overpaying in roles where supply exceeds demand. This project builds a compensation benchmarking tool that analyses internal pay against market percentiles, identifies employees who are underpaid or overpaid relative to their grade, and flags flight risk and budget exposure — giving HR and Finance a data-driven foundation for salary review decisions.

## Key Insight
> Fixing all below-band employees costs **AED 490,800 annually** — a fraction of the cost of losing and replacing them. Yet 66 employees need immediate or priority pay action, including high performers sitting 30% below market midpoint.

## Project Summary
| Metric | Result |
|---|---|
| Employees analysed | 500 across 6 grades and 6 departments |
| Within band | 402 employees (80.4%) |
| Above band | 54 employees (10.8%) |
| Below band | 44 employees (8.8%) |
| Pay-related flight risks | 123 employees (24.6%) |
| Employees needing immediate action | 66 employees |
| Annual cost to fix below-band | AED 490,800 |
| Most underpaid department | Finance (avg compa-ratio 97.9) |

## Compensation Action Categories
| Action | Employees |
|---|---|
| No action required | 362 |
| Immediate review — below band, performing | 38 |
| Priority increase — low compa, high performer | 28 |
| Grade progression review | 25 |
| Salary freeze — above band | 29 |
| Salary freeze — high compa, low performer | 12 |
| Monitor — below band, low performance | 6 |

## Key Concepts
- **Compa-ratio** — actual salary divided by market midpoint × 100. A score of 100 = exactly at market. Below 90 = underpaid. Above 110 = overpaid.
- **Pay band** — defined as ±20% around the market midpoint for each grade
- **Market percentile** — where the employee sits within their grade's salary distribution
- **Flight risk flag** — employees with compa-ratio below 90 or salary below band minimum

## Tech Stack
- Python · pandas · numpy
- scipy · matplotlib · seaborn

## Files
| File | Description |
|---|---|
| `03_compensation_benchmarking.ipynb` | Full analysis notebook |
| `compensation_dashboard.png` | 6-chart compensation dashboard |
| `compensation_action_report.csv` | Employee-level actions and cost analysis |
