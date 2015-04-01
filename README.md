# stcm

Social scientists have become increasingly interested in the development and application of Set-Theoretic Comparative Methods for social inquiry. These methods --- notably Qualitative Comparative Analysis (QCA) --- are distinguished from other methods by their set-based variable codings, use of boolean reduction algorithms, and common application to small- and medium-N datasets. Recent methodological work has shown, however, that their results can be especially sensitive to small changes in certain calibration and reduction parameters, as well as the presence measurement error or model-specification error. The **stcm** package introduces a number of tools that are designed to help users of these methods assess the sensitivity of their results to a variety of perturbations. The package also introduces a set of functions implementing a related class of methods that relies centrally on classification and regression tree algorithms.

## Installation

To download from github:

```R
# install.packages("devtools")
devtools::install_github("ckrogs/stcm")
```

