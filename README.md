# Stats-506-Final-project-analysis-code-repository
# Government Funding and Nonprofit Advocacy  
*STATS 506 Final Project*

## Overview
This repository contains the analysis code and data for the STATS 506 final project, which examines the relationship between **government funding and nonprofit advocacy participation**.

Using the **2021 National Survey of Nonprofit Trends and Impacts (NSNTI)** public-use dataset, the project evaluates whether a higher share of government revenue is associated with a greater likelihood of nonprofit advocacy activity.

---

## Data
- **File**: `YEAR-02-DATA-PUF.csv`
- **Source**: 2021 National Survey of Nonprofit Trends and Impacts (NSNTI), public-use file
- **Unit of analysis**: Nonprofit organizations
- **Outcome variable**: Advocacy participation (binary)
- **Key predictors**:
  - Share of government funding
  - Organizational size
  - Volunteer capacity

Due to confidentiality restrictions, mission type and geographic identifiers are not available in the public-use data.

---

## Analysis
- **Main analysis file**: `Stats506finalproject.qmd`
- **Methods**:
  - Data cleaning and variable construction
  - Exploratory data analysis
  - Logistic regression modeling
  - Robustness checks controlling for organizational capacity

All analyses are conducted in **R**.

---

## Figures
- `figure1.png`: Predicted probability of advocacy by government funding share  
- `figure2.png`: Advocacy patterns across organizational size categories  

These figures are generated from the analysis and used in the final report.

---

## How to Run
Open `Stats506finalproject.qmd` in RStudio and render the document to reproduce the analysis and figures.

---

## Author
**Linxuan Ma**  
M.S. student in Applied Statistics  
University of Michigan

---

## Notes
This repository is intended for academic coursework only.
