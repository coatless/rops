
[![Project Status: Active - The project has reached a stable, usable
state and is being actively
developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Travis-CI Build
Status](https://travis-ci.org/coatless/rops.svg?branch=master)](https://travis-ci.org/coatless/rops)
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/rop)](https://cran.r-project.org/package=rops)
[![CRAN RStudio mirror
downloads](http://cranlogs.r-pkg.org/badges/rops)](http://www.r-pkg.org/pkg/rops)
[![Coverage
Status](https://img.shields.io/codecov/c/github/coatless/rops/master.svg)](https://codecov.io/github/coatless/rops?branch=master)

# R Ops (`rops`)

The objective behind this package is to provide an extension to base *R*
that supplements present operators manipulations.

# Supported Functionality

Presently, the package has support for the following operators:

  - [Null coalescing
    operator](https://en.wikipedia.org/wiki/Null_coalescing_operator):
    `%??%`
      - Operator to allow checking and substitution if a value is null
        without `if`/`else` structure
  - Missing value (`NA`) coalescing operator: `ifna(x, y)`
      - Substitute value when NA is detected.
  - [Is Whole Number](https://en.wikipedia.org/wiki/Integer):
    `is_whole(x)`
      - Vectorized boolean operator to assess whether value is an
        integer.
  - Safe Sequence Generation: `from %:% to`, `safe_seq(from, to, by)`
  - Not In Set: `%notin%`
