# Package Title: maxSiyu

Original R package written by Siyu Zou.

Website built by Siyu Zou.

URL to the [GitHub link](https://github.com/zsyfirst/Project3_pkgdown_SiyuZou.git) where the original R package came from

URL to the [deployed website](https://zsyfirst.github.io/Project3_pkgdown_SiyuZou/)

The goal of maxSiyu is to calculate the maximum and minimum value of variables

## Installation

You can install the development version of maxSiyu from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("zsyfirst/Project3_pkgdown_SiyuZou")
```

## Customized in the pkgdown website
1. Home page of the pkgdown site is generated from the package's README.md.Include customized content, such as an introduction to the package, examples, and how to installation.
2. theme: minty
3. navbar: title, left, right
4. front: google:
        - Fira Sans
        - sans-serif
5. params:
    bootswatch: flatly
    bslib:
      bg: '#f8f9fa'
      fg: '#212529'
      primary: '#0d6efd'
      
      
## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(maxSiyu)
x <- rnorm(100, 1, 2)
maximum(x)
minimum(x)
```
