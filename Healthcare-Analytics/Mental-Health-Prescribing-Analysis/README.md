# Mental Health Prescribing Analysis

## Project Overview

This project analyses NHS mental health prescribing data to explore prescribing trends, antidepressant medication usage patterns, prescribing costs, and regional variations across England.

The analysis is based on NHSBSA Prescription Cost Analysis (PCA) data and was inspired by the NHS Step Up virtual career challenge:

> Turning Data into Insight – Building Awareness of Mental Health Prescribing

This project demonstrates healthcare analytics, exploratory data analysis, statistical thinking, and data storytelling using Python.

---

## Objectives

- Analyse prescribing trends for antidepressant medications
- Explore regional variations in prescribing behaviour
- Understand prescribing cost patterns across England
- Identify high-volume and high-cost medications
- Generate insights relevant to healthcare planning and operational reporting
- Explore future forecasting opportunities for prescribing demand

---

## Dataset Information

Source:

NHSBSA Open Data Portal – Prescription Cost Analysis Dataset

The project uses two NHS prescribing datasets.

---

## Dataset 1 – Drug-Level Prescribing Data

### File

```text
BSA_ODP_PCA_REGIONAL_DRUG_SUMMARY.csv
```

### Description

This dataset contains detailed antidepressant prescribing information across NHS regions in England.

The dataset describes:

> Per English NHS Region and per year-month, the volume and cost of each antidepressant drug prescribed.

### Columns

| Column | Description |
|---|---|
| YEAR | Prescribing year |
| YEAR_MONTH | Year and month in YYYYMM format |
| REGION | NHS region |
| DRUG | Antidepressant medication name |
| ITEMS | Number of prescription items |
| COST | Combined prescribing cost |

### Planned Analysis

- Drug prescribing trends
- Cost analysis
- Regional comparisons
- High-volume medications
- Time-series analysis
- Forecasting opportunities

---

## Dataset 2 – Regional Summary Data

### File

```text
BSA_ODP_PCA_REGIONAL_SUMMARY.csv
```

### Description

This dataset contains higher-level prescribing summaries organised using the British National Formulary (BNF) hierarchy.

The BNF structure is organised as:

```text
BNF Chapter
   ↓
BNF Section
   ↓
Drug
```

Example:

```text
04: Central Nervous System
    ↓
Antidepressant drugs
    ↓
Amitriptyline hydrochloride
```

### Planned Analysis

- BNF chapter analysis
- BNF section analysis
- Healthcare hierarchy analysis
- Broader prescribing trends
- Category-level reporting

---

## Key Analysis Questions

1. Which antidepressant medications are prescribed most frequently?
2. Which medications generate the highest prescribing costs?
3. How do prescribing trends change over time?
4. Which NHS regions show the highest prescribing activity?
5. Are there seasonal or long-term prescribing patterns?
6. What insights could support mental health awareness and healthcare planning?

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Healthcare Analytics
- Public Health Analysis
- Statistical Analysis
- Trend Analysis
- Data Visualisation
- Insight Generation
- Python Programming

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git & GitHub

---

## Project Structure

```text
Mental-Health-Prescribing-Analysis/
│
├── data/
├── notebooks/
├── visuals/
├── reports/
└── README.md
```

---

## Project Status

Project setup and exploratory analysis in progress.