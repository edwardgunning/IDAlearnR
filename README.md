
<!-- README.md is generated from README.Rmd. Please edit that file -->

# IDAlearnR

<!-- badges: start -->

<img src="inst/figures/hex-badge.png" width="200px" />
<!-- badges: end -->

The goal of IDAlearnR is to publish interactive tutorials for the module
**“Introduction to Data Analytics with R”**.

## Installation

You can install IDAlearnR from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("edwardgunning/IDAlearnR")
```

## Interactive tutorials

### Launching from the Tutorials pane

Once you have installed the package, you should be able to launch the
tutorials from the Tutorials pane on the right-hand side of the RStudio
IDE (provided that you have a recent version of RStudio installed).

![](inst/figures/tutorial-pane.png)

Otherwise, you can launch them using the `run_tutorial()` function from
the `learnr` package.

### Launching using `run_tutorial()`

#### Tutorial 1 - The basics of R

``` r
learnr::run_tutorial(name = "section_1_basics_of_R",
                     package = "IDAlearnR")
```