
<!-- README.md is generated from README.Rmd. Please edit that file -->

# takehomecarpentries

<!-- badges: start -->

<!-- badges: end -->

The goal of takehomecarpentries is to practice what you learned at your
[*Carpentries
workshop*](http://swcarpentry.github.io/r-novice-inflammation/).

## Installation

If do not have the package, devtools installed, please uncomment the
install.packages() line item before running the next line. If you do
have devtools installed, proceed with running the following code block:

``` r
# install.packages("devtools")
devtools::install_github("gcipriano/takehomecarpentries")
```

Next, use the below functions to start your tutorial.

``` r
library(takehomecarpentries)

run_tutorial("takehome_tutorial", package = "takehomecarpentries")
```
