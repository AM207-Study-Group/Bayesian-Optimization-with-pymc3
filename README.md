# Bayesian Optimization with pymc3

This is a paper-reproducing project for AM207 in 2018 Fall.
Check our course website for more info: http://am207.info/

We repeated and explained how Bayesian Optimization works, according to the following 2012 paper:
https://papers.nips.cc/paper/4522-practical-bayesian-optimization-of-machine-learning-algorithms.pdf
Practical Bayesian Optimization of Machine Learning Algorithms
By Jasper Snoek, Hugo Larochelle and Ryan P. Adams

Unlike the existing projects like SpearMint (https://github.com/HIPS/Spearmint), we're using the pymc3 as our sampler, which is generally stable and pretty efficient module for Bayesian statistics sampling. The reason why we need a sampler in building Gaussian Process will be introduced with details in our tutorial.

We would be glad if this tutorial helps anyone.
