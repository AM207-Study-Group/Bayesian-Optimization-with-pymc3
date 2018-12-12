# Bayesian Optimization with pymc3

Repeat and explain how Bayesian Optimization works, according to the following 2012 paper:
https://papers.nips.cc/paper/4522-practical-bayesian-optimization-of-machine-learning-algorithms.pdf
Practical Bayesian Optimization of Machine Learning Algorithms
By Jasper Snoek, Hugo Larochelle and Ryan P. Adams

Unlike the existing projects like SpearMint (https://github.com/HIPS/Spearmint), we use the pymc3 as our sampler, which is generally stable and pretty efficient module for Bayesian statistics sampling. The reason why we need a sampler in building Gaussian Process will be introduced with details in our tutorial.
