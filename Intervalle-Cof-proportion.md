# A test script for the function stitch()



This report was automatically generated with the R package **knitr**
(version 1.13).


```r
mat <- matrix(c(55,145,35,65),byrow=T,ncol=2,nrow=2)
rownames(mat) <- c("Homme","Femme")
colnames(mat) <- c("Fumeur","Non Fumeur")
prop.test(mat,conf.level=0.95,correct=FALSE)->res
res$conf.int
```

```
## [1] -0.18711054  0.03711054
## attr(,"conf.level")
## [1] 0.95
```

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
##  [1] magrittr_1.5       formatR_1.2.1      markdown_0.7.7    
##  [4] htmltools_0.3      tools_3.2.2        base64enc_0.1-3   
##  [7] yaml_2.1.13        stringi_1.0-1      rmarkdown_0.9.6.14
## [10] highr_0.5.1        stringr_1.0.0      digest_0.6.9      
## [13] mime_0.4           evaluate_0.9
```

```r
Sys.time()
```

```
## [1] "2016-10-08 21:26:37 AEST"
```

