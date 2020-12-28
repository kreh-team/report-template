
# report-template <!-- <img src="figures/logo.png" align="right" width="120"/> -->

<!-- badges: start -->
<!-- badges: end -->

## Overview

[LaTeX](http://www.latex-project.org/) is a typesetting program for
producing high quality technical documents. Formatting LaTeX documents
is difficult and modifying pre-built templates often require extensive
knowledge of the template.

This template using Rmarkdown offers an easy to use solution to quickly
typeset an academic report, whilst using reasonable document options.

Under the hood, a LaTeX template is used to ensure that the document
follows the standards. At the same time, composition and formatting can
be done using lightweight markdown syntax, and R code and its output can
be seamlessly included using {knitr}.

## Usage

To use this template modify the `report.Rmd` and Knit the document using
the RStudio UI or render using the {rmarkdown} package:

``` r
rmarkdown::render("template/report.Rmd")
```
