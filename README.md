# 1701-gefcom

Code for the paper:

Roach, Cameron. 2018. “Reconciled Boosted Models for GEFCom2017 Hierarchical Probabilistic Load Forecasting.” International Journal of Forecasting. https://doi.org/10.1016/j.ijforecast.2018.09.009.

This was my first attempt at using R markdown and R packages for producing papers. As such it isn't exactly my tidiest piece of work, but it should still be useful for anyone attempting to replicate the results.

In addition to this repository, you will require the [gefcom2017](https://github.com/camroach87/gefcom2017) R package which you can install by running

```r
install.packages("devtools")
library(devtools)
install_github("camroach87/gefcom2017")
```

Since the paper's acceptance, I have also released a tidied version of the data available in the [gefcom2017data](https://github.com/camroach87/gefcom2017data) repository. This should make working with the data considerably easier.
