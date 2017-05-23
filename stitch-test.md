# A test script for the function stitch()

 Yihui Xie

This report was automatically generated with the R package **knitr**
(version 1.13).


```r
set.seed(1121)
(x = rnorm(20))
```

```
##  [1]  0.1449583  0.4383221  0.1531912  1.0849426  1.9995449 -0.8118832
##  [7]  0.1602680  0.5858923  0.3600880 -0.0253084  0.1508809  0.1100824
## [13]  1.3596812 -0.3269946 -0.7163819  1.8097690  0.5084011 -0.5274603
## [19]  0.1327188 -0.1559430
```

```r
mean(x);var(x)
```

```
## [1] 0.3217385
```

```
## [1] 0.5714534
```

```r
boxplot(x)
```

<img src="figure/stitch-test-Rmdauto-report-1.png" title="plot of chunk auto-report" alt="plot of chunk auto-report" style="display: block; margin: auto;" />

```r
hist(x, main = '')
```

<img src="figure/stitch-test-Rmdauto-report-2.png" title="plot of chunk auto-report" alt="plot of chunk auto-report" style="display: block; margin: auto;" />

The R session information (including the OS info, R version and all
packages used):


```r
sessionInfo()
```

```
## R version 3.2.2 (2015-08-14)
## Platform: x86_64-apple-darwin13.4.0 (64-bit)
## Running under: OS X 10.10.3 (Yosemite)
## 
## locale:
## [1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## other attached packages:
## [1] knitr_1.13
## 
## loaded via a namespace (and not attached):
##  [1] magrittr_1.5       formatR_1.2.1      htmltools_0.3     
##  [4] tools_3.2.2        base64enc_0.1-3    yaml_2.1.13       
##  [7] stringi_1.0-1      rmarkdown_0.9.6.14 highr_0.5.1       
## [10] stringr_1.0.0      digest_0.6.9       evaluate_0.9
```

```r
Sys.time()
```

```
## [1] "2016-10-08 21:25:59 AEST"
```

