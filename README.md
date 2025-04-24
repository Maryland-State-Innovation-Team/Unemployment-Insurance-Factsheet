# Unemployment-Insurance-Factsheet

Automate the creation of the UI factsheet with R markdown.

## Prerequisites

To use this project, you need to install the following:

1. **R**: Download and install R from [CRAN](https://cran.r-project.org/).
2. **RTools**: If you are on Windows, download and install RTools from [RTools](https://cran.r-project.org/bin/windows/Rtools/).
3. **RStudio**: Download and install RStudio from [RStudio](https://posit.co/download/rstudio/).

## Instructions

1. Clone this repository to your local machine.
2. Open the `ui-federalactionsimpactmdemployment-hifreqindicators.Rmd` file in RStudio.
3. Before knitting the file, ensure the `MD_DOL_INTERNAL_UCFE` variable is set correctly at the top of the file. This variable is not automatically collected and must be manually updated.
   ```r
   MD_DOL_INTERNAL_UCFE = 1200  # Replace with the updated value
   ```
4. Install any missing R packages. The script will automatically attempt to install required packages if they are not already installed.
5. Knit the R Markdown file to HTML by clicking the "Knit" button in RStudio.
6. If desired, print the resulting HTML file to a PDF using your browser's print functionality.

## Notes

- The factsheet is updated with the latest data from external sources. Ensure you have an active internet connection when running the script.
- For any issues with package installation, ensure your R and RTools installations are correctly configured.
