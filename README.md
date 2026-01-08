# A/B Testing Analysis Tool (Python + Tableau)

## Overview
End-to-end A/B testing project that analyzes conversion metrics using **Python statistical testing** and presents results in an **interactive Tableau dashboard**.  
The project follows a real-world analytics workflow: raw events → statistical validation → business-ready visualization.

---

## What This Project Does
- Performs **two-sided proportion z-tests** for A/B experiments
- Calculates conversion rates and relative metric change (%)
- Identifies **statistically significant results (α = 0.05)**
- Supports **segmented analysis** by:
  - Country
  - Device
  - Continent
  - Channel
- Exports clean results for BI tools

---

## Metrics Analyzed (per session)
- Add payment info
- Add shipping info
- Begin checkout
- New accounts

---

## Tech Stack
- **Python**: pandas, numpy, statsmodels  
- **Visualization**: Tableau Public  
- **Environment**: Google Colab

---

## Output
- `.tsv` file with test results:
  - Conversion rates
  - Metric change (%)
  - Z-statistic & p-value
  - Significance flag
- [Interactive Tableau dashboard] (https://public.tableau.com/app/profile/olena.dziuba/viz/ABtest_17617430569810/ABtest) with:
  - Test selection
  - Segment filters
  - Conversion comparison


