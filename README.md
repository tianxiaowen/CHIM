README
================
Xiaowen Tian
7/22/2019

CHMIpower
=========

<!-- badges: start -->
<!-- badges: end -->
The goal of CHMIpower is to perform power calculation for designs of Controlled Human Malaria Infection studies.

Installation
------------

You can install the released version of CHMIpower from <https://github.com/tianxiaowen/CHMI/blob/master/CHMIpower_0.0.0.9000.tar.gz>.

Please install package dependencies first.

``` r
packages <- c("survival","beeswarm","MASS","stats","graphics","grDevices")
if (length(setdiff(packages, rownames(installed.packages()))) > 0) {
  install.packages(setdiff(packages, rownames(installed.packages())))  
}
install.packages("pathname/CHMIpower_0.0.0.9000.tar.gz", repos = NULL, type = "source")
```

General setup
-------------

https://tianxiaowen.github.io/CHMI/README.html
