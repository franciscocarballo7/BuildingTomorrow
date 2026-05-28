Cleaning data
================

# Load Excel file

``` r
data <- read_excel("raw/ESS latest term 3 2025.xlsx")
```

``` r
data %>% 
  count(camp_sub_county)
```

    ## # A tibble: 30 × 2
    ##    camp_sub_county           n
    ##    <chr>                 <int>
    ##  1 Balawoli SC               4
    ##  2 Balawoli Town Council     3
    ##  3 Building Tomorrow         1
    ##  4 Bulopa S/C                7
    ##  5 Busedde S/C               7
    ##  6 Butagaya S/C             10
    ##  7 Butansi SC               13
    ##  8 Buwenge S/C              10
    ##  9 Buwenge T/C               3
    ## 10 Buyengo T/C              10
    ## # ℹ 20 more rows
