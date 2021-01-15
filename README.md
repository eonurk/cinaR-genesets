
<!-- README.md is generated from README.Rmd. Please edit that file -->

# cinaR-genesets <a href='https://eonurk.github.io/cinaR/'><img src='man/figures/cinaR.png' align="right" height="139" /></a>

<!-- badges: start -->

[![Build
Status](https://travis-ci.com/eonurk/cinaR.svg?branch=master)](https://travis-ci.com/eonurk/cinaR)
<!-- badges: end -->

## Overview

## Installation

    # install.packages("devtools")
    devtools::install_github("eonurk/cinaR-genesets")

## Usage

You can use these modules via setting `geneset` argument in
[cinaR](https://eonurk.github.io/cinaR/):

    library(cinaR)
    library(cinaRgenesets)

    data("VP2008")
    cinaR(..., geneset = vp2008)

## Available Genesets

This package contains 5 genesets curated from different sources

#### Immune Modules

    data("VP2008")

#### PBMC scRNAseq Modules

#### Wikipathways

#### Wikipathways Inflammation

#### Dice Major Cell Types

## Contribution

You can send pull requests to make your contributions.

## Author

-   [E Onur Karakaslar](https://eonurk.github.io/)

## License

-   GNU General Public License v3.0
