Homework1
================
2022-09-22

# P8105

## Homework 1 **UNI**: *rp3022*

``` r
library(tidyverse)
```

    ## ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.2 ──
    ## ✔ ggplot2 3.3.6      ✔ purrr   0.3.4 
    ## ✔ tibble  3.1.8      ✔ dplyr   1.0.10
    ## ✔ tidyr   1.2.0      ✔ stringr 1.4.1 
    ## ✔ readr   2.1.2      ✔ forcats 0.5.2 
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()

``` r
data("penguins", package = "palmerpenguins")
```

## Problem 1

``` r
a=data.frame(penguins)
nrow(a)
```

    ## [1] 344

``` r
ncol(a)
```

    ## [1] 8

``` r
mean(a$flipper_length_mm, na.rm=TRUE)
```

    ## [1] 200.9152

### Description of the ‘dataset penguins’

### The dataset penguins has 344 observations i.e *344 rows* and 8 variables i.e *8 columns*.The data provides information regarding 344 penguins, and has variables :

-   “*species*” which has 3 categories: Adelie, Chinstrap and Gentoo  
-   “*island*” which has 3 categories Togerson, Biscoe and Dream.
-   “*bill length*”, “*bill_depth_mm*”, “*flipper_length_mm*” and
    “*body_mass_g*”: They are continuous numerical variables providing
    information about the length and depth of their bills and the length
    of their flippers in mm and their body mass in grams
-   “*sex*” dichotomous variable : Male, Female
-   “*year*”

### The mean of flipper length is *200.9152* mm
