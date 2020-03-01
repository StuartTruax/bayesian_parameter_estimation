# Bayesian Parameter Estimation using Markov Chain Monte Carlo (MCMC)

by Stuart Truax

_initial commit: 2020-3_

This repo is a collection of jupyter notebooks for doing common Bayesian
parameter estimation and posterior prediction tasks using `pymc3`
as the MCMC solver.

Example tasks include:

 - Analysis of Variance (__ANOVA__) using Bayesian methods
 - Estimation of parameters for __Gaussian Mixture Models__
 - Generating __posterior predictive distributions__
 - Performing __logistic regression__ using Bayesian methods

 In each notebooks, some toy, random data will be generated and used as input
 to the MCMC solver. The random input data is parameterizable, which allows
 the user to see the effect of varying the parameters of the random input data
 on the results of the Bayesian estimation. For example, in ANOVA, varying the
 standard deviation of the level/group distributions will
 affect the p-value of the hypothesis test.


## Primary Requirements

 - `python 3.6`

 with the libraries:
```
pymc3
theano
```


## Useful Resources

A useful compendium of methods for improving MCMC estimation results:

 -  https://eigenfoo.xyz/bayesian-modelling-cookbook/
