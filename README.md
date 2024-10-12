---
output: github_document
---

<!-- README.md is generated from README.Rmd. Please edit that file -->



# dividefair

<!-- badges: start -->
[![R-CMD-check](https://github.com/jakobschumacher/dividefairly/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/jakobschumacher/dividefairly/actions/workflows/R-CMD-check.yaml)
[![Codecov test coverage](https://codecov.io/gh/jakobschumacher/dividefairly/graph/badge.svg)](https://app.codecov.io/gh/jakobschumacher/dividefairly)
<!-- badges: end -->

The goal of dividefair is to ...

## Installation

You can install the development version of dividefair from [GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("jakobschumacher/dividefairly")
```

## Documentation

Full documentation website on: https://jakobschumacher.github.io/dividefairly

## Example

This is a basic example which shows you how to solve a common problem:


``` r
library(dividefair)
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`? You can include R chunks like so:


``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You'll still need to render `README.Rmd` regularly, to keep `README.md` up-to-date. `devtools::build_readme()` is handy for this.

You can also embed plots, for example:

<div class="figure">
<img src="man/figures/README-pressure-1.png" alt="plot of chunk pressure" width="100%" />
<p class="caption">plot of chunk pressure</p>
</div>

In that case, don't forget to commit and push the resulting figure files, so they display on GitHub and CRAN.
