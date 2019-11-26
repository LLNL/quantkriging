
Quantile Kriging is a method to model the uncertainty of a stochastic simulation by modelling both the overall simulation response and the output distribution at each sample point.  The output distribution is characterized by dividing it into quantiles, where the division of each quantile is determined by kriging.  
This library is our re-implementation of Quantile Kriging as described by Matthew Plumlee & Rui Tuo in their 2014 paper "Building Accurate Emulators for Stochastic Simulations via Quantile Kriging."  With computational savings when dealing with replication from the recent paper "Practical heteroskedastic Gaussian process modeling for large simulation experiments " by Binois, M., Gramacy, R., and Ludovski, M. it is now possible to apply Quantile Kriging to a wider class of problems.  In addition to fitting the model, other useful tools are provided such as the ability to automatically perform leave-one-out cross validation.

Getting Started
----------------
Quantkriging can be downloaded and installed inside of RStudio by using the devtools package.  If you do not have the devtools package run:
> install.package("devtools")

once devtools is installed, run:
> library(devtools)
> install_github("kquinlan/quantkriging")


Documentation
----------------

Documentation is included in the package.  It can be viewed in RStudio with the command: help(quantkriging)

Contributing
------------------------
Just send us a [pull request](https://help.github.com/articles/using-pull-requests/). 

Authors
----------------

This implementation of quantile kriging was developed by Kevin Quinlan, quinlan5@llnl.gov.


Licenses
----------------

quantkriging is distributed under the terms of the MIT license

See [LICENSE](https://github.com/quantkriging/quantkriging/blob/develop/LICENSE), and
[NOTICE](https://github.com/quantkriging/quantkriging/blob/develop/NOTICE) for details.

SPDX-License-Identifier: MIT

LLNL-CODE-796243
Title: Quantkriging (Quantile Kriging R Package) , Version: 0.1.0
Author(s) Kevin R. Quinlan, James R. Leek
