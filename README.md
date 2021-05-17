---
output: github_document
---

<!-- README.md is generated from README.Rmd. Please edit that file -->

```{r, include = FALSE}
knitr::opts_chunk$set(
  collapse = TRUE,
  comment = "#>",
  fig.path = "man/figures/README-",
  out.width = "100%"
)
```

# foofactors

<!-- badges: start -->
<!-- badges: end -->

The goal of foofactors is to make factors less aggravating by creating functions that allow you to create a new factor from two existing factors, make a sorted frequency table for a factor, etc.

#' are the union of the levels of the input factors.

## Installation

You can install the released version of foofactors from [CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("foofactors")
```

## Example

This is a basic example which shows you how to solve a common problem:

```{r example}
library(foofactors)
fbind(a,b)
```


You'll still need to render `README.Rmd` regularly, to keep `README.md` up-to-date. `devtools::build_readme()` is handy for this. You could also use GitHub Actions to re-render `README.Rmd` every time you push. An example workflow can be found here: <https://github.com/r-lib/actions/tree/master/examples>.

You can also make a sorted frequency table for a factor:

```{r pressure, echo = FALSE}
fcount(x)
```

In that case, don't forget to commit and push the resulting figure files, so they display on GitHub and CRAN.
