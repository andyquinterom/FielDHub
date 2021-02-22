# FielDHub


[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)


FielDHub is a customer centric R Shiny design of experiment (DOE) app that aids in the 
creation of non-traditional and traditional DOE. Our app provides a graphical workflow to import 
treatment lists and export field books. For field experiments, it allows users to specify the 
dimensions of the field as row and columns, while controlling the percentage of check plots, and 
obtaining randomized field maps and field books that can be used directly as templates and input 
files for central databases.

## Installation

You can install the dev version of FielDHub from:

``` r
devtools::install_bitbucket("DidierMurillo/fieldhub-package", 
                            auth_user = "DidierMurillo", 
                            password = rstudioapi::askForPassword())
```

or 


``` r
remotes::install_bitbucket("DidierMurillo/fieldhub-package", 
                            auth_user = "DidierMurillo", 
                            password = rstudioapi::askForPassword())
```

## Example

This is a basic example which shows you how to launch the app:

``` r
library(FielDHub)
run_app()
```

