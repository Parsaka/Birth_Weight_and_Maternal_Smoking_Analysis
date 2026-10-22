# Birth Weight and Maternal Smoking

Statistical comparison of newborn birth weight across maternal smoking-status groups.
Project II of the *Introductory Case Studies* course, TU Dortmund.

**Project page:** https://parsa-kamali.de/projects/birth-weight-smoking-analysis.php

## What the analysis does
- Describes birth weight per maternal smoking group (for example no, light and heavy smoking).
- Runs a global test (one-way ANOVA) for any difference between groups.
- Runs pairwise two-sample tests with Bonferroni correction and Tukey HSD post-hoc comparisons.
- Reports confidence intervals and checks the test assumptions.

## Repository contents
| File | Description |
|---|---|
| `CaseStudy2.ipynb` | Complete analysis notebook |

## Tech stack
Python, Jupyter, pandas, SciPy, statsmodels, pingouin, matplotlib/seaborn

## How to run
```bash
pip install pandas scipy statsmodels pingouin matplotlib seaborn jupyter
jupyter notebook CaseStudy2.ipynb
```
The babies/mothers dataset is not included in this repository.
