# Moduleflakescategories
This repository contain the code we applied to study the technological attributions between the module flakes categories.

This repository contains the data and code for our paper:

> David Nora, Ariel Malinsky Buller, Boris Gasparyan, Artur Petrosyan, Ellery Frahm, (2025). *Snakes and Ladders: A technological approach to tool maintenance by-products using module flake categories.*. Name of journal/book
> <https://doi.org/xxx/xxx>

Our pre-print is online here:

> David Nora, Ariel Malinsky Buller, Boris Gasparyan, Artur Petrosyan, Ellery Frahm, (2025). *Snakes and Ladders: A technological approach to tool maintenance by-products using module flake categories.* Name of
> journal/book, Accessed 18 Feb 2025. Online at
> <https://doi.org/xxx/xxx>

### How to cite

Please cite this compendium as:

> Authors, (2025). *Compendium of R code and data for Title of your
> paper goes here*. Accessed 18 Feb 2025. Online at
> <https://doi.org/xxx/xxx>

## Contents

The **analysis** directory contains:

- [:file_folder: data](/analysis/data): Data used in the analysis.
- [:file_folder: figures](/analysis/figures): Plots and other
  illustrations
- [:file_folder:
  supplementary-materials](/analysis/supplementary-materials):
  Supplementary materials including notes and other documents prepared
  and collected during the analysis.

## How to run in your browser or download and run locally

This research compendium has been developed using the statistical
programming language R. To work with the compendium, you will need
installed on your computer the [R
software](https://cloud.r-project.org/) itself and optionally [RStudio
Desktop](https://rstudio.com/products/rstudio/download/).

You can download the compendium as a zip from from this URL:
[master.zip](/archive/master.zip). After unzipping: - open the `.Rproj`
file in RStudio - run `devtools::install()` to ensure you have the
packages this analysis depends on (also listed in the
[DESCRIPTION](/DESCRIPTION) file). - finally, open
`analysis/paper/paper.Rmd` and knit to produce the `paper.docx`, or run
`rmarkdown::render("analysis/paper/paper.qmd")` in the R console

### Licenses

**Text and figures :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Code :** See the [DESCRIPTION](DESCRIPTION) file

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

### Contributions

We welcome contributions from everyone. Before you get started, please
see our [contributor guidelines](CONTRIBUTING.md). Please note that this
project is released with a [Contributor Code of Conduct](CONDUCT.md). By
participating in this project you agree to abide by its terms.
