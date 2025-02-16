# Statistical Analysis of Consumer Behavior in Bajtocja

This project involves a comprehensive statistical analysis of consumer behavior survey data from the fictional country of Bajtocja. The analysis is implemented in Jupyter Notebook and includes exploratory data analysis, statistical testing, and regression modeling.

## Dataset Description

The dataset (`dane_projekt1.csv`) contains survey results from a representative sample of Bajtocja residents, including the following variables:

- `id` - Observation identifier
- `waga` - Weight (kg)
- `wzrost` - Height (cm)
- `plec` - Gender (1 - "female", 2 - "male")
- `dzieci` - Number of dependent children
- `wiek` - Age (years)
- `dochod` - Declared monthly income (in bajtalars)
- `oszczednosci` - Declared monthly savings (in bajtalars)
- `jednoos` - Household status (1 - "single-person household", 0 - "multi-person household")
- `miejsce` - Size of residence location (1 - "up to 10,000 residents", 2 - "10,000 to 100,000 residents", 3 - "over 100,000 residents")
- `wydatki_zyw` - Declared food expenses in the surveyed month (in bajtalars)

## Analysis Components

1. **Data Exploration (Tasks 1-3)**
   - Dataset structure analysis
   - Descriptive statistics
   - Distribution analysis
   - Correlation analysis
   - Visual exploration (heatmaps, scatterplots, boxplots, stacked bar charts)

2. **Statistical Analysis (Tasks 4-6)**
   - Confidence intervals calculation (99% level)
   - Wealth class analysis
   - Statistical hypothesis testing
   - Distribution fitting

3. **Regression Analysis (Task 7)**
   - Linear regression modeling
   - Model diagnostics
   - Assumptions verification
   - Model improvement
   - Results interpretation

## Requirements

- Python 3.x
- Jupyter Notebook
- Required packages:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy
  - statsmodels

