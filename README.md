# mixexp

Design and analysis of mixture experiments, including ternary contour plots and mixture effect plots.

Compatibility updates by Renova.

Version 1.2.7.1.9001 fixes an escaped ampersand in the `SLD` help page reference and removes the stale optional `Date` field from `DESCRIPTION`. No R function was changed.

## Install

```r
install.packages("mixexp", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/mixexp@renova-1.2.7.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

mixexp is by John Lawson (maintainer) and Cameron Willden, with a contribution from Greg Piepel; the original CRAN package is at <https://CRAN.R-project.org/package=mixexp>. See `citation("mixexp")`. License: GPL (>= 2); see [COPYING](COPYING).
