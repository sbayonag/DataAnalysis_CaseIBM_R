# DataAnalysis_CaseIBM_R

HR Employee Attrition analysis in R with reproducible reports and visuals.

## Reports (GitHub Pages)
- Attrition analysis: `docs/Attrition_IBM_R.html` or https://sbayonag.github.io/DataAnalysis_CaseIBM_R/Attrition_IBM_R.html
- IBM analysis: `docs/IBM_R.html` or https://sbayonag.github.io/DataAnalysis_CaseIBM_R/IBM_R.html

## Highlights
- EDA with class balance checks and missing data review
- Correlation analysis with cleaned numeric features
- Reproducible workflow using ggplot2, ggcorrplot, dplyr, recipes

## How to render
Open the project and knit either Rmd. Outputs go to `docs/` for GitHub Pages.

## Publishing note
Rendered HTML in `docs/` is committed so GitHub Pages can serve the reports.

## PDF on demand
If you need a PDF, render explicitly:
```r
rmarkdown::render("Attrition_IBM_R.Rmd", output_format = "pdf_document")
rmarkdown::render("IBM_R.Rmd", output_format = "pdf_document")
```
