# Large Bayesian VARs for Binary, Censored and Count Variables
Joshua C.C. Chan, Davide Pettenuzzo, Michael Pfarrhofer, Aubrey Poon and Dan Zhu

### Abstract

We extend the vector autoregression (VAR) to model binary, censored, count and unrestricted variables jointly, treating missing observations of any type in the same way. Each restricted observation is linked to a latent Gaussian variable, so that the standard machinery for VARs, such as shrinkage priors, stochastic volatility and outlier components, applies directly to the VAR for the latent variables. The latent variables have a truncated normal conditional distribution with a banded precision matrix, from which they are drawn, jointly or equation by equation, using Hamiltonian Monte Carlo, and the sampler scales well to high dimensions. A simulation study shows that treating restricted variables as continuous distorts the levels and scales of the system and worsens forecasts of the restricted outcomes in most designs. In an application to 25 US macro-financial variables, we estimate a business cycle indicator, the intensity of banking distress and shadow rates. We use the model for scenario analysis with restrictions on the recession probability, bank failures and interest rates at the effective lower bound.

## Description
This repository is reserved for the code and replication files accompanying the paper. It is a placeholder for now; replication materials will be added later.

> This code comes without technical support of any kind. The code is free to use, provided that the paper is cited properly.


