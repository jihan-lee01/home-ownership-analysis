# What Factors Affect Home Ownership?

### Comparative Analysis of the Determinants of Home Ownership During the Great Recession

This repository contains the source code, data, and documentation for the project **Comparative Analysis of the Determinants of Home Ownership Between the Great Recession**, which examines the key factors influencing home ownership in the U.S. during 2007 and 2009 using IPUMS CPS data.

---

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data](#data)
- [Methods](#methods)
- [Results](#results)
- [References](#references)
- [Contact](#contact)

---

## Introduction

Home ownership is a significant indicator of economic stability and societal patterns in the U.S. This project investigates how factors such as race, sex, marital status, family size, education level, income, hours worked, and region influenced home ownership during the Great Recession. By comparing determinants in 2007 and 2009 using regression analysis, we aim to uncover changes driven by economic upheaval.

---

## Project Structure

The directory structure is organized as follows:

```bash
data/
|------ cps.csv
docs/
|------ project_final.html
|------ project_proposal.html
figures/
|------ fig1.png
|------ fig2.png
notebooks/
|------ project.ipynb
|------ project_final.ipynb
|------ project_proposal.ipynb
.gitignore
README.md
```

---

## Data

- **Source**: Current Population Survey (CPS) data from IPUMS.
- **Population**: Heads of households in the United States.
- **Key Variables**:
  - **Demographics**: Race, sex, marital status, family size, education level.
  - **Economic**: Income, hours worked per week.
  - **Regional**: U.S. regions (e.g., Midwest, South).
- **Years Analyzed**: 2007 and 2009. 
- **Preprocessing**: Includes cleaning, encoding categorical variables, and handling missing values.

---

## Methods

1. **Exploratory Data Analysis**:
   - Summary statistics of variables
   - Data visualization with histograms, pie charts, and correlation heatmaps
2. **Regression Analysis**:
   - Linear Probability Model (LPM) to estimate the likelihood of home ownership.
   - Multiple model specifications

---

## Results

- **Key Determinants**:
  - Age and education positively influenced home ownership, with minimal changes during the recession.
  - Racial disparities persisted, with non-white individuals less likely to own homes.
  - Marital status and income had significant effects on ownership rates.

- **Recession Impact**:
  - Minor shifts in determinant significance, with no major economic changes in effects.
  - Regional disparities in home ownership rates were observed.

---

## Conclusion

Our study highlights the consistent importance of age, education, and income on home ownership, alongside persistent racial disparities. While the recession altered some determinants slightly, these changes were not economically significant. Future work should incorporate additional variables like credit scores, interest rates, broader economic indicators and address potential endogeneity issues.

---

## References

- **Dataset**: [IPUMS CPS](https://cps.ipums.org/cps/)

___

## Contact
 
If you need any revisions or additional details, feel free to contact me [here](mailto:jihan.lee@alumni.emory.edu)
