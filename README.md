# Statistical Drivers of Loan Default Risk

## Project Overview

This project analyzes loan-level data to identify statistical drivers of default risk and develop a structured Early Warning Indicator (EWI) framework.

The analysis transforms descriptive metrics into operational watchlist and escalation logic.

---

## Dataset

1,000 loans across:
- Auto
- Mortgage
- Personal
- Business
- Home Equity

Key variables include:
- Loan amount
- Outstanding balance
- Interest rate
- Payment behavior
- Default flags

---

## Analytical Framework

### Data Standardization
- Normalized column names
- Converted monetary strings to numeric
- Harmonized product categories

### Product-Level Default Analysis
- Default rates by loan type
- 95% confidence intervals
- Risk band classification

### Tail Risk Modeling
- 90th / 95th / 99th percentile exposure
- Concentration detection

### Early Warning Indicator (EWI)
Composite score based on:
- Missed payments
- Tail exposure
- Product uncertainty risk

### Watchlist Escalation Framework
| Tier | Action |
|------|--------|
| LOW | Normal monitoring |
| MEDIUM | Portfolio review |
| HIGH | Watchlist |
| CRITICAL | Immediate escalation |

---

## Key Findings

- 26% of loans require escalation
- Tail exposure concentrated in higher-risk products
- Behavioral risk (missed payments) is strongest default predictor

---

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## View Full Interactive Analysis

Download HTML version in `/outputs` folder or open locally.

---

## Strategic Impact

This project demonstrates how statistical analysis can be translated into operational risk monitoring and portfolio governance frameworks.

