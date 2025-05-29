# Genotype-Analysis-Toolkit

## Project Overview

This project explores statistical analysis techniques applied to genotype-based biological data. It uses Python to perform tests such as t-tests, ANOVA, and likelihood-based modelling, aiming to investigate genotype effects on quantitative traits. The notebook serves as a toolkit for biologists conducting exploratory and inferential statistics in genetic studies.

## Data Source and Description

The dataset includes biological measurements grouped by genotype, suitable for evaluating mean differences, interaction effects, and model-based hypotheses. It provides a realistic use case for applying statistical tools in a biological context.

## Analysis Techniques

- **Descriptive Statistics**: Summary of means, standard deviations, and distributions
- **Normality Testing**: Shapiro-Wilk test to check distribution assumptions
- **Comparative Testing**:
  - Independent and paired t-tests
  - One-way and Two-way ANOVA
  - Linear models with interaction terms
- **Custom Likelihood-Based Models**: Fitting models using user-defined log-likelihood functions

## Areas for Development

While the notebook demonstrates useful techniques, there are several areas I intend to improve:

- Ensure assumptions like **equal variances** are formally tested and accounted for
- Refine **explanatory text** for clarity and precision
- Add **interaction testing** in multi-factor analyses and improve model visualisation
- Fix a **syntax issue** in the custom `likelihood_log` function, and ensure that **variance constraints** are implemented correctly
- Restructure parts of the code to make it **clearer and more modular**, with better documentation

Community contributions are welcome — whether it’s cleaning the code, improving explanations, or refining the statistical approach.

## Installation

Install the required Python libraries using:

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels
```

## Usage

1. Open the notebook `Stats for Biologists.ipynb`.
2. Follow the workflow from data loading to model fitting and result visualisation.
3. Apply improvements or build on the framework as needed.

## Contributing

Contributions to enhance statistical rigour, code clarity, or biological insight are encouraged. Please fork the repository and submit pull requests with your suggestions.

## License

This project is licensed under the MIT License.

## Contact

For queries, please contact **Shazaib Rehman**.  
Connect with me on [LinkedIn](https://www.linkedin.com).
