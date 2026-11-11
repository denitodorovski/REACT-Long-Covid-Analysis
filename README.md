# Long COVID in healthcare workers

Logistic regression analysis of whether healthcare workers reported long COVID more often than other workers, using a synthetic version of the REACT-1 study data (rounds 14–19).

## Files

- `react_lc_2026_analysis.Rmd`: data cleaning, logistic regression model, odds ratios with 95% confidence intervals, and interpretation.

## Running the analysis

The data file is not included in this repository. To run the analysis:

1. Place `react_lc_2026.rds` in this folder.
2. Open `react_lc_2026_analysis.Rmd` in RStudio and click **Knit**.

Required R packages: `tidyverse`, `broom`, `knitr`, `rmarkdown`.

## Main result

Among 931 working adults, healthcare workers had about twice the odds of reporting long COVID compared with other workers, after adjusting for age, sex and health conditions (OR 2.03, 95% CI 1.35–3.03, p < 0.001). See the notebook for full results and limitations.
