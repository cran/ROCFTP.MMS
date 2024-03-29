
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ROCFTP.MMS

<!-- badges: start -->

<!-- badges: end -->

The goal of ROCFTP.MMS is to generate perfect sample from a given
posterior. It takes a posterior, and generates two Markov chains by
Metropolis with a multishift proposal. This proposal is monotone and
forces these two Markov chains started from the two extreme points of
the most interest range to be coalesced. This mechanism is used in
ROCFTP to generate a perfect sample.

## Installation

You can install the released version of ROCFTP.MMS from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("ROCFTP.MMS")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("nabipoor/ROCFTP.MMS")
```

## Example

Basic examples provided in the Help document.
