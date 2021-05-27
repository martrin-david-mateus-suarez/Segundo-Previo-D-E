SEGUNDO PREVIO
================

## Experimento de la Farmacocinetica

This is an R Markdown format used for publishing markdown documents to
GitHub. When you click the **Knit** button all R code chunks are run and
a markdown file (.md) suitable for publishing to GitHub is generated.

``` r
subj1 <- ifelse(Theoph$Subject == 1, TRUE, FALSE)
View(subj1)
Theoph[subj1,]
```

    ##    Subject   Wt Dose  Time  conc
    ## 1        1 79.6 4.02  0.00  0.74
    ## 2        1 79.6 4.02  0.25  2.84
    ## 3        1 79.6 4.02  0.57  6.57
    ## 4        1 79.6 4.02  1.12 10.50
    ## 5        1 79.6 4.02  2.02  9.66
    ## 6        1 79.6 4.02  3.82  8.58
    ## 7        1 79.6 4.02  5.10  8.36
    ## 8        1 79.6 4.02  7.03  7.47
    ## 9        1 79.6 4.02  9.05  6.89
    ## 10       1 79.6 4.02 12.12  5.94
    ## 11       1 79.6 4.02 24.37  3.28

## Including Code

You can include R code in the document as follows:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](Previo-de-diseño_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
