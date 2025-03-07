# SHT 0.1.9

* Corrected an error in `eqdist.2014BG()` thanks to [Wolfgang Rolke](https://academic.uprm.edu/wrolke/) at UPR.

# SHT 0.1.8

* Added tests of uniformity on the probability simplex.

# SHT 0.1.7

* Replaced CLIME estimation algorithm for `mean2.2014CLX()` with cross validation.
* Changed the default setting for `cov2.2012LC()`.

# SHT 0.1.6

* Fixed an error in `mean2.2014CLX()` in case of adaptive thresholding estimate used.
* New methods added; `sim1.LRT()`.
* Option for `cov2.2012LC()` is changed for clarity.
* Default parameters are changed for `mean2.mxPBF()`.

# SHT 0.1.5

* Fixed critical errors in `cov2.2012LC()`.
* In `mean2.2014CLX()`, support for an adaptive thresholding estimator is added for a case with non-sparse precision matrix.

# SHT 0.1.4

* Fixed an error in `cov2.2012LC()` function.

# SHT 0.1.3

* Defensive protection for OpenMP. 

# SHT 0.1.2

* Corrected example's multiline display of simulation results.
* Change of maintainer's contact.
  
# SHT 0.1.1

* Functions are added, a lot.
* `README` invisible on CRAN. Later we'll add vignette.
  
# SHT 0.1.0

* Package is first deployed.
* Initialize the following documentation:
  - `NEWS` for keeping record of updates.
  - `README` to briefly introduce the method.
