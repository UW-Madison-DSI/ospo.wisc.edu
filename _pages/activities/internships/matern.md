---
title: Internships | Open Source Program Office
layout: job-listing
permalink: /activities/internships/matern
job-title: Matern Covariance
job-link: https://drive.google.com/file/d/1jJ6wABKsPerw5le3Mtw9WySkMhAAYC2f/view
---
### Project leader:
Chris Geoga, (geoga@wisc.edu)

### Project description:
The project mentor has a library for fast evaluation of the Matern covariance
function _and_ its derivatives, including with respect to the smoothness
parameter. This originally stemmed from a paper they wrote a few years ago about
using autodiff to accurately differentiate the Matern function with respect to
the smoothness parameter, which is not possible in closed form without using
generalized confluent hypergeometric functions. But this is a problem, because
as the theory around fixed-domain asymptotics for Gaussian processes indicates
this parameter is quite likely the most important one to be fitting.

The original code that they wrote was in Julia, but predictably many people
have indicated that they would like to use it but would only do so if it were
available in R/python. With this in mind, we've translated and enhanced the
routines to get a minimal viable product, and in order to end up with GCC-able
code we've also developed a very ornate pipeline that differentiates the
routines using Enzyme, which works on LLVM IR, and then actually compiles the
LLVM IR back to gcc-able C so that it can be used by languages like R which do
not permit packages to enforce the use of a specific C compiler.

Longer term, the goal is for this library to offer (1) by far the fastest Matern
covariance evaluation routines, (2) derivatives with respect to all parameters
that are accurate to double precision and fast, and (3) extensions involving
smarter parameterizations of geometric anisotropy and other enhancements
that can serve as a backbone for casual users of front-end languages like R
and Python. As of now, (1) and (2) are largely done, although the mentor is
continually interested to find improvements for the runtime and algorithmic
strategies of evaluating the Matern function. The mentor's ultimate ambition is
to get within the cost of three exp evaluations...although we'll have to see if
that will ever happen.

An intern could contribute to this project by:
1. Packaging code up neatly in R and python packages
2. Developing and enhancing an automated testing suite for all three major OSes
3. Developing a robust build process, which is complex because the Enzyme AD
   engine is unstable and the LLVM C backend is only an unofficially maintained
   target that is kept alive by some Julia developers (of all people).
4. Micro-optimizing current code
5. Potentially implementing new routines and numerical strategies

### Intern needs:
Students who are comfortable with the C programming language and low-level code
optimization and debugging would be the best fit. For performance optimization,
we are talking about shaving off nanoseconds, so it would be best for students
to be interested in low-level programming and optimization as well as floating
point arithmetic. For testing and distribution, a good understanding of Github
pipelines and automated workflows would be ideal.
