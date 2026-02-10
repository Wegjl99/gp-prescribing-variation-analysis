# GP Prescribing Variation Analysis

## Background
As a UK General Practitioner, variation in prescribing behaviour between practices can indicate:
- clinical risk
- unmet patient need
- population differences
- or quality improvement opportunities

This project analyses prescribing differences using statistical standardisation rather than raw counts.

---

## Aim
Identify GP practices whose prescribing patterns significantly differ from peers.

We use z-scores to detect potential outliers in medication usage.

---

## Dataset
Synthetic GP prescribing dataset containing:
- practice code
- medication
- number of items prescribed

---

## Method

1. Calculate prescribing rate per practice
2. Standardise using z-scores
3. Detect outliers (|z| > 1)

---

## Example Findings

Practice A81003

- Higher prescribing of Omeprazole 20mg capsules (z=1.08)
- Lower prescribing of Ramipril 5mg capsules (z=-1.18)
- Higher prescribing of Salbutamol inhaler (z=1.29)

This may represent:
- population morbidity differences
- prescribing preference
- or potential optimisation opportunity

---

## Skills Demonstrated
- Python
- Pandas data analysis
- Statistical standardisation
- Clinical interpretation of healthcare data

---

## Next Steps
Planned extensions:
- visualisation dashboards
- real NHS prescribing data
- risk-adjusted modelling
