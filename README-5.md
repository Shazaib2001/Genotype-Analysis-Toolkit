# Genotype-Analysis-Toolkit

## Project Overview

This project is a statistical analysis notebook developed for genotype-based biological data. It applies fundamental statistical techniques including t-tests, ANOVA, and linear modelling to explore the influence of genotypes on biological measurements. The aim is to build a foundational toolkit for biologists conducting statistical analysis on genotype datasets using Python.

## Data Source and Description

The dataset involves simulated or experimental genotype data. It includes multiple groups or treatment conditions with corresponding biological measurements, enabling the application of comparative statistical methods.

## Analysis Techniques

- **Descriptive Statistics**: Mean, variance, and standard deviation summarisation
- **Normality Testing**: Shapiro-Wilk test for assessing Gaussian distribution assumptions
- **Comparative Testing**:
  - Independent and paired **t-tests**
  - **One-way and Two-way ANOVA**
  - **Linear Models and Interaction Terms**
- **Custom Likelihood Models**: Attempt to apply model-based inference using log-likelihood functions

## Known Issues and Areas for Improvement

This notebook received critical feedback identifying several issues:

### Section 2.2 (5/10):
- Variances are **not equal**, yet this assumption is not tested or corrected for.
- Wording and explanations are **imprecise** and should be revised for clarity.

### Section 3 (5/20):
- **Interaction effects** are not tested despite being relevant.
- The **final plot/model** does not accurately reflect the statistical analysis, possibly misleading.

### Section 4 (10/20):
- A critical cell **fails to run** due to a syntax error in the `likelihood_log` function.
- After manual fix, the model runs, but **variances are not constrained to their means**, as was explicitly requested.
- Code structure and logic are **confusing** and would benefit from modularisation and clearer comments.

These issues should be addressed to improve statistical validity and code usability.

## Installation

Install the required Python libraries using:

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels
```

## Usage

1. Open the notebook `Stats for Biologists.ipynb`.
2. Follow each section sequentially to reproduce statistical analysis on genotype data.
3. Address noted code issues where necessary for full functionality.

## Contributing

Improvements are welcome. Suggestions to clarify model code, fix the likelihood function, and improve statistical robustness are encouraged.

## License

This project is licensed under the MIT License.

## Contact

For queries, please contact **Shazaib Rehman**.  
Connect with me on [LinkedIn](https://www.linkedin.com).
