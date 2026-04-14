# Global Influenza Data Analytics & Temporal-Spatial Visualization

## Overview
An end-to-end data pipeline analyzing 178,004 rows of WHO FluNet laboratory surveillance data (1995-2025). This project focuses on data integrity, logical cross-validation, and seasonal trend analysis across multiple WHO regions.

## Key Technical Highlights
* **Robust Data Cleaning:** Implemented conditional logical filling for hierarchical data (Type A/B sub-types) rather than simple imputation.
* **ISO-8601 Standardization:** Handled complex time-series alignment using ISO week-year standards.
* **Outlier Investigation:** Validated extreme data peaks against official CDC and Xinhua news reports.
* **WHO Regional Comparative Study:** Focused analysis on EUR, AMR, SEAR, and WPR regions, revealing the 2025 seasonal dominance of Influenza A (84%).