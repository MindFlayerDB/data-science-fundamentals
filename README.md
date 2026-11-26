# Data Science Fundamentals & Statistical Preprocessing Pipeline

**Author:** Tejbir Singh  
**Program:** Data Analyst Internship (Hyderabad) — Task 1  

## Overview
This repository provides a practical, end-to-end implementation of foundational Data Science and Data Analytics principles in Python. It bridges theoretical statistical concepts with real-world data engineering workflows through both a modular Python script (`data_science_fundamentals.py`) and an interactive Jupyter Notebook (`data_science_fundamentals.ipynb`) that simulate and resolve common data quality challenges encountered in enterprise analytics.

The workflow is structured into three core analytical modules:
1. **Python Basics & Data Structures:** Demonstrates lists, immutable tuples, sets, and dictionary comprehensions, highlighting memory efficiency and algorithmic trade-offs when handling analytical metadata.
2. **Data Types & Measurement Scales:** Generates a synthetic multi-variable employee dataset spanning qualitative scales (nominal identifiers, ordinal experience tiers) and quantitative scales (discrete counts, interval performance scores, continuous ratio compensation figures), intentionally injecting missing values and extreme anomalies.
3. **Statistical Foundations & Cleaning Best Practices:** Uses NumPy, Pandas, and SciPy to compute central tendency (mean, median, mode), dispersion (sample standard deviation, variance, IQR), and skewness, followed by distribution-aware median imputation, Tukey's IQR outlier Winsorization, ordinal encoding, and Z-score standardization.

---

## Repository Structure

```text
├── data_science_fundamentals.py     # Modular Python script executing the full pipeline
├── data_science_fundamentals.ipynb  # Interactive Jupyter Notebook version
└── README.md                        # Project documentation
