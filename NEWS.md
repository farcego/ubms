# ubms v1.0.2

* Fix issues in `sim_z` C++ code that triggered clang-UBSAN errors
* Adjust occuTTD test so it doesn't fail on Solaris
* Fix various issues with build on r-oldrel-macos-x86_64 

# ubms v1.0.1

* Added vignette comparing ubms and JAGS output
* Added configuration for pkgdown site
* Small adjustments to wording in DESCRIPTION and docs for CRAN submission

# ubms v0.1.9

* Add time-to-detection occupancy model (`stan_occuTTD`)
* Wrote examples for all fitting functions
* Many new tests added
* Wrote a vignette demonstrating random effects

# ubms v0.1.8

* Added distance-sampling model (`stan_distsamp`)
* Added multinomial-Poisson mixture model (`stan_multinomPois`)
* Wrote overview vignette

# ubms v0.1.4

* Added dynamic occupancy model (`stan_colext`)
* Consolidated single-season models into one Stan file to speed up compilation
* Using rasters as `predict` input is now supported
