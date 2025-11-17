---
title: Internships | Open Source Program Office
layout: job-listing
permalink: /activities/internships/lasso
job-title: Spike-and-Slab LASSO
job-link: https://studentjobs.hr.wisc.edu/cw/en-us/job/509741
---
### Project leader:
Sameer Deshpande, (sameer.deshpande@wisc.edu)

### Project description:
The LASSO (i.e., l1 regularization) is one of the most important methods
in modern statistics and machine learning, enabling practitioners to fit
high-dimensional models with more latent parameters than observations. From
the linear models that underpin genome-wide association studies to deep neural
network, l1 regularization is an indispensable tool in modern data science.
While some of the LASSO's popularity and ubiquity can be attributed to its
strong empirical performance and its favorable theoretical properties, a far
larger share is due to the availability of easy-to-use open-source software
implementations, notably the glmnet package in R.

Despite its success, the LASSO is known to struggle in settings with correlated
features and in more complicated problems involving multiple, possibly dependent
outcomes. Over the last decade has seen, an alternative penalty, known as the
spike-and-slab LASSO has emerged and proven to work somewhat better than the
LASSO in these challenging settings. Unlike the LASSO, which shrinks large and
small signals towards zero at exactly the same rate, the spike-and-slab LASSO
automatically and adaptively shrinks smaller signals to zero less aggressively
than larger signals. This often yields superior variable selection, lower
estimation error, and increased predictive accuracy. Unfortunately, development
of the spike-and-slab LASSO has occurred across several R package, which are
not inter-operable.

This project aims to unify these implementations into a new R package,
built around a single, shared C++ library. It will also involve creating
a package website (e.g., with [pkgdown](https://pkgdown.r-lib.org/)) containing documentation
and vignettes explaining how to use the main functions. Ultimately,
the goal is to create something akin to [glmnet](https://glmnet.stanford.edu/index.html) and its website
 but for spike-and-slab regularization.

The project will not involve developing or deriving any new statistical
algorithms. Instead, it will consist primarily in re-factoring existing C++
code, developing user-facing R wrapper functions, documentation, and creating
vignettes demonstrating the main operations.

### Intern needs:
Knowledge of R and version control with Git is required as is a willingness
to learn C++. Of course, previous experience with C++ would be beneficial.
Familiarity with l1 regularization would be useful but is not strictly
necessary.
