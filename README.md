
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->
<!-- badges: end -->

The goal of libminer is to help you understand your libraries better,
and learn how to write packages.

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("threePD/libminer")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(libminer)

lib_summary()
#>                                                                    Library
#> 1                                       C:/Program Files/R/R-4.3.1/library
#> 2                        C:/Users/pd375616/AppData/Local/R/win-library/4.3
#> 3 C:/Users/pd375616/AppData/Local/Temp/RtmpQf9I4D/temp_libpath40641ef84aa7
#>   n_packages
#> 1         30
#> 2        173
#> 3          1

# Also can calculate sizes
lib_summary(sizes = TRUE)
#>                                                                    Library
#> 1                                       C:/Program Files/R/R-4.3.1/library
#> 2                        C:/Users/pd375616/AppData/Local/R/win-library/4.3
#> 3 C:/Users/pd375616/AppData/Local/Temp/RtmpQf9I4D/temp_libpath40641ef84aa7
#>   n_packages  lib_size
#> 1         30  68858812
#> 2        173 303987541
#> 3          1     13227
```
