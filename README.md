# Air Pollution at RDU Airport, 2018–2020

Author: Haochen Wang
Date: November 22, 2026

## Purpose

This project cleans daily air pollution measurements and explores
patterns in CO, PM2.5, and ozone concentrations using summary
tables and plots.

## Data Source

The data were provided for the course project and contain
measurements from the EPA air pollution monitor at RDU airport.
They cover 2018, 2019, and January–April 2020.

## Files

- AQ_2018.csv: Original air pollution data for 2018.
- AQ_2019.csv: Original air pollution data for 2019.
- AQ_2020.csv: Original air pollution data for January–April 2020.
- Haochen WANG_project2.Rmd: Data cleaning function, analysis,
  plots, and report text.
- Haochen-WANG_project2.docx: Generated Word report.
- project2.Rproj: RStudio project file.
- README.md: Project description and reproduction instructions.

## How to Reproduce

1. Download or clone this repository.
2. Open project2.Rproj in RStudio.
3. Install the required R packages if they are not already installed:

   install.packages(c("tidyverse", "lubridate", "knitr", "rmarkdown"))

4. Keep the three CSV files in the same folder as the RMarkdown file.
5. Open Haochen WANG_project2.Rmd and click Knit to Word.

The report uses ozone concentrations in ppm. The cleaning function
also supports conversion to ppb through its ozone_units argument.