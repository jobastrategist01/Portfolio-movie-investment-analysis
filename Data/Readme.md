---

## 🧪 Cleaned & Enriched Dataset

In addition to the original Kaggle dataset, this repository includes a **cleaned and enhanced version** of the data, processed using Python during the exploratory analysis phase. This updated dataset adds several key columns to support better filtering, visualization, and business insights.

The file is available as:

data/movies_1980_2020_cleaned.xlsx


### 🔧 Enhancements Made

- Cleaned and standardized column formats (e.g., dates, text types).
- Filtered to include only movies released between **1980 and 2020**.
- Added derived fields like:
  - `region` → Groups countries into **North America** or **Foreign**.
  - `ROI (%)` → Calculates the return on investment.
  - `Investment Risk Level` → Labels each genre by its percentage of unprofitable movies (Low, Moderate, High Risk).
- Removed missing or incomplete records to improve data reliability.

> Both the **original Kaggle dataset** and the **cleaned version** are included in the `/data` folder for full transparency and reproducibility.
