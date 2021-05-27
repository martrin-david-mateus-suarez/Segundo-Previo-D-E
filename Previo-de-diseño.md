SEGUNDO PREVIO
================

## Experimento de la Farmacocinetica

La base de datos Theoph, tiene 132 filas y 5 columnas de datos de un
experimento sobre la farmacocinética de la teofilina. Boeckmann, Sheiner
y Beal (1994) informan datos de un estudio del Dr. Robert Upton sobre la
cinética del fármaco antiasmático teofilina.

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

``` r
mean(subj1, na.rm = TRUE)
```

    ## [1] 0.08333333

## Including Code

You can include R code in the document as follows:

![](Previo-de-diseño_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
