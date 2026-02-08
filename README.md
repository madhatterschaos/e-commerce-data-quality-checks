# E-Commerce Data Quality Check

## Overview
Preformed five data quality checks on E-commerce dataset, inspecting completeness, validity, uniqueness, accuracy and consistency in order to ensure that it can be used for analytical and reporting purposes.

---

## Project Structure

```
e-commerce-data-quality-checks/
│
├── qualtity_checks.ipynb  # Contains quality checks and their descriptions
├── temp.db                # Temporary copy of the initial dataset to work with SQLite
├── data.csv               # Initial e-commerce dataset
└── README.md              # File with project description
```
---

##  Implemented Data Quality Checks

The following categories of checks are implemented:

1. **Vital Keys Integrity**
   - Invoice number and customer id completeness

2. **Transactional Validity**
   - Positive quantity and unit price

3. **Product Duplicates**
   - Each product appears once in one invoice

4. **Country Accuracy**
   - Country existence

5. **Product Data Quality**
   - Product's description consistency
