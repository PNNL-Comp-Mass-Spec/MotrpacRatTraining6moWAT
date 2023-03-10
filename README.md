
<!-- README.md is generated from README.Rmd. Please edit that file -->

# MotrpacRatTraining6moWAT

A collection of functions for the analysis and visualization of the
MoTrPAC PASS1B white adipose tissue (WAT) data as provided in the
<a href="https://motrpac.github.io/MotrpacRatTraining6moData/index.html">MotrpacRatTraining6moData</a>
package. This package was built specifically to generate the
MotrpacRatTraining6moWATData package, so much of it is tailored only for
use with those datasets, though users may find some of the functionality
contained herein to be useful in other projects:

- Differential analysis (DA) with the
  <a href="https://bioconductor.org/packages/release/bioc/html/limma.html">limma</a>
  and
  <a href="https://bioconductor.org/packages/release/bioc/html/edgeR.html">edgeR</a>
  packages
- Fast Gene Set Enrichment Analysis (FGSEA) with
  <a href="https://bioconductor.org/packages/release/bioc/html/fgsea.html">fgsea</a>
  and
  <a href="https://cran.r-project.org/web/packages/msigdbr/index.html">msigdbr</a>
- Kinase-Substrate Enrichment Analysis (KSEA) with
  <a href="https://www.phosphosite.org/homeAction.action">PhosphoSitePlus</a>
- Over-representation analysis (ORA)
- Weighted Gene Co-expression Network Analysis (WGCNA)

## Installation

Install this package with `devtools`:

``` r
if (!require("devtools", quietly = TRUE)) {
  install.packages("devtools")
}
devtools::install_github("PNNL-Comp-Mass-Spec/MotrpacRatTraining6moWAT")
```
