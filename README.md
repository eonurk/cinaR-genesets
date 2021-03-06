
<!-- README.md is generated from README.Rmd. Please edit that file -->

# cinaR-genesets <a href='https://eonurk.github.io/cinaR/'><img src='man/figures/cinaR.png' align="right" height="139" /></a>

<!-- badges: start -->

[![Build
Status](https://travis-ci.com/eonurk/cinaR.svg?branch=master)](https://travis-ci.com/eonurk/cinaR)
[![CRAN
version](https://www.r-pkg.org/badges/version/cinaRgenesets)](https://cran.r-project.org/package=cinaRgenesets)
[![CRAN
download](https://cranlogs.r-pkg.org/badges/cinaRgenesets?color=orange)](https://cran.r-project.org/package=cinaRgenesets?color=orange)
<!-- badges: end -->

## Installation

    # CRAN mirror
    install.packages("cinaRgenesets")

### Development Version

To get bug fix and use a feature from the development version:

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

This package contains 6 genesets curated from different sources.

#### Immune Modules

Immune system related modules from SLE patients published in [Nature
Communications (2020)](https://doi.org/10.1038/s41467-020-14396-9)

    data("VP2008")

#### PBMC scRNAseq Modules

Curated from PBMC scRNA-seq data published in
[here](https://www.nature.com/articles/s41590-020-0743-0):

    data("PBMC.scRNAseq")

#### Wikipathways

These genesets are curated from
[wikipathways](https://www.wikipathways.org/index.php/WikiPathways):

    data("wiki")

#### Wikipathways Immune

Hand-picked subset of immune related pathways from
[wikipathways](https://www.wikipathways.org/index.php/WikiPathways):

    data("wiki.immune")

#### Dice Major Cell Types

Major cell types curated from [DICE](https://www.dice-database.org/)
database:

    data("dice.major")

#### Activated Immune Cells

Activated immune cells curated by [Ucarlab](https://www.ucarlab.com/)
and published in
[here](https://www.biorxiv.org/content/10.1101/2020.12.23.424147v1.abstract):

    data("activated.immune")

## Contribution

You can send pull requests to make your contributions.

## Author

-   [E Onur Karakaslar](https://eonurk.github.io/)

## License

-   GNU General Public License v3.0
